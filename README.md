# PWA icons and splash screens

This repository contains Adobe Illustrator and IconSlate source files to help generate the images needed for the splash-screens (iOS) and app icons of progressive web apps. It also includes a sample HTML file and webmanifest.

## Usage

### App icons

- Open images-original/icons/icons.ai with Adobe Illustrator
- Add your icon in the artboards for each size
- Click "Export..." in the File menu
- Select the images/icons directory, use the suggested file name.
- Select PNG format
- Check the Artboards checkbox
- Click export and accept the default settings

### Mask icons (for Safari pinned tab)

- Open images-original/icons/mask-icons.ai with Adobe Illustrator
- Add your icon in the artboards for each size
- Click "Export..." in the File menu
- Select the images/icons directory, use the suggested file name.
- Select SVG format
- Check the Artboards checkbox
- Click export and accept the default settings

### Splash screens (currently only for iOS)

- Open images-original/splash-screens/splash.ai with Adobe Illustrator
- Add your splash screens in the artboards for each size
- Click "Export..." in the File menu
- Select the images/splash-screens directory, use the suggested file name.
- Select PNG format
- Check the Artboards checkbox
- Click export and accept the default settings

### Favicons

- Open images-original/icons/favicons.ai with Adobe Illustrator
- Add your favicon in the artboards for each size
- Click "Export..." in the File menu
- Select the images/icons directory, use the suggested file name.
- Select PNG format
- Check the Artboards checkbox
- Click export and accept the default settings
- Open favicon.iconproj with IconSlate
- Drag each icon from images/icons/favicon_*.png to the corresponding size box (16, 32, 48, 256)
- Click "Build" in the menu bar and select images/icons as the output directory
- Cick "options" in the dialog and uncheck "Create a folder for each icon format" and then click "Build"