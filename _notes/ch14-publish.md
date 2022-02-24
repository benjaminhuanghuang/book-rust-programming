build release
```
  cargo build --release
```

## release profile in cargo.toml
```
  [profile.dev]
  opt-level = 0

  [profile.release]
  opt-level = 3
```

## doc
Doc comments use three slashes `///`, support Markdown notation
```
  ///
```
open doc
```
  cargo doc --open
```

## Publish
```
  
```