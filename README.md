# gnome-wallpaper-changer
GNOME extension to change wallpaper from providers

## Install instructions
```
git clone https://github.com/Jomik/gnome-wallpaper-changer.git ~/.local/share/gnome-shell/extensions/wallpaper-changer@jomik.org
cd ~/.local/share/gnome-shell-extensions/wallpaper-changer@jomik.org
glib-compile-schemas ./schemas/
```

Relog and you're good to go!

## Folder provider
Looks, by default, for wallpapers in `~/wallpapers` and applies them at random.

## Wallhaven provider
Currently no preferences.
Takes SFW General pictures with the ratio 16x9 from wallhaven.cc and applies them to your pictures.
It downloads a page of pictures at once and deletes them as they're used.
