# Hero Theme

 Hero is a simple, beautiful flat theme for Sublime Text 3.

## Design

### Hero Dark
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark1.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark2.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark3.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark4.png)
![Hero Dark Theme](https://raw.github.com/nickbalestra/Hero/master/images/hero_dark5.png)


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


### Color Schemes

```javascript
{
    "color_scheme": "Packages/Theme - Hero/Hero Dark.tmTheme"
}
```

### Settings

The theme support active guides, enable them on your preferences file.

```javascript
{
    "indent_guide_options":
        [
            "draw_normal",
            "draw_active"
        ],
}
```

Font used on the screenshot: Inconsolata


### Files icons on sidebar

hero support using file icons on the sidbar. [Info on how to add them](https://github.com/nickbalestra/hero/issues/1)

