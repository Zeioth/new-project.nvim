# create-project.nvim
A plugin that provide the command `:NewProject` to create a new project.

## Hello!
This plugin is in conceptual phase. Check it out in a few months.

## What's the idea behind it
Using telescope as user interface to let users create a new project, in an IDE like fashion. Initial planned support for express, angular, react, vue, C# and a few others.

## ZIG
for zip we would wanna have

* create exe project →  this has to run `zig init-exe`.
* create lib project → this has to run `zig init-lib`.

These are meant to run with compiler.nvim, which does `zig build` or `zig build run`.

## Provided options
WIP

## Planned for 2027
In the meantime you can use the command :TermExec cmd="my command to create project" or wathever you may need.
