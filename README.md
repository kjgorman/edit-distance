
# edit-distance

[![Build Status](https://travis-ci.org/febeling/edit-distance.svg)](https://travis-ci.org/febeling/edit-distance)
[![](http://meritbadge.herokuapp.com/edit-distance)](https://crates.io/crates/edit-distance)

Calculate Levenshtein distance between two strings.

The Levenshtein edit distance is a measure for the similarity between
two strings. It's helpful for spelling correction, fuzzy completion,
type-ahead and similar use cases.

This implementation supports Unicode.

## Installation

In Cargo.toml add

```toml
[dependencies]
edit-distance = "^1.0.0"
```

Then re-run `cargo build`. That fetches the dependencies and builds
the code.

## Usage

```rust
extern crate edit_distance;

edit_distance("kitten", "sitting"); // => 3
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

2015-05-01 1.0.0 Release  
2015-04-18 0.0.1 Initial upload

## Credits

Thanks to @skade for very helpful criticism of my first rust lib.

## License

APL 2.0, see LICENSE file.
