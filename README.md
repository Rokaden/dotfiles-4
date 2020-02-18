UPDATE: Im going to move this setup to another branch, after seeing so many people using and making content for bspwm I decided to give it a try...
Suffice to say, I'm loving it so far. Also switched URxvt for kitty, updated all my scripts/configs/etc to be more readable.
The new setup should be ready soon(ish).

Had to put Windows back on my system (my DJ controller refuses to work on Linux), so a few things have changed with my Arch setup.
I've nuked the old repo to reduce file size, ditch useless stuff.

Check DEPS.md for everything you'll need to use this setup.
A few of the config files are wpg templates that need to be linked before they will work.

	# wpg-install.sh -gi
	# wpg -ta ~/.config/dunst/dunstrc
	# wpg -ta ~/.config/i3/config
	# wpg -ta ~/.config/polybar/config
	# wpg -ta ~/.config/qutebrowser/config.py
	# wpg -ta ~/.config/rofi/config.rasi
	# wpg -ta ~/.local/share/gedit/styles/medium.xml
	# wpg -ta ~/.local/share/localweb/startpage/index.html
	# wpg -ta ~/.local/share/localweb/startpage/script/script.js
	# wpg -ta ~/.local/share/localweb/startpage/style/style.css

also to further reduce the size of this repo all of the wallpapers & colour schemes can be found @ https://drive.google.com/open?id=1JTo31c7Yy2YHZzNzo929TWGevlwOWFCP

I'm running out of things to tweak on this so I'll start working on an install script soon, maybe even an AUR package.

Here's a short demo of some of the features...
<blockquote class="reddit-card" data-card-created="1576563498"><a href="https://www.reddit.com/r/unixporn/comments/ebrjii/i3gaps_please_reddit_no_softwaregore_this_time/">[i3-gaps] Please Reddit, no softwaregore this time...</a> from <a href="http://www.reddit.com/r/unixporn">r/unixporn</a></blockquote>
