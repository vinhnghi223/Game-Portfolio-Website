Game Portfolio Wordpress Theme
==============

For testing and educational purpose uses.

![ScreenShot](https://raw.github.com/vinhnghi223/virgo.fi-theme/master/screenshot.jpg)

The theme was built on virgo-blank which is just a blank wordpress theme created by famed web designer and developer Chris Coyier. I only did some minor changes for the background as well as some CSS preprocessors. 

The full-fledged theme system is located in virgo.fi-theme which can be found at:
https://github.com/vinhnghi223/virgo.fi-theme/tree/master/virgo

Here you can have a better view of how I implemented the theme. Basically I override the following php files:

+ 404.php
+ header.php
+ Style.css
+ single.php
+ screenshot.png

I then also added some new php files:

+ attachment.php
+ loading.gif
+ page-about.php (designed for the about page)
+ page-game.php (designed for the game page)
+ page-games.php (designed for the games page; games page is the page containing list of games, each game is a link to a game page that mentioned just above)
+ page-home.php (designed for the home page)
+ page-person.php (designed for the person page)

The rest are left untouched.

Some plugins that are critical and required to run the theme: contact-form-7, custom-post-background (with a little modification, included in the repository), qtranslate and slimbox. These are plugins that were installed after installing the virgo.fi-theme not the blank one.

