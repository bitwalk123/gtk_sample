project('GTK samples', 'c', version: '0.1')

gtkdep = dependency('gtk4')

src_hello_world = files('gtk4_hello_world.c')
src_packing_button = files('gtk4_packing_button.c')

executable('gtk4_hello_world', src_hello_world, dependencies: gtkdep, install: true)
executable('gtk4_packing_button', src_packing_button, dependencies: gtkdep, install: true)
