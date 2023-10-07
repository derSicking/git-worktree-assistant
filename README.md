# Git Worktree Assistant

This extension aims to make working with worktrees in VS Code easy and accessible, without having to
learn the command line interface for worktrees.

## Features

### Add new worktrees

Use the Command Palette to create a new worktree with the `Add Worktree` command. It guides you through
the process of picking options or branches for your worktree and suggests a location. The default worktree
directory can be adjusted in the extension settings.

## Requirements

Your Workspace needs to be a git repository and the `git` command has to be available on your system.

## Extension Settings

This extension contributes the following setting:

- `gitWorktreeAssistant.addWorktree.defaultWorktreeDirectory`: The path where worktrees are reccomended to be created (relative to repo root).

## Known Issues

If commands do not work for unknown reasons, consider updating your git installation. I used 2.42.0 for development.

## Release Notes

Also see [the change log](CHANGELOG.md).

No releases yet...