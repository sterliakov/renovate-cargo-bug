# 36056

## Current behavior

Renovate creates a PR mentioning upgrade of `hashbrown` to the same version.

Here's the PR: https://github.com/sterliakov/renovate-cargo-bug/pull/1

Note that `Cargo.toml` has outdated (one patch behind) version, 
but `Cargo.lock` locks to the latest.

## Expected behavior

No unrelated packages are listed in upgrade PR.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/36056
