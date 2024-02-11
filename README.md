# aarch64-dep-reproducer

This repository reproduces a bug in flatpak-poetry-generator where aarch64
wheels may be picked despite these only working on aarch64 (64-bit ARM),
resulting in manifests which do not build on x86\_64.

Issue: https://github.com/flatpak/flatpak-builder-tools/issues/396
