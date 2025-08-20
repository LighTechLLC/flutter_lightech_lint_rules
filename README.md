# Flutter Linter Rules

A comprehensive set of strict linting rules for Flutter projects to enforce LighTech's best practices and coding standards.

## 📦 Installation

Add `flutter_lightech_lint_rules` as a dev dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  flutter_lightech_lint_rules:
    git:
      url: git@github.com:LighTechLLC/flutter_lightech_lint_rules.git
      ref: 1.1.0  # Use specific version for stability
```

## 🚀 Setup

Include the lint rules in your `analysis_options.yaml`:

```yaml
include: package:flutter_lightech_lint_rules/analysis_options.yaml
```

### Customizing Rules

You can override specific rules if needed:

```yaml
include: package:flutter_lightech_lint_rules/analysis_options.yaml

linter:
  rules:
    # Disable specific rule
    lines_longer_than_80_chars: false
    # Enable additional rule
    prefer_single_quotes: true
```

## 📋 What's New

See [CHANGELOG.md](CHANGELOG.md) for detailed version history and migration guides.

## Contributing

We welcome contributions! If you have ideas for new rules or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/LighTechLLC/flutter_lightech_lint_rules/blob/main/LICENSE) file for details.

---

This README provides an overview of the package, how to install it, set it up, and a brief description of what it does. Make sure to customize the links and names with the actual information from your project.