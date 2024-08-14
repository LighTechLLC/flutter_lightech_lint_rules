# Flutter Linter Rules

A set of linting rules for Flutter projects to enforce best practices and coding standards.

## Getting Started

### Installation

Add `flutter_lightech_lint_rules` as a dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  flutter_lightech_lint_rules:
    git:
      url: git@github.com:LighTechLLC/flutter_lightech_lint_rules.git
```

### Setup

To start using the linting rules, include them in your `analysis_options.yaml`:

```yaml
include: package:flutter_lightech_lint_rules/analysis_options.yaml
```

You can also override specific rules by adding them directly to your `analysis_options.yaml`:

```yaml
linter:
  rules:
    avoid_print: true
    # Add more custom rules here
```

### Example

Here's an example of how your `analysis_options.yaml` might look:

```yaml
include: package:flutter_lightech_lint_rules/analysis_options.yaml

linter:
  rules:
    avoid_print: true
    unnecessary_null_checks: false
```

## Rules Overview

The rules provided by `flutter_lightech_lint_rules` cover a wide range of areas:

- **Style Guidelines:** Rules for naming conventions, code organization, and formatting.
- **Best Practices:** Rules that encourage the use of effective patterns and discourage common pitfalls.
- **Error Prevention:** Avoid bugs and other issues before they occur.

## Contributing

We welcome contributions! If you have ideas for new rules or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/LighTechLLC/flutter_lightech_lint_rules/blob/main/LICENSE) file for details.

---

This README provides an overview of the package, how to install it, set it up, and a brief description of what it does. Make sure to customize the links and names with the actual information from your project.