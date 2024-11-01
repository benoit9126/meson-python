# SPDX-FileCopyrightText: 2024 The meson-python developers
#
# SPDX-License-Identifier: MIT

py.extension_module(
    'extension',
    'extension.c',
    install: true,
    subdir: 'namespace' / 'lib1',
)

py.install_sources('__init__.py', subdir: 'namespace' / 'lib1')
