# defaults
Default system-wide configs, skeleton /etc/skel files, shell setups, and window manager configs.

## Hostname

`etc/hostname` sets the distro default to `emperor`. Installers should copy it
to `/etc/hostname`; the kernel `CONFIG_DEFAULT_HOSTNAME` value only covers the
period before userspace sets the hostname.
