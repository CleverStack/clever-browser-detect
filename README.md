# Cleverstack Browser Detect Module

This module provides an AngularJS Service which you can use to detect browsers and OS.


## Setup - Using CLI.

You can use [CleverStack CLI](https://github.com/CleverStack/cleverstack-cli) for easy install.

Run the following command:

`clever install clever-browserdetect`


## Setup - Manual.
1. Add 'cs_browserdetect' to your app/modules/main.js file.
It belongs in the `package` array at the top.

2. Add `cs_browserdetect` to your app/modules/application/main.js file.
It belongs in the array of required modules.

3. Add `cs_browserdetect` to your app/modules/application/module.js file.
`cs_browserdetect` belongs in your `app` module's array of required modules.


## Usage
Include the service `$CSBrowserDetectService` into a controller and you can reference the following properties.

`browserdetect.browser` // Chrome Safari, Firefox, MSIE, Opera...

`browserdetect.version` // ie - 24, 28, 4.2...

`browserdetect.OS` // Windows, Mac, Linux, iPhone...


## Testing
It sets up a view with a route you can test if you go to `http://localhost/browserdetect`.