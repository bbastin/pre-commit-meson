# pre-commit-meson
Integrate [meson tests](https://mesonbuild.com/Unit-tests.html) with [pre-commit](https://pre-commit.com/).

This hook runs all tests registered with meson. It assumes that the build folder is named `build/`.
