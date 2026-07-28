## 0.8.0
### Changed
- Merged PR#2 (thanks to tttmmmyyyy san).
  - Migrate to the unboxed-Array standard library.
  - fixproj.toml: Bumped `fix_version` to 1.5.0.
- Upgraded to minilib-io@0.9.0, asynctask@2.0.0.

## 0.7.3
### Changed
- Upgraded to minilib-io@0.8.5, ring-buffer@0.1.2.
- Modified some code to remove the deprecation warnings.

## 0.7.1
### Changed
- Removed indirect dependencies.

## 0.7.0
### Changed
- Minilib.Thread.Channel: Now use `RingBuffer` as a queue instead of `Minilib.Collection.Deque`.
- fixproj.toml:
  - Bumped `fix_version` to 1.3.0.
  - Depends on minilib-common@0.12.0, minilib-io@0.8.0.
  - Added ring-buffer@0.1.1 to dependencies.
  - Removed minilib-collection from dependencies.

## 0.6.0
### Changed
- Some functions that return `IO` or `IOFail` monads now use `MonadIO` or `MonadIOFail`.
- `Minilib.Thread.TaskPool`: `TaskPool` is now boxed.
