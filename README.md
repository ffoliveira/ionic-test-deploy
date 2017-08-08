This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

## How to use this template

*This template does not work on its own*. The shared files for each starter are found in the [ionic2-app-base repo](https://github.com/ionic-team/ionic2-app-base).

To use this template, either create a new ionic project using the ionic node.js utility, or copy the files from this repository into the [Starter App Base](https://github.com/ionic-team/ionic2-app-base).

### With the Ionic CLI:

Take the name after `ionic2-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myBlank blank
```

Then, to run it, cd into `myBlank` and run:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.


cli packages: (.\blank\node_modules)

    @ionic/cli-plugin-cordova       : 1.6.2
    @ionic/cli-plugin-ionic-angular : 1.4.1
    @ionic/cli-utils                : 1.7.0
    ionic (Ionic CLI)               : 3.7.0

global packages:

    Cordova CLI : 7.0.1

local packages:

    @ionic/app-scripts : 2.1.3
    Cordova Platforms  : browser 4.1.0
    Ionic Framework    : ionic-angular 3.6.0

System:

    Android SDK Tools : 25.2.5
    Node              : v6.10.3
    OS                : Windows 10
    npm               : 3.10.10
