# wp-manager

#installation
 install the script
1. wget "ncode.codes/wp-manager"
 move to /usr/local/bin/
2. sudo mv wp-manager /usr/local/bin/
 make wp-manager executable
3. sudo chmod +x /usr/local/bin/wp-manager
 add alias to bashrc
4. sudo echo 'alias wp-manager="/usr/local/bin/./wp-manager"' >> ~/.bashrc

Usage: wp-manager [OPTION]
WordPress installations manager.

options:
    -a                  Add a new WordPress website.
    -r                  Remove a WordPress installation.
    -l                  List all available WordPress installation.
    --help              Display this help and exit.

Report bugs to: https://github.com/Noam-Alum/wp-manager/issues
