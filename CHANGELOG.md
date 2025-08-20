## 1.1.0

### Added
- `strict_top_level_inference` - Enforces type inference for top-level variables (from flutter_lints 6.0.0)
- `unnecessary_underscores` - Removes unnecessary underscores in identifiers (from flutter_lints 6.0.0)
- `avoid_futureor_void` - Prevents using FutureOr<void> type which can be confusing
- `require_trailing_commas` - Enforces trailing commas for better formatting and diffs

### Changed
- `always_put_control_body_on_new_line`: false → true - Improves code readability
- `avoid_final_parameters`: true → false - Too restrictive for most codebases
- `prefer_final_parameters`: removed - Conflicted with avoid_final_parameters

### Removed
- `prefer_const_constructors` - Removed in flutter_lints 5.0.0
- `prefer_const_declarations` - Removed in flutter_lints 5.0.0
- `prefer_const_literals_to_create_immutables` - Removed in flutter_lints 5.0.0
- `library_names` - Removed in flutter_lints 4.0.0
- `package_prefixed_library_names` - Removed in flutter_lints 4.0.0

### Fixed
- Compatibility with flutter_lints 6.0.0
- Removed deprecated and conflicting rules

## 1.0.0

- Initial release