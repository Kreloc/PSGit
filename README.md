[![Stories in Ready](https://badge.waffle.io/poshcode/psgit.png?label=ready&title=Ready)](https://waffle.io/poshcode/psgit)
# PSGit

A PowerShell implementation of Git, providing a new command-line interface and object pipeline.

The intent is to take full advantage of the object Pipeline and create task-based commands following the verb-noun syntax of PowerShell.  The [Command Proposals](https://github.com/PoshCode/PSGit/wiki/Command-Proposals) are a list of the commands we probably need to implement, and how they map to `git` commands.

## Secondary Goals

We're also using this project as a way to test out a process of co-working and doing TDD in PowerShell projects -- we'll have one or two people writing specs and tests and we'll be asking other people to implement the commands to pass the tests.

Therefore, we want you to [get involved](CONTRIBUTING.md)!

## Current project build status

| **master** | [![master status](https://ci.appveyor.com/api/projects/status/42a7ng63t0q7ba7e/branch/master?svg=true)](https://ci.appveyor.com/project/Jaykul/psgit/branch/master) |
| **dev** | [![dev status](https://ci.appveyor.com/api/projects/status/42a7ng63t0q7ba7e/branch/dev?svg=true)](https://ci.appveyor.com/project/Jaykul/psgit/branch/dev) |