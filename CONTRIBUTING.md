# Contributing to Piconet

The code is in the repositories the [organisation's page](https://github.com/piconet-live) lists. Each has its own
README with its requirements, its build and its checks; where a repository has its own `CONTRIBUTING.md`, that one
applies.

## Making a change

1. Fork the repository and make a branch for your change.
2. Keep a pull request to one change, with a message that says what it changes and why.
3. Open the pull request against `main`. The checks of the repository you change must pass, and so must CI.

A change to a file format or a message the parts share (the relay's packets, the launch, replay and match files, the
status board) goes to [piconet-protocol](https://github.com/piconet-live/piconet-protocol) first; the parts then
take it with a submodule bump.

Please discuss bigger changes on the [Discord](https://discord.gg/DcauFmsGh) before you start on them. Bugs and
small fixes can go straight to an issue or a pull request.

## Licence

The launcher, the runner, the protocol and the tools are licensed under GPL-3.0-or-later. By opening a pull request
you agree that your contribution is licensed under the same terms. The forks keep their upstreams' licences.
