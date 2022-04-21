sources = files('a.vala', 'b.vala') # Sources which constitute the library
deps = [] + [dependency('glib-2.0'), dependency('gobject-2.0')] # Target's immediate dependencies
lib = library('foo', sources, dependencies: deps) # Library to be built
foo_dep = declare_dependency(include_directories: '.', link_with: lib) # Dependency object to be referred to by other components