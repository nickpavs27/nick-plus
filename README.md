# nick-plus
Nick+ personal profile, selected work, and trailer

Published at https://nickpavs27.github.io/nick-plus/ using GitHub Pages from
`main` / root. No build step is needed; keep `.nojekyll`.

`index.html` contains the layout and interactions. `assets/` contains the eight
original WebP photos, extracted without re-encoding. Relative asset paths work
under the `/nick-plus/` project path. The hero photo loads with high priority;
below-the-fold photos load lazily with reserved dimensions. Vimeo loads only
when the trailer is opened, and closing the dialog unloads the player.

The layout reflows for phones, tablets, desktop windows, and browser zoom.
Profile and trailer dialogs use native keyboard/focus handling, keep a visible
close button while scrolling, and restore page position on close. Hover effects
are limited to mouse-like pointers, and reduced-motion preferences are respected.
