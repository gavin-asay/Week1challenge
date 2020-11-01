horiseon website code refactor
==============================

Weekly challenge was to refactor HTML and CSS on a straightforward single-page application. The original site was largely functional and visually correct apart from a broken link due to a missing id.

The following changes were made to index.html:
* New, informative title
* Most div tags were replaced with more specific tags to improve accessibility and search engine compatibility. The update code now includes header, footer, nav, section, and article tags where appropriate.
* Some classes were removed following CSS optimization.
* Comments added to clarify flow of the document.

The following changes were made to style.css:
* Consolidated numerous redundant rulesets that were identical for different classes, reducing the file length by some 60 lines.
* Reorganized order of rulesets to match the flow of the site's content and HTML file.
* Added comments delineating different sections of the page.

https://gavin-asay.github.io/Week1challenge/

https://github.com/gavin-asay/Week1challenge

![Screenshot of horiseon page on GitHub Pages](./assets/images/horiseon_app.jpg)