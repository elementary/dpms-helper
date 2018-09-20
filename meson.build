project(
    'io.elementary.dpms-helper',
    version: '1.0'
)

meson.add_install_script('meson/post_install.py', join_paths(get_option('prefix'), get_option('datadir')))

subdir('bin')
subdir('data')
