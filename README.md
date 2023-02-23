# Rusted Project Template

This is a template to get new Rust projects started.

## Config

Copy the contents of `config/vscode` into the `.vscode` directory. This will
enable the Rust LSP.

Update rust_rules with the [latest version](https://github.com/bazelbuild/rules_rust/releases)

Update the `cargo.bazel.lock` running:

```sh
CARGO_BAZEL_REPIN=true bazel build //...
```
