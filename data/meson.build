install_data(
    'io.elementary.dpms.gschema.xml',
    install_dir: join_paths(get_option('datadir'), 'glib-2.0', 'schemas')
)

install_data(
    meson.project_name() + '.desktop',
    install_dir: join_paths(get_option('sysconfdir'), 'xdg', 'autostart')
)

install_data(
    'io.elementary.dpms-greeter-helper.desktop',
    install_dir: join_paths(get_option('sysconfdir'), 'xdg', 'autostart')
)

install_data(
    'power-greeter.conf',
    install_dir: join_paths(get_option('sysconfdir'), 'systemd')
)

test(
    'Validate desktop file',
    find_program('desktop-file-validate'),
    args: join_paths(meson.current_build_dir (), meson.project_name() + '.desktop')
)
