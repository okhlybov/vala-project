# Sample Vala project

This is the sample Vala project which can be used as a project template or a build environment testbed.

It sports a compound project which consists of a Vala module `runme` built as executable which depends on Vala multi-source modules `foo` and `bar`
which are built as independent libraries `libfoo` and `libbar`.

## Prerequisites

- [Vala](https://wiki.gnome.org/Projects/Vala) compiler & dependencies
- [Meson](https://mesonbuild.com) build system & dependencies

## Kick start

```
meson builddir
meson compile -C builddir
```

The above commands perform initial configuration & compilation run for the project.
The resulting executable is placed into `builddir/src/runme`.