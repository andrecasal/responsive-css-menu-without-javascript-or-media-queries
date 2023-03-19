# Responsive CSS Menu without JavaScript or Media Queries

This repository contains a simple HTML and CSS implementation of a responsive navigation menu without using any media queries. The menu is designed to be easy to understand and use in your own projects.

## Why

- Offload breakpoint calculation (at which the hamburger menu has to show up because there's not enough space to display all the menu items) to CSS
- Higher performance
- I haven't found a single responsive CSS Menu without both JavaScript and Media Queries

## Features

- Fully responsive design without using media queries
- Pure HTML and CSS implementation (no JavaScript)
- Easy to customize and style
- Listless Nav

## Drawbacks

- Menu needs a fixed height
- Clicking the logo either doesn't close the menu if it's opened or turning the logo into a label always toggles the menu (opening it if it's closed)

## Usage

This repository is made for you to understand it's underlying concepts and apply them to your own project.

If you have an HTML project:

1. Copy the provided HTML and CSS code into your project.
2. Add your own content and modify the menu structure as needed.
3. Customize the menu appearance and behavior by changing CSS variables and styles.

## Explanation

The code is structured as follows:

- The `:root` element contains CSS variables for the navigation bar height and the gap between navigation items.
- The `input` element is hidden and the `input:checked` selector is used to modify the menu behavior and appearance when the input element is checked.
- The `nav` element contains the main navigation menu.
- The `logo`, `label`, and `div` elements within the `nav` element are styled for different parts of the menu.
- The `a` element is styled for individual menu items.

Feel free to adapt and modify the code to suit your specific needs and preferences.

## Help Wanted

Feel free to contribute any improvements to this implementation.

In particular I'm looking for help with:

- Accessibility
- Transitions
