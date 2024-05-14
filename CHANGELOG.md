# Changelog

## [0.4.2](https://github.com/statnett/github-workflows/compare/v0.4.1...v0.4.2) (2024-05-14)


### Bug Fixes

* use new project location for release-please-action ([#85](https://github.com/statnett/github-workflows/issues/85)) ([3f4c0ee](https://github.com/statnett/github-workflows/commit/3f4c0ee79d4647b99e5b296e97b771a79e4a9963))

## [0.4.1](https://github.com/statnett/github-workflows/compare/v0.4.0...v0.4.1) (2023-12-14)


### Bug Fixes

* don't use digests for CodeQL actions ([#66](https://github.com/statnett/github-workflows/issues/66)) ([3fd128f](https://github.com/statnett/github-workflows/commit/3fd128fd4def0f7938e90fc6f7f4fde8a3f45db3))
* ensure CodeQL runs with correct Go version ([#64](https://github.com/statnett/github-workflows/issues/64)) ([4bad1b8](https://github.com/statnett/github-workflows/commit/4bad1b83045a36fee8a4b872312c720001f86a1d))

## [0.4.0](https://github.com/statnett/github-workflows/compare/v0.3.1...v0.4.0) (2023-12-11)


### ⚠ BREAKING CHANGES

* remove use of deprecationMessage (does not work) ([#52](https://github.com/statnett/github-workflows/issues/52))
* migrate clean-ghcr workflow to use GH token ([#50](https://github.com/statnett/github-workflows/issues/50))

### Features

* add manifest-file input to release-please workflow ([#51](https://github.com/statnett/github-workflows/issues/51)) ([df7c32f](https://github.com/statnett/github-workflows/commit/df7c32f3e0c7ec927f00cc2ac39543ab91bb811d))
* migrate clean-ghcr workflow to use GH token ([#50](https://github.com/statnett/github-workflows/issues/50)) ([8de53b8](https://github.com/statnett/github-workflows/commit/8de53b8af8d2156b3b98ca0c12f029666a0b2c75))


### Bug Fixes

* remove use of deprecationMessage (does not work) ([#52](https://github.com/statnett/github-workflows/issues/52)) ([b29384f](https://github.com/statnett/github-workflows/commit/b29384f2054633f63e93016dcfa8587aae4366cf))

## [0.3.1](https://github.com/statnett/github-workflows/compare/v0.3.0...v0.3.1) (2023-12-06)


### Reverts

* "chore(deps): update google-github-actions/release-please-action action to v4" ([#45](https://github.com/statnett/github-workflows/issues/45)) ([69d81b6](https://github.com/statnett/github-workflows/commit/69d81b6d2d711aff0bc0546e24d180ff80672ea2))

## [0.3.0](https://github.com/statnett/github-workflows/compare/v0.2.0...v0.3.0) (2023-10-10)


### Features

* add reusable scorecard workflow ([#22](https://github.com/statnett/github-workflows/issues/22)) ([09472b5](https://github.com/statnett/github-workflows/commit/09472b511fbf37689f14e1dd1e3f57d4c19db24d))


### Bug Fixes

* content read by default ([#26](https://github.com/statnett/github-workflows/issues/26)) ([bc7d1d1](https://github.com/statnett/github-workflows/commit/bc7d1d182341432ad606b73e446824b12901eb77))
* install newer Java if CodeQL run with Java ([#29](https://github.com/statnett/github-workflows/issues/29)) ([30e8f56](https://github.com/statnett/github-workflows/commit/30e8f56c940a7c0aa4f77ab67e8c1c433f6b0904))
* no workflow default permissions ([#30](https://github.com/statnett/github-workflows/issues/30)) ([e4fac84](https://github.com/statnett/github-workflows/commit/e4fac84eba004c101651a7dac85ca2af716ede61))

## [0.2.0](https://github.com/statnett/github-workflows/compare/v0.1.0...v0.2.0) (2023-10-09)


### Features

* new reusable CodeQL workflow ([#19](https://github.com/statnett/github-workflows/issues/19)) ([e482882](https://github.com/statnett/github-workflows/commit/e482882b4a649ea32a058302a724c3ab6754ae80))


### Bug Fixes

* correct syntax to obtain output variables ([#20](https://github.com/statnett/github-workflows/issues/20)) ([7807616](https://github.com/statnett/github-workflows/commit/78076161d9adf287e00ef2134cc90ae5ce365b37))

## [0.1.0](https://github.com/statnett/github-workflows/compare/v0.0.0...v0.1.0) (2023-10-06)


### Features

* new extra-files input to release-please workflow ([#17](https://github.com/statnett/github-workflows/issues/17)) ([b9be85c](https://github.com/statnett/github-workflows/commit/b9be85c49b5e527b95f4dcc94b81d92a2288d59c))


### Bug Fixes

* changes after QA of workflow permissions ([#13](https://github.com/statnett/github-workflows/issues/13)) ([31b6573](https://github.com/statnett/github-workflows/commit/31b6573aaafab2f9a04c32d7f0c3b323eeed299d))
* ensure all actions use exact digest version ([#12](https://github.com/statnett/github-workflows/issues/12)) ([8546bfc](https://github.com/statnett/github-workflows/commit/8546bfc634d3277688121b9ae7d49a27822ff885))
