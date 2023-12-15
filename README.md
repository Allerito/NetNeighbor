# NetNeighbor ![Project version](https://img.shields.io/badge/Version-0.0.0a-%23002aff)

A lan application that allows all devices connected in a lan to communicate and share files and messages without limitation

---

# [Rust](https://www.rust-lang.org/learn/get-started) ![Rust version](https://img.shields.io/badge/Version-1.74.0-orange)

Rust is the main language of the project.

This project is in fact based on [Cargo](https://crates.io/) the Rust package manager; thanks to Cargo, it is also possible to manage the various libraries used in the project.

These libraries are written within the [Cargo.toml](https://github.com/Allerito/NetNeighbor/blob/main/Cargo.toml) file under the *dependencies* section.

Below you will find the main ones with the commands you need to execute to download them, however you may encounter errors:
- The libraries might depend on other libraries or this file might be outdated compared to the libraries used in the project
  - To solve the first problem, I recommend downloading the dependencies using the appropriate commands or those found on the [crates](https://crates.io/) site
  - Regarding the second problem, please refer to the [Cargo.toml](https://github.com/Allerito/NetNeighbor/blob/main/Cargo.toml) file in the repository

- Another problem could be versions of Rust, Cargo or some libraries that differ from those used in the project
  - For this problem, check the versions marked both here and in the [Cargo.toml](https://github.com/Allerito/NetNeighbor/blob/main/Cargo.toml) file

- A final problem could be that it does not find the libraries you have already installed
  - To solve this problem, try relaunching the library installation command within the project folder

## [Druid](https://docs.rs/druid/latest/druid/) ![Druid version](https://img.shields.io/badge/Version-0.8.3-yellowgreen)

Druid is the library used to manage the GUI.

```
cargo add druid
```

---
# General project info

Developments and their advancements are marked within the [github projects](https://github.com/users/Allerito/projects/6)

## General rules for contributing to the project

- [Issues](https://github.com/Allerito/NetNeighbor/issues) must be created for any problems encountered while using the software or to recommend improvements.
Before creating an issue, check whether another issue describing the same problem already exists.

- If you want to merge the code you have written, you have to open a [pull request](https://github.com/Allerito/NetNeighbor/pulls) from a 'temporary' branch (the one created by default by github when you open it)

<sup>Please contact me if you have any problems</sup>
