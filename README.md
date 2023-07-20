# potato

A stricter typed dialect of python

### What's this?

This is a stricter dialect of python with a strong type system (sort of like typescript for javascript), written in rust
and aims to have performance gains while still retaining the simple syntax of python.

### Features (HEAVILY WIP!)

- LLVM Backend
- Strong type system
- Written in rust
- Nice errors :)

### Running

```
git clone https://github.com/KittyBorgX/potato.git
cd potato
cargo build --release
./target/release/potato test.py # Assuming your file is `test.py`
```
