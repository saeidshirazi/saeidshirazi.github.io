---
layout: post
title: Building Your Own Downloader in Rust!
date: 2024-06-15 00:01:00
description: this is what included pseudo code could look like
tags: coding, reverse
categories: sample-posts
pseudocode: true
---

We will build a downloader in Rust, which will download and run a shell script (maybe like a real malware!).

## First Step: Setting Up Our First Rust Program

```sh
cargo new simple-downloader
cd simple-downloader

$ cargo new simple-downloader
Created binary (application) `simple-downloader` package
$ cd simple-downloader/
$ tree
.
├── Cargo.toml
└── src
    └── main.rs
    ```

The Default main.rs
$ cargo new simple-downloader
Created binary (application) `simple-downloader` package
$ cd simple-downloader/
$ tree
.
├── Cargo.toml
└── src
    └── main.rs
