# OS X Auto VPN

## Configure

Edit `auto-vpn` with a text editor and replace `MyVPN` with your vpn connections name. Then replace the value of `TESTIP` with a static IP on your vpn network.

Install `Packages`

```shell
brew cask install packages
```

Open `osx-auto-vpn.pkgproj` with packages.app and build the installer.

## Installation

After you've built the package run the package installer located in the `build` folder.
