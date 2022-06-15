
[![hacs][hacs-badge]][hacs-url]
[![release][release-badge]][release-url]
![downloads][downloads-badge]

# Material 3 Theme for Home Asistant: D06, Teal Blue

## What is it
A Material 3 based extended Dark & Light theme for Home Assistant.

This theme not only defines Material 3 dark and light mode colors, but also adapts some of the Home Assistant colors in dark mode as advised by Material 3:
- The error, warning, success and info colors
- The energy dashboard colors
- The label badge (red, blue, green, yellow, grey) colors
- The state climate colors
- The state (on, off, home, not home, unknown, idle) colors

All these colors have been desaturated a bit and given more brightness to have a better match with the dark mode.

The theme also defines some Neumorphic shadow colors for dark and light mode.

For the manual: see https://material3-themes-manual.amoebelabs.com/

For more theme examples, check [the overview of all the 22 examples][ham3-docs-examples-url]
<br>And to implement them in your cards: look at [how to use these Material 3 themes in a Home Assistant card][ham3-docs-howtouse-url]

## Installation via HACS
This Theme is in the default theme repository of HACS

## Manual Installation
Get the yaml file and put int into your `themes` folder.

If you have the following in your `configuration.yaml`:
```yaml
frontend:
  themes: !include_dir_merge_named themes/
```

The theme will be automatically available once you have reloaded the themes using the Home Assistant 'Developer Tools' > 'Services' > 'frontend.reload_themes' service.

## Theme Preview:
Below the definition of the theme, generated and displayed using the [Swiss Army Knife custom card for Home Assistant][sak-docs-url] (NYR).

![m3-06-palettes](https://github.com/AmoebeLabs/ha-theme_m3-06-tealblue/blob/master/preview/m3-theme-06-palettes.png)

![m3-06-surfaces](https://github.com/AmoebeLabs/ha-theme_m3-06-tealblue/blob/master/preview/m3-theme-06-surfaces.png)

![m3-06-light](https://github.com/AmoebeLabs/ha-theme_m3-06-tealblue/blob/master/preview/m3-theme-06-light.png)

![m3-06-dark](https://github.com/AmoebeLabs/ha-theme_m3-06-tealblue/blob/master/preview/m3-theme-06-dark.png)

## Some real-world screenshots:
A Light and Dark example made with the [Swiss Army Knife custom card][sak-docs-url].

Note that the card background in the light theme is white instead of the lightest theme background. Will be corrected...

![m3-06-sake12-light](https://github.com/AmoebeLabs/ha-theme_m3-06-tealblue/blob/master/screenshots/m3-example-06-light.png)

![m3-06-sake12-dark](https://github.com/AmoebeLabs/ha-theme_m3-06-tealblue/blob/master/screenshots/m3-example-06-dark.png)

<!-- Badges -->

[hacs-url]: https://github.com/hacs/integration
[hacs-badge]: https://img.shields.io/badge/HACS-Default-41BDF5.svg?style=for-the-badge
[release-badge]: https://img.shields.io/github/v/release/AmoebeLabs/HA-Theme_M3-D06-TealBlue?style=for-the-badge
[downloads-badge]: https://img.shields.io/github/downloads/AmoebeLabs/HA-Theme_M3-D06-TealBlue/total?style=for-the-badge

<!-- References -->

[home-assistant]: https://www.home-assistant.io/
[home-assitant-theme-docs]: https://www.home-assistant.io/integrations/frontend/#defining-themes
[hacs]: https://hacs.xyz
[release-url]: https://github.com/AmoebeLabs/HA-Theme_M3-D06-TealBlue/releases
[sak-docs-url]: https://swiss-army-knife.docs.amoebelabs.com
[ham3-docs-examples-url]: https://material3-themes-manual.amoebelabs.com/examples/introduction/
[ham3-docs-howtouse-url]: https://material3-themes-manual.amoebelabs.com/using/using-ham3-in-cards/
