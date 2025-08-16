[![Gemfury](https://badge.fury.io/fp/gemfury.svg)](https://gemfury.com/f/partner)

# UbuntuCockpit (UBU)

## Features
UbuntuCockpit is a Ubuntu chroot subsystem for DreamOS that allows to run python3 server apps with python2 plugins.

## Usage as chroot console
To enter the ubuntu subsystem open a telnet session:
- cd /data/ubuntu/root
- ./enter_chroot
- cd /root (home dir)
- source venv/bin/active (python venv)

Now the Ubuntu subsystem is active. DreamOs continous to run.

To leave the ubuntu subsystem:
- deactivate (python venv)
- exit
- cd /data/ubuntu/root
- ./umount_chroot (this is required for the DreamOs subsystem to shutdown without hang)

## Usage as subsystem for enigma2_plugin_ubuntu_xxxx plugins
For this use case no manual actions are required. The python2 plugin activates chroot and runs the python3 plugin part.

## Limitations

- UBU is being tested on DM 920 and DM ONE (OE 2.6) only

## Links

- Installation: https://dream-alpha.github.io/UbuntuCockpit
- Support: https://github.com/dream-alpha/UbuntuCockpit/discussions
