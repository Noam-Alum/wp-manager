# wp-manager

## Installation

To install the `wp-manager` script, follow these steps:

1. Download the script: ```wget "ncode.codes/wp-manager"```
2. Move the script to the /usr/local/bin/ directory: ```sudo mv wp-manager /usr/local/bin/```
3. Make the wp-manager script executable: ```sudo chmod +x /usr/local/bin/wp-manager```
4. Add an alias to the .bashrc file: ```sudo echo 'alias wp-manager="/usr/local/bin/./wp-manager"' >> ~/.bashrc```

## Usage

The `wp-manager` script provides the following options:

- `-a`: Add a new WordPress website.
- `-r`: Remove a WordPress installation.
- `-l`: List all available WordPress installations.
- `--help`: Display help information.

To report bugs, please visit the [issue tracker](https://github.com/Noam-Alum/wp-manager/issues).

**Note:** Make sure you have the necessary permissions and meet the requirements before running the script.
