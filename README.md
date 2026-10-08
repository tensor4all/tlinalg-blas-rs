# tlinalg-blas-rs — retired

This repository is **retired**. The `tlinalg-blas` crate was merged into
[tensor4all/tlinalg-rs](https://github.com/tensor4all/tlinalg-rs) as a sibling crate
(`crates/tlinalg-blas`) together with this repository's history on 2026-10-05, and all further
development happens there. Do not open issues or pull requests here.

| | |
|---|---|
| Crate | [`tlinalg-rs/crates/tlinalg-blas`](https://github.com/tensor4all/tlinalg-rs/tree/main/crates/tlinalg-blas) |
| Issues | [tensor4all/tlinalg-rs/issues](https://github.com/tensor4all/tlinalg-rs/issues) |
| Merge | `tlinalg-rs` commit `543261a`; this repository's final commit `e678bfd` is an ancestor of `tlinalg-rs` `main` |
| Superseded README | [at the final commit](https://github.com/tensor4all/tlinalg-blas-rs/blob/e678bfd/README.md) |

The crate's role is unchanged: the LAPACK/BLAS provider of the tensor-free numerical interface,
with vendor-owned threading and a serial batch loop. Its scope has since grown from the packed-LU
family to every remaining LAPACK family, in `tlinalg-rs`.

## License

MIT OR Apache-2.0.
