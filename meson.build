project('flatseal',  
          version: '2.3.1',
    meson_version: '>= 0.59.0',
  default_options: [ 'warning_level=2',
                   ],
)

i18n = import('i18n')


subdir('data')
subdir('src')
subdir('po')
subdir('tests')
subdir('help')

gnome.post_install(
  gtk_update_icon_cache: true,
  glib_compile_schemas: true,
  update_desktop_database: true,
)
