This directory contains the results of the [benchmark](../benchmarks/) with 
segment file pre-allocation either enabled or disabled.

Benchmarks have been done on:

1. [Linux Btrfs](./linux_btrfs)
2. [Linux Ext4](./linux_ext4)
3. [macOS APFS](./macos_apfs)

The markdown file under the each directory contains the results data, and there 
are also plotted, see the png files.

# Environments

## Linux env:


```sh
$ uname -a
Linux fedora 6.10.9-100.fc39.x86_64 #1 SMP PREEMPT_DYNAMIC Mon Sep  9 02:28:01 UTC 2024 x86_64 GNU/Linux
```

## macOS env:

```sh
$ sw_vers
ProductName:            macOS
ProductVersion:         26.0
BuildVersion:           25A5295e

$ uname -a
Darwin Steves-MacBook-Air.local 25.0.0 Darwin Kernel Version 25.0.0: Tue Jun 17 00:04:39 PDT 2025; root:xnu-12377.0.122.0.1~120/RELEASE_ARM64_T8103 arm64
```

# Run the benchmarks

* To run it with pre-allocation enabled

  ```sh
  $ cargo bench -p benchmarks --features pre_alloc
  ```

* To run it with pre-allocation enabled

  ```sh
  $ cargo bench -p benchmarks
  ```