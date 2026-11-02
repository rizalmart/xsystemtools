# xsystemtools-GTK

A simple collection of GTK+3 essential system administration utilities
written in Python.

Forked from Salix Linux. Now made for all distros especially DE's that has lack of some system tools.

It works on sysvinit, systemd, and runit init system

## Maintained Utilities

- gtkclocksetup - Configure system date and time.
- gtkhostsetup - Configure system hostname.
- gtkusersetup - Manage system users and groups.

## Requirements

- Python 3
- GTK+3
- PyGObject
- Required command-line utilities for each application.

## Building

    make

## Installing

    make install

To install into a staging directory:

    make install DESTDIR=/tmp/package

## Cleaning

    make clean

## License

See COPYING for licensing information.
