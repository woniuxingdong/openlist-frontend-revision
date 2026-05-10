# Customized OpenList frontend

![License MIT](https://img.shields.io/badge/license-MIT-green)

Based on OpenList frontend of version 4.2.1.

## BUILD

You can use [the build script](./build.sh).

```plaintext
Usage: ./build.sh [--dev|--release] [--compress|--no-compress] [--enforce-tag] [--skip-i18n] [--lite]

Options (will overwrite environment setting):
  --dev         Build development version
  --release     Build release version (will check if git tag match package.json version)
  --compress    Create compressed archive
  --no-compress Skip compression
  --enforce-tag Force git tag requirement for both dev and release builds
  --skip-i18n   Skip i18n build step
  --lite        Build lite version

Environment variables:
  OPENLIST_FRONTEND_BUILD_MODE=dev|release (default: dev)
  OPENLIST_FRONTEND_BUILD_COMPRESS=true|false (default: false)
  OPENLIST_FRONTEND_BUILD_ENFORCE_TAG=true|false (default: false)
  OPENLIST_FRONTEND_BUILD_SKIP_I18N=true|false (default: false)
```

## References

[OpenList](https://github.com/OpenListTeam/OpenList)
[OpenList frontend](https://github.com/OpenListTeam/OpenList-frontend)
