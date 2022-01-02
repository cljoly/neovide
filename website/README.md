## Build

To build neovide’s website, ensure you have [zola](https://getzola.org/) and `awk` installed.

Then, in this directory, run:
```sh
git submodule update --init
make serve
```

## Edit

Markdown files in [`content`](./content/) may be sourced from other parts of the repository, thanks to [RISS](https://cj.rs/riss). This is to ease maintenance.


