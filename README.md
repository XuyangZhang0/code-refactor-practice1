# horiseon-code-refactor
Product of a code refactor practice, following accessibility standards, with ***semantic HTML*** tags,  alt attributes, properly ordered heading attributes, etc.

## Change Logs
1. Updated title tag in `index.html` to be Horiseon Marketing so that the site has meaningful name
2. Changed the tag `<div class="header">` to be `<header>` in `index.html`, leveraging ***semantic HTML*** tag
3. Updated all `header` class references, to `header` element in `style.css`, as a follow up action to change #2 ensure the page function remain the same
4. Added comments in `index.html` to indicate the start and closing of the `header` section of the website
5. Updated the `div` tag in `header` element to be `<nav>` in `index.html`, leveraging ***semantic HTML*** tag
6. Updated all `header div` selector references, to `nav` element in `style.css`, as a follow up action to change #5 ensure the page function remain the same
7. Replaced `<div class="hero"></div>` element with `figure` element that contains a `img` element in `index.html`, with ***`alt`*** text
8. Updated `hero` class styling in `style.css` and removed `background-image` url, as the function is surfaced in `index.html`
9. Changed `<div class="content">` element to be `<main>` in `index.html`, leveraging ***semantic HTML*** tag
10. Updated `content` class reference in `style.css` to be `main` selector
11. Updated `div` tags within `<main>` to be section, leveraging ***semantic HTML*** tag
12. Added ***`alt`*** attribute to 3 images in the `main` section within the `index.html`
13. Removed unnecessary/unused class declarations in `<main>` element from `index.html`, and added id declaration for the first section, to ensure the anchor link in nav functions
14. Updated all `search-engine-optimization`, `online-reputation-management`, `social-media-marketing` class references in `sytle.css` to be `id` (# instead of .)
15. Updated `<div class="benefits">` element to be aside in `index.html`, leveraging ***semantic HTML*** tag
16. Added ***`alt`*** attributes to three images in `aside` section of the index.html
17. Updated `benefit-lead`, `benefit-brand`, `benefit-cost` classes to be `benefit-item` in `index.html`
18. Updated all above class references to `benefit-item`, and removed redundant styling in `style.css`
19. Updated `div` tag in the `aside` element to be `section` in `index.html`, leveraging ***semantic HTML*** tag
20. Updated `<div class="footer">` element to be `<footer>` in `index.html`, leveraging ***semantic HTML*** tag
21. Replaced all class `footer` references in `style.css` to be `footer` element selector, as a follow up action to change #20 to maintain page function
22. Added a class `marketing-function-item`, and associate to sections in `<main>`, so that we can reduce redundant styling.
23. Updated `search-engine-optimization`, `online-reputation-management`, `social-media-marketing` id reference to be class `marketing-function-item`, and removed redundant styling code in `style.css`
24. Added comments in `index.html`
25. Updated `footer` `heading` to be `h4` instead of `h2` in `index.html`, and corresponding css selector in `style.css`

## Self-Check Against Acceptance Criteria
GIVEN a webpage meets accessibility standards
- [x] WHEN I view the source code THEN I find ***semantic HTML*** elements
- [x] WHEN I view the structure of the HTML elements THEN I find that the elements follow a logical structure independent of styling and positioning
- [x] WHEN I view the icon and image elements THEN I find accessible alt attributes
- [x] WHEN I view the heading attributes THEN they fall in sequential order
- [x] WHEN I view the title element THEN I find a concise, descriptive title

## GitHub Page Link
This result of this excercise is published on [GitHub Pages](https://xuyangzhang0.github.io/code-refactor-practice1/)

## Website Rendering Screenshot after Refactoring

Below is the website rendering screenshot after refactoring

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/images/01-html-css-git-homework-demo.png)



