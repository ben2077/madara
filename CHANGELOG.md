# Madara Changelog

## Next release

- ci: downgraded windows runner to windows-latest
- ci: added windows binaries build and upload the binaries to the release page
- ci: add `CHANGELOG.md` and enforce it is edited for each PR on `main`
- fix: removed `madara_runtime` as a dependency in the client crates and make
  errors more expressive
- fix: state root bug fix where the tree was stored in runtime _before_ being
  committed
- feat: add a `genesis_loader` for the node and mocking
- feat: add `madara_tsukuyomi` as a submodule
- branding: use new logo in the README
- test: add `starknet-rpc-test` crate to the workspace
- test(rpc): add `get_block_number.rs` tests
- test(rpc): add `get_block_hash_and_number.rs` tests
- test(rpc): add `get_block_transaction_count.rs` tests
- test(rpc): add `chain_id.rs` tests
