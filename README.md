# Spacegray

A set of custom UI themes for Sublime Text 2/3. It's all about hype and minimal. Comes with accompanying [Base16](https://github.com/chriskempson/base16) color schemes.

***

### Themes

#### Spacegray

Default flavor based on Base16 Ocean Dark color scheme.

![image](Screenshots/spacegray.png)

***

### How to Install

#### Manual

You can also install the theme manually:

1. [Download the .zip](https://github.com/markhuot/spacegray/archive/master.zip)
2. Unzip and rename the folder to `Theme - Spacegray`
3. Copy the folder into `Packages` directory, which you can find using the menu item `Sublime Text -> Preferences -> Browse Packages...`

***

### How to Activate

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User` (<kbd>⌘</kbd><kbd>,</kbd> on Mac).

You can choose whichever flavor you like, but don't forget to change *both* color scheme and UI theme so they match.

***Note: Don't forget to restart Sublime Text after activating the theme.***

#### Settings for Spacegray

```json
{
  "theme": "Spacegray.sublime-theme",
  "color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme"
}
```

***

### Settings

#### Tab labels font size

Copy and paste one of four options in your user preferences file:

```json
  "spacegray_tabs_font_small": true
```
```json
  "spacegray_tabs_font_normal": true
```
```json
  "spacegray_tabs_font_large": true
```
```json
  "spacegray_tabs_font_xlarge": true
```

#### Tabs size

Tabs height:

```json
  "spacegray_tabs_small": true
```
```json
  "spacegray_tabs_normal": true
```
```json
  "spacegray_tabs_large": true
```
```json
  "spacegray_tabs_xlarge": true
```

Tabs width: 

```json
  "spacegray_tabs_auto_width": true
```

#### Sidebar labels font size

```json
  "spacegray_sidebar_font_small": true
```
```json
  "spacegray_sidebar_font_normal": true
```
```json
  "spacegray_sidebar_font_large": true
```
```json
  "spacegray_sidebar_font_xlarge": true
```

#### Sidebar tree rows height

```json
  "spacegray_sidebar_tree_xsmall": true
```
```json
  "spacegray_sidebar_tree_small": true
```
```json
  "spacegray_sidebar_tree_normal": true
```
```json
  "spacegray_sidebar_tree_large": true
```
```json
  "spacegray_sidebar_tree_xlarge": true
```

***

### Thanks

Icons from the [Seti UI](https://github.com/jesseweed/seti-ui) theme and [Font Awesome](http://fortawesome.github.io/Font-Awesome/).
