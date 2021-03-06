# now-rust changelog

## Unreleased

## 2.0.0

Big thanks to [ekadas](https://github.com/ekadas) for [fixing a ton of issues](https://github.com/mike-engel/now-rust/pull/19)!

### Breaking changes

- OpenSSL is no longer installed by default
- Platform version 1 is no longer supported
- `Cargo.toml` is no longer a valid entrypoint

### Bug fixes

- `now dev` is now 100% functional :tada:

## 1.0.1

### New features

- Support for version 3 of Runtimes [#14](https://github.com/mike-engel/now-rust/pull/14)

## 0.2.6

### New features

- Rust will be installed through a now lifecycle hook in `package.json` rather than by the builder [#5](https://github.com/mike-engel/now-rust/pull/5)

## 0.2.5

This is the initial release as a community-maintained repository. It includes all the existing data from the old official builder as well as the docs from the zeit builder page.

For previous version, please see the [official builder](https://github.com/zeit/now-builders) repo.
