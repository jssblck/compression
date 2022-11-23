<div align="center">

<!-- [![FOSSA Status](https://app.fossa.com/api/projects/custom%2B32924%2Fgithub.com%2Fjssblck%2Fprocession.svg?type=small)](https://app.fossa.com/projects/custom%2B32924%2Fgithub.com%2Fjssblck%2Fprocession?ref=badge_small) -->

</div>

# compression

`compression` is a library implementing compression and decompression algorithms in pure Rust.
Also some containers that aren't themselves compressed, but typically are immediately compressed (e.g. `tar`).

Inspired by [libarchive](http://www.libarchive.org/), intended to remove the need to dynamically link decompression libraries.

## supported algorithms

The algorithms supported and the order in which support is implemented is dictated by need;
I'm implementing these in the order that I need them for projects but if you want to implement or sponsor one to bump it up please do!

Things marked ❌ are not supported and not planned for now. ⏱️ are planned, but not done, and ✅ is supported.

| Algorithm               | Compression | Decompression |
|-------------------------|-------------|---------------|
| `zip`                   | ⏱️          | ⏱️            |
| `tar`                   | ⏱️          | ⏱️            |
| `gz`                    | ⏱️          | ⏱️            |
| `xz`                    | ⏱️          | ⏱️            |
| `bz2`                   | ⏱️          | ⏱️            |
| _Want more? Open a PR!_ | ⏱️          | ⏱️            |

## supported environments

This project is meant to be a library usable by Rust projects directly,
as well as exported in via statically linkable FFI for other languages.

<!-- 

# Licensing

[View third party notices](https://app.fossa.com/reports/9bb31527-cd6e-4186-adbe-f561d236ef2c)

-->
