# Contributing

Use PHP 8.4 or later and Composer. Run `composer install`, then:

```sh
composer qa
composer coverage
```

QA runs PHPStan, PHP CS Fixer in dry-run mode, and PHPUnit. Coverage requires
PCOV or Xdebug in coverage mode and enforces 100% line coverage. Use
`composer cs-fix` to apply formatting.

For parser changes, test accepted and rejected syntax, source-byte offsets,
line and column diagnostics, and scalar types. Preserve the documented strict
subset rather than silently accepting unsupported YAML. For rendering changes,
check complete fences and body joining. Update the [docs](docs/index.md) and
changelog for public behavior changes.
