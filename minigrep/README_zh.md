Translations: [English](README.md) | [简体中文](README_zh.md)

## 关于 minigrep

> minigrep 是由 rust 实现的 mini grep.

## 使用

```shell
[ignore_case] cargo run -- [query] [file_path]
```

```shell
cargo run -- to test_data/test.txt
```

或者

```shell
IGNORE_CASE=1 cargo run -- to test_data/test.txt
```

## 致谢

minigrep 代码来自 [rust-course](https://course.rs/basic-practice/intro.html).

- [rust-course](https://github.com/sunface/rust-course).

更强大的 grep, 可以查看[ripgrep](https://github.com/BurntSushi/ripgrep)
