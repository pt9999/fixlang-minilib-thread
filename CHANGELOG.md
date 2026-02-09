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
