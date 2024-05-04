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

Updates are handled by running the install script again, you can just run the install script and all good!

```bash

sh ./install.sh

```

## Details

The script will install the application in the following destinations if you have installed locally:

- ~/.tarball-installations/firefox
- ~/.local/bin/firefox
- ~/.local/share/applications/firefox.desktop

## Tested Distros

- Fedora by Spookyorange
- SteamOS(Steam Deck) by Spookyorange

## Contributing

If you have a distro that you would like to add to the list of tested distros, please submit a pull request with the changes you made to the script and the distro you tested it on.
