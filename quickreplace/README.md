# quickreplace

Replaces substring in file, writing to new file.

## Usage

cargo run <search_string> <replacement> <INPUT> <OUTPUT>

```text
echo "Hello, world" > test.txt
cargo run "world" "Rust" test.txt test-modified.txt
cat test-modified.txt
```
