# Spicetify_DraculaTheme
A DraculaTheme's inspired Spicetify color scheme.

# Notes:

-  These color scheme can be applied only with the "Sleek" theme, available on the official Spicetify-Theme's Github. h
-  Spotify ad-blocked version is not supported.

# Installation and usage

1. Install spicetify following the guide below and install "Sleek" theme.
2. Clone this repository:
```git clone https://github.com/Piixell/Spicetify_DraculaTheme```
3. Overwrite the old "color.ini" file in the following path:
   ### Linux and MacOS
   ```
   cd Spicetify_DraculaTheme
   cp -r * ~/.config/spicetify/Themes/Sleek
   ```
   ### Windows
   ```
   cd Spicetify_DraculaTheme
   cp * "$(spicetify -c | Split-Path)\Themes\Sleek" -Recurse
   ```
4. Choose the color_scheme:
   ```
   spicetify config current_theme Dracula
   ```
# Preview

![](https://i.ibb.co/XSZY0KK/Schermata-del-2022-09-01-01-27-05.png)

# Useful link

Spicetify-themes's offical Github: https://github.com/spicetify/spicetify-themes

Spicetify installation guide: https://spicetify.app/docs/advanced-usage/installation
