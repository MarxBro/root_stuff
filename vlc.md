# Make vlc run as root. 

Search for _geteuid_ and replace by _getppid_ on the binary itself.

You may need to use __$(which vlc)__ to check where it is.

__It all comes down to change geteuid by getppid.__
