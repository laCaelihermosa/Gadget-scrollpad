# ::-webkit-scrollbar

Non-standard: This feature is non-standard and is not on a standards track.<bold>Do not use it on production sites facing the Web </bold>: it will not work for every user. There may also be large incompatibilities between implementations and the behavior may change in the future.

https://developer.mozilla.org/en-US/docs/Web/CSS/::-webkit-scrollbar

# CSS Scrollbar Selectors

You can use the following pseudo-elements to customize various parts of the scrollbar for WebKit browsers:

::-webkit-scrollbar — the entire scrollbar.
    width
    height
::-webkit-scrollbar-button — the buttons on the scrollbar (arrows pointing upwards and downwards that scroll one line at a time).
::-webkit-scrollbar:horizontal{} — the horizontal scrollbar.
::-webkit-scrollbar-thumb — the draggable scrolling handle.
    background:
    including image, gradients...
::-webkit-scrollbar-track — the track (progress bar) of the scrollbar, where there is a gray bar on top of a white bar.
::-webkit-scrollbar-track-piece — the part of the track (progress bar) not covered by the handle.
::-webkit-scrollbar:vertical{} — the vertical scrollbar.
::-webkit-scrollbar-corner — the bottom corner of the scrollbar, where both horizontal and vertical scrollbars meet. This is often the bottom-right corner of the browser window.
::-webkit-resizer — the draggable resizing handle that appears at the bottom corner of some elements.

# Specifications
Not part of any standard.

# Browser compatibility

    css.selectors.-webkit-scrollbar,
    css.selectors.-webkit-resizer
        only, FIREFOX, FIREFOX FOR ANDROID not supporting it...
    css.selectors.-webkit-scrollbar-button
    css.selectors.-webkit-scrollbar-thumb,        
    css.selectors.-webkit-scrollbar-track,    
    css.selectors.-webkit-scrollbar-track-piece,
    css.selectors.-webkit-scrollbar-corner
        only, FIREFOX, FIREFOX FOR ANDROID, Safari on iOS not supporting it...