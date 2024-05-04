# Install tarball version of Thunderbird with just a basic script!

A script to easily install Thunderbird the tarball way on your Linux machine!

Note: This installation script is by no means affiliated with Thunderbird project, or its maintainers.

## Usage

Clone the repo and run the script
```bash

git clone https://github.com/spookyorange/thunderbird-linux-install.git
cd thunderbird-linux-install
sh ./install.sh

```

To remove the application(if it has been installed with this method)
```bash

sh ./uninstall.sh

```

Updates are handled by changing the version number and running install.sh again, please change the version from inside the install.sh and run it again. If you wish to contribute to the project, whenever a new version comes out, you may open an issue or create a pull request!

```bash

sh ./install.sh

```

## Details

The script will install the application in the following destinations if you have installed locally:

- ~/.tarball-installations/thunderbird
- ~/.local/bin/thunderbird
- ~/.local/share/applications/thunderbird.desktop

## Tested Distros

- Fedora by Spookyorange
- SteamOS(Steam Deck) by Spookyorange

## Contributing

If you have a distro that you would like to add to the list of tested distros, please submit a pull request with the changes you made to the script and the distro you tested it on.
