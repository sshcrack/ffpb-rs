# ffpb-rs

**Not smart. Not comprehensive. Not guaranteed to work.**

<p align="center">
  <img src="https://img.shields.io/github/downloads/clitic/ffpb-rs/total?style=flat-square">
  <img src="https://img.shields.io/github/release/clitic/ffpb-rs?style=flat-square">
  <img src="https://img.shields.io/github/license/clitic/ffpb-rs?style=flat-square">
  <img src="https://img.shields.io/github/repo-size/clitic/ffpb-rs?style=flat-square">
  <img src="https://img.shields.io/tokei/lines/github/clitic/ffpb-rs?style=flat-square">
</p>

ffpb-rs is rust implementation of [ffpb](https://github.com/althonos/ffpb).
ffpb is an ffmpeg progress formatter. It will attempt to display a nice progress bar in the output, based on the raw ffmpeg output, as well as an adaptative ETA timer.

![showcase](https://raw.githubusercontent.com/clitic/ffpb-rs/main/images/showcase.gif)

## Installations

Visit [releases](https://github.com/clitic/ffpb-rs/releases) for prebuilt binaries. You just need to copy that binary to any path specified in your `PATH` environment variable.

Or you can even install it through cargo.

```bash
cargo install --git https://github.com/clitic/ffpb-rs
```

## Usage

ffpb is is not even self-aware. Any argument given to the ffpb command is transparently given to the ffmpeg binary on your system, without any form of validation. So if you know how to use the ffmpeg cli, you know how to use ffpb.

```bash
ffpb --help
```

## Building From Source

- Install [Rust](https://www.rust-lang.org)

- Clone Repository

```bash
git clone https://github.com/clitic/ffpb-rs.git
```

- Build Release

```bash
cargo build --release
```

## License

&copy; 2022 clitic

This repository is licensed under the MIT license. See LICENSE for details.
