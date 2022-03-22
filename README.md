# Dark Theme README
At Purdue Global Unversity, we use vitalsource online ebooks for many of our textbooks. This CSS override is my attempt at making my reading experience a bit more enjoyable on my desktop and laptop. 

## Notes on Dark Theme
- Overrides CSS styles with Chrome Extension *Stylebot*
- Only applies custom CSS to vitalsource reader web pages
- CSS suitable for desktop screen resolutions

## How to Use Dark Theme
1. Install *Stylebot* Chrome extension
2. Go to Stylebot options, then add new style for URL **^.*vitalsource\.com\/(reader|book|mosaic).*$**
3. Add all CSS from [vitalsource.css](/vitalsource.css)
4. Save changes, and load vitalsource ebook. 

## Theme Screenshot
![Theme Screenshot](/dark-theme.PNG)

## Theme Troubleshooting
- Make sure to *Reset to publisher format* in vitalsource Reader Preferences if you applied any custom preferences before installing the dark theme. The custom CSS was written to override the original publisher format.
