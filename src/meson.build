plinex_deps = [
]

executable('plinex', plinex_sources,
  dependencies: plinex_deps,
  install: true,
)

=======
  'main.c',
  'plinex-application.c',
  'plinex-window.c',
]

plinex_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1', version: '>= 1.4'),
]

plinex_sources += gnome.compile_resources('plinex-resources',
  'plinex.gresource.xml',
  c_name: 'plinex'
)

executable('plinex', plinex_sources,
  dependencies: plinex_deps,
       install: true,
)
>>>>>>> a893429 (switched to C and GNOME application preset)
