# Horiseon-Accessibility-Update
Update Horiseon Social Solution Services, Inc. for SEO and accessibility standards.
View site here - https://keiththarp.github.io/Website-Code-Refactor-Accessibility-Update/

## Initial Assessment
Upon initial viewing of the website, I realized the site was not optimized for mobile viewing.

Given the client business and story, along with current trends, it seemed appropriate to address the mobile and small screen presentation of the website as an accessibility issue along with cleaning and reformatting the code for semantics and accessibility.

## Notes on refactoring project
For accessibility sake, I decided to restructure the site matching the existing design/layout, using CSS grid. I tried flexbox first but given the two dimensional layout, grid ended up working better.

**HEADER/NAV**
* Starting from the top, the first change was dealing with the long menu breaking out of the header on smaller screens. - I used information from this blog post to create a mobile/small screen friendly menu - https://blog.teamtreehouse.com/create-an-absolute-basic-mobile-css-responsive-navigation-menu
* Added link to main logo to return to HOME as is standard.
* Repaired Nav link for #SEO section
* Added pipes to delineate menu items in desktop nav (removed on mobile)

**HERO IMAGE**
Again, for accessibility sake I moved the hero image out of the background and added alt text.

**MAIN HTML**
* Altered tags to use semantic HTML tags for ease of reading.
* Commented HTML for ease of reading.
* Added 'horizontal rule' dividers between sections for readability in sidebar.

**IMAGES**
* Added alt text for images. 
* To fix slow loading of site I resized all images. Most were excessively large. > 8600 pixel image for 1700px display. > 7000 pixel image for 300px display, etc.

**CSS**
* Consolidated the repetition of CSS properties.
* Added media query to redraw site for smaller screens with grid layout.
* Organized and commented CSS for ease of reading




