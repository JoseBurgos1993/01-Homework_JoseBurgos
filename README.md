# Homework2_JoseBurgos

These are all my changes to the original code.


REMOVED .header div ul { list-style-type: none; } in style.css and added the code to .header div{}.
It seemed unnecessary for it to have its own block when the list-style-type could be determined
one block up.

Changed title in index.html line 7 from "website" to "Horiseon Home"

Add an ID for search-engine-optimization because the link at the top of the page wasn't working.

Changed class="header" to just header. Did the same for footer. Made appropriate changes in style.css.

Changed the div inside of the header to nav.

Changed the class="content" to section.

Changed the class="benefits" to aside

Changed class="seo" to id="seo" since there is only one occurance of it. Also, in style.css,
I changed "header h1 .seo" to just "#seo". I didn't see a need for that.

Changed "header h1" to just "h1" since h1 is was not used outside of the header.

Minor indentation and spacing changes in index.html because I prefer how it looks.

In style.css, I combined "search-engine-optimization {...}" with the other two since they
had the same code.

In style.css, I removed the "#search-engine-optimization img { max-height: 200px; }" along with the other
two IMG IDs parts. I moved the "max-height: 200px;" to the ".float-right {...}" and ".float-left {...}".

In style.css, I changed "#search-engine-optimization h2 { ... }" to just "section h2 {...}", and removed
the code for the other two ID's.

I moved the code around in style.css so that related elements are next to each other instead of being
randomly spread around.

I moved the code for the big image of all the people doing business to index.html. I removed the div
and instead made it an IMG with an id="hero" rather than a class. I made the appropriate changes to style.css.

I added alt attributes to all images.