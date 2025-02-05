# discussions/33822

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

For my bzlmod updates in `MODULE.bazel`, I get "Failed to look up bazel package rules_coreutils" while all other bazel deps work fine.
This error can be seen in the [renovate dashboard for this repo](https://github.com/luminartech/rules_coreutils_renovate_example/issues/1).

## Expected behavior

`rules_coreutils` updates should work fine.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/33822
