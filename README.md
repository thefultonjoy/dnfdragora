# dnfdragora

dnfdragora is a [DNF](http://dnf.readthedocs.io/en/latest/) frontend, based on rpmdragora from Mageia (originally rpmdrake) Perl code.

dnfdragora is written in Python 3 and uses libYui, the widget abstraction library written by SUSE, so that it can be run using Qt 5, GTK+ 3, or ncurses interfaces.

Example with Qt:
![dnfdragora with Qt UI](http://anaselli.belinux.it/test/dnfdragora.png "dnfdragora with Qt UI")

Example with ncurses:
![dnfdragora with ncurses UI](http://anaselli.belinux.it/test/dnfdragora-ncurses.png "dnfdragora with ncurses UI")

## REQUIREMENTS

### DNF
* https://github.com/rpm-software-management/dnf
* Version higher than 1.1.9 required.

### DNF Daemon
* https://github.com/timlau/dnf-daemon/

### SUSE libyui
* https://github.com/libyui/libyui
* Consider to check some not yet approved changes here https://github.com/anaselli/libyui

### libyui-mga - our widget extension
* https://github.com/xquiet/libyui-mga

### SUSE libyui-bindings - anaselli fork
* https://github.com/anaselli/libyui-bindings/tree/mageia
  This fork is necessary to include also libyui-mga extension.
* For references, master is https://github.com/libyui/libyui-bindings

### at least one of the SUSE libyui plugins
* libyui-gtk     - https://github.com/libyui/libyui-gtk
* libyui-ncurses - https://github.com/libyui/libyui-ncurses
* libyui-qt      - https://github.com/libyui/libyui-qt
* Consider here also to check some not yet approved changes at
  https://github.com/anaselli/libyui-XXX forks (where XXX is
  gtk, qt or ncurses)

### at least one of the MGA libyui widget extension plugins (according to the one above)
* libyui-mga-gtk     - https://github.com/xquiet/libyui-mga-gtk
* libyui-mga-ncurses - https://github.com/xquiet/libyui-mga-ncurses
* libyui-mga-qt      - https://github.com/xquiet/libyui-mga-qt

## INSTALLATION 

TODO

## LICENSE AND COPYRIGHT

See [license](LICENSE) file.

