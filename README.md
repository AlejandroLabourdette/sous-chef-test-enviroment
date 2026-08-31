# sous-chef-test-enviroment

A scratch repository used to exercise the [sous-chef](https://github.com/alab/sous-chef) Claude Code
plugin end to end.

## Purpose

This project holds no real product code. It exists so the sous-chef brigade workflow can be driven
against a live repository:

- `/fire` opens a station (git worktree + herdr workspace + chef-de-partie session)
- `/brigade` reports the live status of every station
- `/pass` runs a background review of a station's branch
- `/plate` pushes the branch and opens a pull request
- `/86` tears a station down

Branches created by the plugin follow the `sous-chef/<slug>` convention. Anything committed here is
disposable test material.
