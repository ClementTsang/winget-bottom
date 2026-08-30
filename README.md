# winget-bottom

A repo to trigger [winget-pkgs](https://github.com/microsoft/winget-pkgs) PRs for bottom. Uses [a fork](https://github.com/ClementTsang/winget-releaser) of
[winget-releaser](https://github.com/vedantmgoyal9/winget-releaser). The generated packages can be found [here](https://github.com/microsoft/winget-pkgs/tree/master/manifests/c/Clement/bottom).

To use this:

1. Generate a classic PAT with public repo access.
2. Update the secret token.
3. Run the release job.
4. Check if a PR is created in [winget-pkgs](https://github.com/microsoft/winget-pkgs).
5. When done, delete the PAT.

Note that you may need to also manually sync up the forked `winget-pkgs` repo, as it is sometimes a bit wonky.
