sources = files('a.vala') # Sources which constitute the library
deps = [foo_dep] + [dependency('glib-2.0'), dependency('gobject-2.0')] # Target's immediate dependencies
lib = library('bar', sources, dependencies: deps) # Library to be built
bar_dep = declare_dependency(include_directories: '.', link_with: lib) # Dependency object to be referred to by other components