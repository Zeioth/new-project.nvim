# create-project.nvim
A plugin that provide the command `:NewProject` to create a new project.

## Hello!
This plugin is in conceptual phase. Check it out in a few months.

## What's the idea behind it
Using telescope as user interface to let users create a new project, in an IDE like fashion. Initial planned support for express, angular, react, vue, C# and a few others.


## Could be useful for
- C#                   → Create program / create dll
- Visual basic dotnet  → Create program / create dll
- Dart
- Flutter
- zig
- go
- rust
- java maven/otros
- kotlin                → kotlin -create-project
- kotlin android studio → android create project --name <project-name> --path <project-path> --package <package-name> --activity <activity-name>

## Not very useful for

- C
- C++
- lua
- perl
- general usage languages that use no frameworks

## ZIG
for zip we would wanna have

* create exe project →  this has to run `zig init-exe`.
* create lib project → this has to run `zig init-lib`.

These are meant to run with compiler.nvim, which does `zig build` or `zig build run`.

## Provided options
WIP

## Planned for 2027
In the meantime you can use the command `:TermExec cmd="my command to create project"` or wathever you may need.
