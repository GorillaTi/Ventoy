# Kameleon (GRUB)

This theme is part of the Kameleon project

## Project

Kameleon is a project to create a full desktop theming to (I know, I know) looking like Windows 10. Nowadays Windows 10 seems to looking like KDE so ...

## Configuration

Download and extract Kameleon grub theme then copy the whole folder with root privileges to :

* /boot/grub/themes/

Install grub-customizer (in Debian Buster):

```
sudo apt install grub-customizer
```

Or edit the file :

* /etc/default/grub

and add:

```
GRUB_THEME="/boot/grub/themes/kameleon/theme.txt"
```

Update grub :

```
sudo update-grub

```

Or :

```
grub-mkconfig -o /boot/grub/grub.cfg

```

## Tweaks

### Background

Open theme folder then replace the "background.png" file to the one you like (it needs to be .png file)

### Icons

By default, your OS icon is selected, you can change it by renaming the corresponding icon in the folder :

* ./icons/

## Credits

This theme is adapt from original Vimix GRUB2 Theme by vinceliuice & Theme Aurora Penguinis by Georg Eckert. All copyrights, credits and everything goes to their original authors.

## Notes

I'm using this theme daily and so far got no issue, I wanted to share with community since a long time, enjoy if you like.

Feel free to copy the theme and made your own change !




