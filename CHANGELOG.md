# Change Log
All notable changes to this project will be documented in this file.

## [0.3] - 2015-09-22
### Changed
- Exact match numeric types to spec.
- Names follow now the spec.
- AST slightly different for better readability or easier parsing.
- Replace golden test for test to validate parsing/encoding.

### Added
- Parsing errors in all cases where `Alternative` is used.
- GraphQL encoder.

### Fixed
- Expect braces `inputValueDefinitions` instead of parens when parsing.

## [0.2.1] - 2015-09-16
### Fixed
- Include data files for golden tests in Cabal package.
- Support for ghc-7.8.

## [0.2] - 2015-09-14
### Added
- Rudimentary parser for `GraphQL` which successfully parses the sample file
  `kitchen-sink.graphql` from `graphql-js` tests.
- Golden test for `kitchen-sink.grahql` parsing.
### Changed
- Many optional data types in `GraphQl` didn't need to be wrapped in a `Maybe`.
- Some `newtype`s became type synonyms for easier parsing.

## 0.1 - 2015-09-12
### Added
- Data types for the GraphQL language.

[0.3]: https://github.com/jdnavarro/graphql-haskell/compare/v0.2.1...v0.3
[0.2.1]: https://github.com/jdnavarro/graphql-haskell/compare/v0.2...v0.2.1
[0.2]: https://github.com/jdnavarro/graphql-haskell/compare/v0.1...v0.2
