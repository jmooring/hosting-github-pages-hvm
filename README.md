# Hosting Test - GitHub Pages with Hugo Version Manager

This is a test of hosting a Hugo project on GitHub Pages in conjunction with the [Hugo Version Manager][].

The version management logic is implemented in the GitHub Actions workflow. Specifically, it overrides the default `HUGO_VERSION` and `HUGO_EDITION` using the values found in the `.hvm` file if present.

All components are imported from the [`jmooring/hugo-module-feature-test`][] module. See its [README][] file for details.

[`jmooring/hugo-module-feature-test`]: https://github.com/jmooring/hugo-module-feature-test
[README]: https://github.com/jmooring/hugo-module-feature-test?tab=readme-ov-file#readme
[Hugo Version Manager]: https://github.com/jmooring/hvm/
