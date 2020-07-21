# minigrep
Rust version of the classic command line tool grep

## Requirements
[Rust-lang](https://www.rust-lang.org/en-US/install.html) should be installed in
your system.

## Installation
```sh
git clone https://github.com/niranjana687/minigrep.git
cd minigrep
cargo build --release
```
## Usage
```sh
./target/release/minigrep -<options> nemo find-nemo-the-movie.txt
```

Example - `./target/release/minigrep -i nemo find-nemo-the-movie.txt`

### Allowed Options
```
i - Case-insensitive.
w - Exact match.
```

## Documentation
```sh
cargo doc --no-deps --open
```

## Run tests
```sh
cargo test
```

## Note
This is not a drop in replacement for the good old grep-like commands. This is
written for the sake of learning Rust-lang.


## What is differently done in `minigrep`?
- Case-insensitive search can be done by passing an option.
- Ability to do exact-match search.
- The query is highlighted in the output.

