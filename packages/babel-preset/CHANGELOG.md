# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.0.1](https://github.com/smooth-code/svgr/compare/v4.0.0...v4.0.1) (2018-11-08)

**Note:** Version bump only for package @svgr/babel-preset





# [4.0.0](https://github.com/smooth-code/svgr/compare/v3.1.0...v4.0.0) (2018-11-04)


### Features

* **v4:** new architecture ([ac8b8ca](https://github.com/smooth-code/svgr/commit/ac8b8ca))
* allow dynamic properties in replaceAttrValues option ([15f55fe](https://github.com/smooth-code/svgr/commit/15f55fe)), closes [#205](https://github.com/smooth-code/svgr/issues/205)


### BREAKING CHANGES

* **v4:** - `template` option must now returns a Babel AST
- `@svgr/core` does not include svgo & prettier by default
