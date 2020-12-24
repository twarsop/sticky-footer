# sticky-footer
Every time I need to add a sticky footer to a website I always seem to forget how to do it and have to search round the internet for the example I used last to time to help me. Invariably I can never find that example and spend hours pulling my hair trying to figure out how to write a sticky footer again.

This hair pulling has motivated me to create this repo for one very simple purpose: to provide (me) an easy to find, definitive, simple example of to write the html and css for a sticky footer.

# What is a sticky footer?
An element on the page that sticks to the bottom regardless of the amount of content within the actual page above it. 

Or to put it diagrammatically:
<!-- language: lang-none -->
    --------------------------------------------
    | container                                |
    |    ----------------------------------    |
    |    |    content                     |    |  
    |    ----------------------------------    |
    |                                          |
    |                                          |
    |                                          |
    |                                          |
    |                                          |
    |                                          |
    --------------------------------------------
    | sticky footer                            |
    --------------------------------------------

<!-- language: lang-none -->
    --------------------------------------------
    | container                                |
    |    ----------------------------------    |
    |    |    content                     |    |  
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    |                                |    |
    |    ----------------------------------    |
    --------------------------------------------
    | sticky footer                            |
    --------------------------------------------