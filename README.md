# I2G
[![Build Status](https://travis-ci.org/jletizia/I2G.svg?branch=master)](https://travis-ci.org/jletizia/I2G)
[![Maintainability](https://api.codeclimate.com/v1/badges/4f97375f416c9430b317/maintainability)](https://codeclimate.com/github/jletizia/I2G/maintainability)

* Issues: [here](https://github.com/jletizia/I2G/issues)
* Code: [here](https://github.com/jletizia/I2G)

# Description:
**I2G** is a theme conversion framework written in ruby.

It contains 4 main pieces:
* `I2G::Parser` - read in the source theme file, and provide an interface to get values converted into destination format
* `I2G::Converter` - provide the actual conversion logic
* `I2G::Generator` - implement the parser to generate a destination theme file
* `I2G::Installer` - install a generated theme file

I2G comes with Iterm2 (.itermcolors) to gnome-terminal (.dconf) conversion support by default.

Expanding support for different source and destination themes is as easy as adding a new class in the proper namespace to perform the appropriate function.

