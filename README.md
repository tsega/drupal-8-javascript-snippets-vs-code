# Drupal 8 JavaScript snippets for Visual Studio Code

This extension adds 2 useful JavaScript snippets that can be used with Drupal 8. These snippets were extracted from the [JavaScript API overview](https://www.drupal.org/docs/8/api/javascript-api/javascript-api-overview) documentation.

## Installation

To install this extension use the following steps:

1. In VS Code, open the **Command Palette** using the shortcut key combination `ctrl-shift-p` (Windows, Linux) or `cmd-shift-p` (OSX)
1. Then in the Command Palette box, type in `Install Extensions` and select that form the list.
1. This will open up the **Extension Manager**. In the search box type in `Drupal 8 JavaScript Snippets`.
1. Click the **Install** button, after that finishes make sure to reload VS Code as well.

## Usage

Once installed, to use these snippets you can use the following two methods, the first Method is geared towards people who are new to the snippets available while the second method is suitable for people who know the available snippets and are looking to increase their speed.

### Method 1
1. Open the **Command Palette**, `ctrl-shift-p` (Windows, Linux) or `cmd-shift-p` (OSX)
1. In the command box type in `Insert Snippet`; this will list all the available snippets.
1. Select the snippet you want to use from the provided list.

### Method 2
1. In the code editor window, type in the **Prefix** of the snippet you want to insert. This will show an intellisense window as you type.
1. Insert the snippet you want by simply pressing the `tab` key.

## Features

Here you will find all the code snippets that are available in this extension. Please note that each title starts with the **Prefix** of the code snippet to insert; useful to memorize them if you plan to use [Method 2](#Method-2) above.

### jqw - jQuery Wrapper

This wrapper makes the $ jQuery short code avialable for code inside it.

Example:
```js
(function ($, Drupal) {
    $(".invisible").hide();
}(jQuery, Drupal));
```

![jQuery Wrapper](images/jqw.gif "jQuery Wrapper Drupal 8 JavaScript Snippet")

### bhv - Drupal 8 Behavior

This inserts a Drupal 8 JS behavior.

Example:
```js
Drupal.behaviors.myBehavior = {
    attach: function (context, settings) {
        console.log('My Behavior');
    }
};
```

![Drupal 8 Behavior](images/bhv.gif "Behavior Drupal 8 JavaScript Snippet")

### Requirements

These snippets are only made available in files with a `.js` extension.

## Release Notes

### 0.0.1

Initial release