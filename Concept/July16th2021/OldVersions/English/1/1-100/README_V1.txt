SafeT concept

A set of safety tools for Linux terminals, so that you don't have to block their access entirely on public computers, and can be a lot safer

Unlock settings (requires entering both the sudo password and SafeT password, for extra security)

Supported terminals so far:

GNOME Terminal
Konsole
Vim

Block level A

Maintenance level

Block the usage of:

snap
install
sudo
update
pulseaudio
etc.

checkboxes for each individual option, and all of them together

Block level B

File level

Block the usage of

rm
rf
cat
etc.

Block level C

Block the usage of these dangerous Linux commands

Danger level

chmod 777
chown 777
sudo rm -rf
sudo rm -rf -no-preserve-root-

Allowed commands by default

cal
dir
ls
cd
etc.
