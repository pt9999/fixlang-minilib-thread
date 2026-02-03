
## 0.6.0
### Changed
- Some functions that return `IO` or `IOFail` monads now use `MonadIO` or `MonadIOFail`.
- `Minilib.Thread.TaskPool`: `TaskPool` is now boxed.
