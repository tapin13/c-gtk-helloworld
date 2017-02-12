# c-gtk-helloworld
First small prog to test gtk on C

Example from https://developer.gnome.org/gtk3/stable/gtk-getting-started.html

Compiled on LinuxMint 17.3

To compile first install libgtk-3-dev:
sudo apt-get install libgtk-3-dev

Then as in example manual:
gcc `pkg-config --cflags gtk+-3.0` -o firstProg firstProg.c  `pkg-config --libs gtk+-3.0`
