wallpaper-changer
=================

Bash daemon for setting random wallpapers from given directory with given rate.

Uses "feh --bg-max" to set a wallpaper.

Options:
-d or --dir or --directory
    Directory with images. Absolute or relative to current working. Search is recursive.

-i or --interval or --delay
    Interval between wallpaper changes.

--no-daemon
    Don't go to background and don't suppress output.

--daemon
    (default) Go to background and suppress output.
