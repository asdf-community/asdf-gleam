# asdf-gleam

[![Build Status](https://travis-ci.org/vic/asdf-gleam.svg?branch=master)](https://travis-ci.org/vic/asdf-gleam)

[Gleam](https://github.com/gleam-lang/gleam) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager


## Install

> *Gleam runtime depends on Erlang. You might need to install it using asdf-erlang.
> For using gleam libraries you might also need `rebar3`. It is installable via asdf-rebar.

```
asdf plugin-add gleam https://github.com/vic/asdf-gleam.git
```

Since `0.2.0`, Gleam has binary releases for macos and linux.

```
# To install a binary release, just specify it
asdf install gleam 0.2.0
```


If you want to build from source. Use

```shell
# Installing from source needs Rust. You might want to install it using asdf-rust.
# Using `ref:`, you can specify any branch, tag (like `v0.2.0`) or commit-sha
asdf install gleam ref:main
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Gleam.
