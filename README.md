## IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.
---

### Resources

[HTML Content from Style Stage by Stephanie Eckles](https://stylestage.dev)

[Build Excellent Websites by Andy Bell](https://buildexcellentwebsit.es/)

[Code for Bell's Build Excellent Websites (the source for the Fluid CSS code linked above) ](https://glitch.com/edit/#!/build-excellent-websites)


### Features included:
- Included Andy Bell's Reset Library
- Used Mobile-First assignment as a starting point
- Used Custom Properties
- Used fluid sizing to make sure that the font does not jump between screen sizes
- Included typography effects such as letter spacing and line height
- Styled the background by having a gradient color change from pink, to white, to light green
- Added CSS to make the skip link only visible when it has the focus
- Styling the links
- Styling the lists
- Used lighthouse to check accessibility

Resources:
- Color Palette Link: https://www.color-hex.com/color-palette/1020588
- I used two google fonts:
    - Unbounded font: https://fonts.google.com/specimen/Unbounded?category=Display
    - Roboto font: https://fonts.google.com/specimen/Roboto?category=Sans+Serif
    