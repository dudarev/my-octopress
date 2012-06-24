---
layout: page
title: "Ubuntu and Russian Phonetic Keyboard Layout"
date: 2008-11-04 13:04
categories:
comments: true
sharing: true
footer: true
meta: false
---

On Ubuntu the standard Russian phonetic keyboard had three keys
different from what I got used to. It was annoying. Naturally,
there is no a "standard" Russian phonetic keyboard.  American
Association of Teachers of Slavic and East European Languages
([AATSEEL](http://www.aatseel.org/)) recommends
[a dozen](http://www.aatseel.org/windows_cyrillic#keyboard) of
different drivers for different systems. For the last decade, on
all Windows machines I worked mostly by myself, I set up
[the layout](http://winrus.com/kbd_e.htm#phon)
by Paul Gorodyansky, recommended as the first on AATSEEL page. On
Linux machines, I either tolerated what came pre-installed, did not
really need Russian keyboard, or vim keys mapping was sufficient
for all tasks. Today I decided to tweak the keyboard layout a bit.
[As described](http://people.uleth.ca/~daniel.odonnell/Blog/custom-keyboard-in-linuxx11) by
Daniel Paul O'Donnell, to change layout in Linux is very simple. On
Ubuntu file `/etc/X11/xkb/symbols/ru` has to be modified and it is rather straightforward.

## Update (October 2011)

Now I am keeping my vim keymap file for Russian phonetic layout at <https://github.com/dudarev/keymap>. 
In README there I also mention which lines I change in `/etc/X11/xkb/symbols/ru` to update standard Russian phonetic layout in Ubuntu to fit my taste.
