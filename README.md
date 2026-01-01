How to install:
- Clone this repo or download zip
- Copy ULTRAKILL folder to `/usr/share/plymouth/themes`
- `sudo plymouth-set-default-theme ULTRAKILL` for most distros. With Linux Mint and other distros that don't work 
`sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/ULTRAKILL/ULTRAKILL.plymouth 200
sudo update-alternatives --config default.plymouth` 
Select ULTRAKILL
`sudo update-initramfs -u`
[Demo](https://file.khoinet.dpdns.org/ULTRAKILL%20Plymouth%20Theme%20Demo.mp4)
