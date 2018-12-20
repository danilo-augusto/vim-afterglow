# vim-afterglow

Vim adaptation of the [Afterglow](https://github.com/YabataDesign/afterglow-theme) theme from Sublime Text 2/3.

Airline scheme included.

## Setup

- To enable it, simply add `colorscheme afterglow` (not ~~vim-afterglow~~) to your `~/.vimrc` after having installed the plugin (manually or by using a package manager).

- Airline theme should be updated accordingly, but can be explicitly specified by using `let g:airline_theme='afterglow'`.

## Options

To further customize Afterglow, you can currently use the following options **before** setting the color scheme on your
vimrc:

- Black background: `let g:afterglow_blackout=1` (default: 0)

     ☀️ Use this option if you need more contrast, such as working in an office where open windows cause glare on your screen.

- Italicize comments: `let g:afterglow_italic_comments=1` (default: 0)

    📖 Helps visual grepping and quickly differentiating source code and comments when skimming through files.

    ⚠️ Using italics needs a terminal emulator (e.g. iTerm in MacOS) and a font supporting it.

## Screenshots

### Python
<img width="700" alt="python" src="https://cloud.githubusercontent.com/assets/8104631/23351157/c9c22072-fcbf-11e6-8c58-a04e0838ce5c.png">

### LaTeX
<img width="700" alt="latex" src="https://cloud.githubusercontent.com/assets/8104631/23351155/c9b3d7c4-fcbf-11e6-8229-0c50707a98be.png">

### HTML
<img width="700" alt="html" src="https://cloud.githubusercontent.com/assets/8104631/23351156/c9bd9318-fcbf-11e6-9f49-0dc661c5aad5.png">

### Ruby
<img width="700" alt="ruby" src="https://cloud.githubusercontent.com/assets/8104631/23351154/c99cf856-fcbf-11e6-88f6-857568a7ed8d.png">

## Donate

Don't forget to give back to the Open Source community in some way (not necessarily me). 😊

And if you liked this project, feel free to pay me a cup of coffee! ☕️ ❤️ 👇

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick" />
<input type="hidden" name="hosted_button_id" value="MVSBJ7JKSVGZ4" />
<input type="image" src="https://www.paypalobjects.com/en_US/FR/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_FR/i/scr/pixel.gif" width="1" height="1" />
</form>
