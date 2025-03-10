# Marc Rebillet Tierlist website

The repository contains the code for my [Marc Rebillet Tierlist website](https://0ctgn.cc/en/marc-tierlist). The website consists of simple HTML and CSS files, and uses JavaScript to render the data. The website is available in French and English.

Files details:

- `en/` contains the English version of the website.
- `robe.css` (like the beautiful robes worn each streams) contains the CSS styles.
- `looper.js` (like the RC-505 which manages everything) contains the main logic to render the streams data, the hall of fame, the jukebox and the song explorer.
- `pedal.js` (like the sustain pedal to add texture) handles the translation of some elements.
- `menu.js` manages the toggled menu.
- `stats.js` manages the stats figures display.

The database and the stats figures are created with Python scripts (see [here](https://github.com/0ctagon/tierlist-scripts)). The SVG files are from [svgrepo](https://www.svgrepo.com/).