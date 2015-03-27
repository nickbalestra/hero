# Hero Theme

 Hero is a very simple flat style theme for Sublime Text 3.

Based on Piatto Theme by Samuel Rafo [https://github.com/samuelrafo/piatto](https://github.com/samuelrafo/piatto) and on the Heroku Color Scheme by Rubens Stulzer [https://github.com/stulzer/heroku-colorscheme](https://github.com/stulzer/heroku-colorscheme).

Also included is a "Hero Dark Eighties" theme based off [Base16's Ocean scheme](http://chriskempson.github.io/base16/#ocean).

## Design

### Hero Dark
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark1.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark2.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark3.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark4.png)

### Hero Dark Eighties
![Hero Dark Theme](https://raw.github.com/aaronbushnell/Hero/master/images/hero_dark_eighties1.jpg)
![Hero Dark Theme](https://raw.github.com/aaronbushnell/Hero/master/images/hero_dark_eighties2.jpg)
![Hero Dark Theme](https://raw.github.com/aaronbushnell/Hero/master/images/hero_dark_eighties3.jpg)
![Hero Dark Theme](https://raw.github.com/aaronbushnell/Hero/master/images/hero_dark_eighties4.jpg)

## Installation

Hero theme is designed to work with the latest development builds of Sublime Text: [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Hero Theme via the `Package Control: Install Package` menu item. The Hero Theme package is listed as `Theme - Hero` in the packages list.

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Hero`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.


### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Hero Dark.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Hero Dark.sublime-theme"
    }


### Color Scheme

```javascript
{
    "color_scheme": "Packages/Theme - Hero/Hero Dark.tmTheme"
}
```

```javascript
{
    "color_scheme": "Packages/Theme - Hero/Hero Dark Eighties.tmTheme"
}
```
