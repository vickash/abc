# Arduino Batch Compiler

A simple Ruby script that automates the compilation of one Arduino sketch for all the official Arduino products.

## Requirements

* Ruby 1.9.3 or newer installed
* `bundler` gem installed. `gem install bundler` to get it.
* Arduino IDE 1.6.0 or newer installed

## Installation
```shell
git clone git@github.com:vickash/abc.git
cd abc
bundle install
```
Make `abc` executable.
You can optionally add it to your PATH.

## Usage
```shell
/path/to/abc --output-dir ~/Desktop/firmata firmata.ino
```
This will compile `firmata.ino` in the working directory and output named binaries to the `firmata` folder I have on my desktop.

## Additional Boards
Compile options for additional boards can be specified in `boards.yml`.
