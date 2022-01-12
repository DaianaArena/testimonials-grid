# testimonials-grid
(IN PROGRESS) testimonials grid section challenge by front-end mentor.

CORRECCIONES 

First fix html

no text in divs alone, use meaningful elements
hint - you need headings earlier in these boxes if you're going to use them. You could also use figures with figcaptions and blockquotes
Change h2s to paragraphs. Those sentences don't make sense as h2s
Give each box the same class so you can attach shared styles to it (remember elements can have multiple classes)
------
Then in css

remove the 5px columns/rows in grid template
Remove margins from boxes
Set a max width on the grid
Set a little padding on the wrapper eg body (to stop content from hitting screen edges)
Min height 100vh and grid/flex properties can be used to vertically center grid on page
Remove display grid and grid templates from individual boxes in desktop media query - the boxes themselves have the same layout on all screen sizes
Have one class that sets the shared base styles of boxes (padding, border radius, box shadow, text sizes, one of the color sets)
Then for other boxes that have different colors, use another class just to change that
In the grid, change rows to auto not 1fr. You want them to grow and shrink
Remove column and row gap, just use the gap property. Something like 1fr
Once these changes have been made the grid line numbers will need updating. Personally I find it a lot easier using grid template areas than line numbers
