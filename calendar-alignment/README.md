# Notice
**This will misalign other locales.** This is an editied version of the clock module included in waybar by default, specifically to fix alignment issues with the **'ja_JP.UTF-8'** locale.
The kanji seem to cause problems with the spaces added by default. To fix the issue this replacement module changes the number of spaces in 3 locations to improve the alignment.

I recommend saving a copy of your original clock.cpp file, although you can perform a 'git reset' on your waybar directory.

# Changes
getCalendarLine: chaged the number of spaces to align the days of the week to the days in the month.

get_calendar: changed the number of spaces to align month/year header and the line outputs of days of the week.
