# Drupal QA Tools

A comprehensive metapackage that bundles essential Quality Assurance (QA) tools and dependencies for Drupal development projects.

## Overview

This package provides a curated collection of development, testing, and quality assurance tools commonly used in Drupal projects. It simplifies the process of setting up a consistent development environment by installing all necessary QA dependencies in one go.

## Installation

To install this package, run:

```bash
composer require gnikolovski/drupal-qa --dev
```

## Included Tools

### Testing Frameworks
- **Behat**: Behavior-driven development framework
  - Includes Mink for web testing
  - BrowserKit Driver for headless testing
  - Chrome Extension for browser testing
  - Screenshot capability for debugging
  - Drupal Extension for Drupal-specific testing

### Code Quality
- **PHP_CodeSniffer via Drupal Coder**: Ensures code adheres to Drupal coding standards
- **PHPStan**: Static analysis tool
  - Drupal-specific rules
  - Deprecation rules
- **Drupal Rector**: Automated code upgrade tool
- **Twig CS Fixer**: Twig template coding standards

### Development Tools
- **Devel**: Suite of modules for Drupal development
  - Kint integration
  - Kint extras
  - PHP execution
- **Upgrade Status**: Drupal upgrade readiness checker

### Testing
- **PHPUnit**: Unit testing framework

## Requirements

- PHP 8.1 or higher
- Composer 2.x
- Drupal

## License

This project is licensed under GPL-2.0-or-later.

## Contributing

Issues and pull requests are welcome. Please follow Drupal coding standards when contributing.

## Credits

Maintained by [gnikolovski](https://www.drupal.org/u/gnikolovski)
