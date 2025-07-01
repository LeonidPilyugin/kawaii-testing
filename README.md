# kawaii-testing
Testing repo for [MenheraOS](https://github.com/LeonidPilyugin/menheraOS).
I use this repo to test new features in MenheraOS without changing the [kawaii](https://github.com/LeonidPilyugin/kawaii-repo)
repository, so use `kawaii` repository instead of this.

To use it, add
```
[kawaii-testing]
Server = https://raw.githubusercontent.com/LeonidPilyugin/kawaii-testing/main/x86_64/
```
to /etc/pacman.conf file and install kawaii-keyring package:
```
wget https://github.com/LeonidPilyugin/kawaii-keyring/releases/download/v2.0/kawaii-keyring-2.0-1-x86_64.pkg.tar.zst
sudo pacman -U kawaii-keyring-2.0-1-x86_64.pkg.tar.zst
```
or [sign keys manually](https://wiki.archlinux.org/title/Pacman/Package_signing#Adding_unofficial_keys). My key is A308BDBE10D7C9C168AA2E055F2E4806FFE6B2CD
