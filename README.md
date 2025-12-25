# winget-bottom

Repo to trigger [winget-pkgs](https://github.com/microsoft/winget-pkgs) PRs for bottom. Uses [a fork](https://github.com/ClementTsang/winget-releaser) of [winget-releaser](https://github.com/vedantmgoyal9/winget-releaser).

To use this:

1. Generate a classic PAT with public repo access.
2. Update the secret token.
3. Run the release job.
4. Check if a PR is created in [winget-pkgs](https://github.com/microsoft/winget-pkgs).
5. When done, delete the PAT.
