# TextMate bundle for Eric Meyers's CSS Reset

To install, you'll need both TextMate and Git installed on your machine. Then do the following, from Terminal:

    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/charliepark/css_reset_tmbundle.git "CSS Reset.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


The bundle includes four reset snippets.


## CSS Reset - Eric Meyer

This is the raw Reset CSS file, version 1.0, from http://meyerweb.com/eric/tools/css/reset/.

To add it to your CSS or HTML file, just type "resetem" and hit the "tab" key.


## CSS Reset

This is the same as the above file, but with slight minification, and with some selector cleanup. Personally, I prefer my CSS selectors to be alphabetized. This snippet does that.

To add it to your CSS or HTML file, just type "reset" and hit the "tab" key.


## CSS Reset - Charlie Park

This is the same as the above (slightly minified) file, with an extra line of code that I use to get my own apps started.

To add it to your CSS or HTML file, just type "resetcp" and hit the "tab" key.


## CSS Reset - Minified

This is the raw CSS Reset, run through an extreme minifier. Use this one if you just need the code included, but don't need to actually read it.

To add it to your CSS or HTML file, just type "resetmin" and hit the "tab" key.