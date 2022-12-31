# Vimty: A vim typewriter

[Here's a video of it in action](https://old.dixonary.co.uk/s/typewriter-vim.mp4)

## Dependencies

* i3wm (to move the window from shell)
* xrandr (to get screen info)
* xwininfo, xdotool (to get window info)
* vim >7.4 (for some of the buffer stuff)
* normal shell stuff like awk, head, cut

## How to use
1. In vim: `:source vimty.vim`
2. If you didn't get a ton of errors, it's probably working

Side note: It might be difficult to use this if your vim window is > half of your screen width or height, depending on how i3 is feeling. It might not want to position off the top or left of the screen!
