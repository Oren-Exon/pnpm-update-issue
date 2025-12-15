# pnpm update issue

## How to reproduce

run `pnpm update`

### Expected Result

should update catalog>express4-21>express to latest "~4.21.X"

### Actual Result

updates catalog>express4-21>express to latest "^4.21.X"

which in turn causes future `pnpm update` to update minor version!
