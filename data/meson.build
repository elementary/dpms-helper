install_data(
    'io.elementary.dpms.gschema.xml',
    install_dir: join_paths(get_option('datadir'), 'glib-2.0', 'schemas')
)

install_data(
    meson.project_name() + '.desktop',
    install_dir: join_paths(get_option('datadir'), 'applications')
)

test(
    'Validate desktop file',
    find_program('desktop-file-validate'),
    args: meson.project_name() + '.desktop'
)
