# Dragon-GRUB-Theme
Dragon GRUB Theme for the GRUB2 bootloader

Supported Languages: English

Best results on 1920x1080 screens
____________________________________________________________________________
### Install:

Copy the folder 'Dragon-GRUB-Theme' to /boot/grub/themes 
NOTE: use `sudo mkdir /boot/grub/themes` if you dont have the folder

Open /etc/default/grub with your favourite text editor
Add the following line in it
`GRUB_THEME="/boot/grub/themes/Dragon-GRUB-Theme/theme.txt"`

Update your grub.cfg using `sudo update-grub`

If everything goes fine, you should see the following lines:
``` 
Generating grub configuration file ...
Found theme: /boot/grub/themes/Dragon-GRUB-Theme/theme.txt 
```

You're now ready to go!

### Screenshot
<img src="https://github.com/AravindhanV/images1/blob/master/GRUB%20screenshot.png">
