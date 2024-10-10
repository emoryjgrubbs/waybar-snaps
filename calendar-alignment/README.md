This will misalign other locales.

This is an editied version of the clock module included by waybar by default, specifically to fix alignment issues with the 'ja_JP.UTF-8' locale.

I recommend saving a copy of your original clock.cpp file, although you can perform a 'git reset' on your waybar directory.

The kanji seem to cause problems with the spaces added by default. To fix this, this replacement module changes the number of spaces in a 3 location to improve the alignment.

