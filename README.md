# Display the forecast.weather.gov weather graph in your terminal

# Installation

You need `wget`, `lynx` and `imgcat` in order for the `weather` script to work.

You also need to be [using the GNU version of the `date` command][howto] (probably only an issue for Mac users).

`wget` and `lynx` can be installed with Homebrew, Yum or whatever you use to install packages.

`imgcat` is installed via `npm` like so:

    sudo npm -g install imgcat-cli

# Screenshots

When you run `weather` it looks like this!

<img src="http://i.imgur.com/tXRSZSE.png" alt="weather graph screenshot">

[howto]: http://apple.stackexchange.com/questions/69223/how-to-replace-mac-os-x-utilities-with-gnu-core-utilities "how to install the GNU date command on Mac"
