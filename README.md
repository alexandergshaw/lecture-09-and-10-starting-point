# lecture-09-and-10-starting-point

## Fieldnotes responsive website

Open `index.html` in a browser, or serve this directory with
`python3 -m http.server 8000` and visit `http://localhost:8000`.
No installation or build step is required.

The page uses CSS Grid for the hero, trip cards, and information sections,
plus Flexbox for navigation and card content. At 900px and below, the trip
grid changes from three columns to two. At 600px and below, sections stack
into one column and the navigation moves below the wordmark.

To check the assignment requirements, use browser DevTools to set the
viewport to 320px, 768px, and 1200px. Confirm that all content and links
remain usable, columns change at the breakpoints, and there is no horizontal
scrolling or overlapping content. There is no existing automated test suite.