# build_parser_by_cherniavskyi

An educational Rust crate that demonstrates how to build a simple list parser using the [`peg`](https://crates.io/crates/peg) library.

## Example

```rust
use build_parser_by_cherniavskyi::*;

fn main() {
    println!("{:?}", list_parser::list("[1,1,2,3,5,8]"));
}
