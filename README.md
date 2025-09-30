# @tichopad/dnt - Deno to Node Transform

Deno to npm package build tool.

**Fork of an excellent project [@deno/dnt](https://github.com/denoland/dnt).**

## What does this do?

Takes a Deno module and creates a Node.js compatible npm package.

See
[@deno/dnt README for more details](https://github.com/denoland/dnt/blob/main/README.md).
This README will focus on what's different.

## What's different?

This fork fixes ESM compatibility issues with the output produced by the
original project. See
[the issue for more details](https://github.com/denoland/dnt/issues/476).
