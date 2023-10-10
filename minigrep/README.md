##### Translate to: [简体中文](README_zh.md)

## About minigrep

> The minigrep is a mini grep written by rust.

## Usage

```shell
[ignore_case] cargo run -- [query] [file_path]
```
```shell
cargo run -- to test_data/test.txt
```
or 
```shell
IGNORE_CASE=1 cargo run -- to test_data/test.txt
```

## Acknowledgments

The minigrep source code comes from [rust-course](https://course.rs/basic-practice/intro.html).

- [rust-course](https://github.com/sunface/rust-course).

For better grep, you can see [ripgrep](https://github.com/BurntSushi/ripgrep). 