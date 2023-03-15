svgo mirror
================

Mirror of svgo package for pre-commit.

For pre-commit: see <https://github.com/pre-commit/pre-commit>

For svgo: see <https://github.com/svg/svgo>

### Using svgo with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/UnknownPlatypus/mirrors-svgo
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: svgo
```
