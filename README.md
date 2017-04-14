# Beautify Git in Your MacOS or OSX Terminal

This set of config files can help transform your command line from something ugly and painful to something delightful and easy-to-read.

![](screenshot.png)

## Setup
First things first, you'll want to install a nice color theme for your terminal. The one in the screenshot above is called TupeloHoney, and you'll find it included in this repo. I based it off of the most excellent [Flat terminal theme](https://github.com/ahmetsulek/flat-terminal) from [ahmetsulek](https://github.com/ahmetsulek).

You can load the theme by opening up your mac terminal and navigating to **Preferences > Profiles > Import**.

With that out of the way, we can now log into the bash terminal and set our git configuration to display colors. Here's my setup from the above screenshot.

MacOS & OS X:

```sh
git config --global color.ui true
git config --global color.status.changed "blue normal"
git config --global color.status.untracked "red normal"
git config --global color.status.added "magenta normal"
git config --global color.status.updated "green normal"
git config --global color.status.branch "yellow normal bold"
git config --global color.status.header "white normal bold"
```

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* 0.0.1
    * Work in progress

##

### Contact
- Email: cary.a.miller@gmail.com

### Social Media
- Twitter: [@vintageD18](https://twitter.com/vintageD18)
- GitHub: [https://github.com/cmilr/](https://github.com/cmilr/)

### License
Distributed under the MIT license. See ``LICENSE`` for more information.

# Thanks for stopping by!