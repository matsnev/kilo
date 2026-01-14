# Kilo

A version of [antirez kilo editor](https://github.com/antirez/kilo), with some improvements:

*   Buffered memory handling (not one byte at a time)
*   PageUp/PageDown keeps the cursor position on the screen, just scrolls the text in the background
*   When scrolling up/down, tries to keep a few rows above/below the cursor row visible
*   Line numbers (can toggle on/off)
*   Fast jump to the first/last row/character
