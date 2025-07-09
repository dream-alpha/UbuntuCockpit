[![Gemfury](https://badge.fury.io/fp/gemfury.svg)](https://gemfury.com/f/partner)

# UbuntuCockpit (UBU)

## Features
UbuntuCockpit is a Ubuntu chroot subsystem for DreamOS that allows to run python3 server apps with python2 plugins.

## Usage
This plugin just installs the Ubuntu subsystem to /data/ubuntu.

To enter the ubuntu subsystem open a telnet session:
- cd /data/ubuntu/root
- ./enter_chroot

Now the Ubuntu subsystem is active. DreamOs continous to run.

To leave the ubuntu subsystem:
- cd /data/ubuntu/root
- ./exit_chroot (this is required for the DreamOs subsystem to shutdown without hang)

## Limitations

- UBU is being tested on DM 920 and DM ONE (OE 2.6) only

## Languages

- english
- german

## Links

- Installation: https://dream-alpha.github.io/UbuntuCockpit
- Support: https://github.com/dream-alpha/UbuntuCockpit/discussions
