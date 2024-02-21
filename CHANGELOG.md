# Changelog

## [0.0.1] - 2024-02-20

### Added

- Initial release.

## [0.0.2] - 2024-02-21

### Added

- Added `contrib/waitgroup`.
- Partial unit test coverage for `run.go`.
- Some additional code comments on `runnable.Run`.

### Fixed

- Fixed syntax error in `group_test.go`.
- Wait until `n` messages come across `closeCh`, not `n-1`. This was a copy/paste issue.