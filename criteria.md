# Quality Criteria for Frontend Course 
**Bro Academy**

**Purpose:**<br />
When developing a website, there are many conditions that must be met to ensure the site displays correctly.

❤️ Mandatory for passing the course <br />
💛 Required for the highest grade <br />
💚 Optional  <br />

## 1. General 

**1.1 ❤️ Bundler is used as a build tool**  
   The project is set up with any Bundler for automation tasks.  

**1.2 ❤️ Public and node_modules folders should not be in the GitHub repository**  
   The `.gitignore` file is configured to exclude **automatically generated build files**.  

**1.3 ❤️ The project builds correctly**  
   - After running `npm start` or `npm run dev`, the project should build **without critical errors**.  
   - The final files should be correctly placed in `public/` **without manual intervention**.  
   - The build process **should stop** if critical errors occur.  

**1.4 ❤️ No errors (`error`) in the console during the build process**  
   - The console should not show **red error messages (`error`)**.  
   - All dependencies should be installed, and plugins should be correctly configured.  

**1.5 💛 No warnings (`warning`) in the console during the build process**  
   - The console should not show **yellow warning messages (`warning`)**, such as **package incompatibilities or missing dependencies**.  
   - The code should follow best practices and be validated with linters (`stylelint`, `eslint`, `htmllint`).  

**1.6 ❤️ File names and extensions should be lowercase without spaces.** <br />

   ❌ *Bad:*
   ```html
   Style.css
   Images
   catalog page.html
   loginPage.html
   ```

   ✅ *Good:*
   ```html
   style.css
   img
   index.html
   catalog-page.html
   ```

**1.7 ❤️ Uniform code formatting**   <br />
- Consistent indentation (tabs/spaces)  
- Consistent empty lines  
- Correct nesting  
- Use auto-formatting in code editor
   
   ❌ *Bad:*
   ```css
   .link:before {
      font-size:         12px;
   line-height:  14px; 
   }

   .link::after {
             font-size: 10px;
         line-height:  20px; 
   }
   ```
   
   ✅ *Good:*
   ```css
   .link::before {
      font-size: 12px;
      line-height: 14px; 
   }
   .link::after {
      font-size: 10px;
      line-height: 20px; 
   }
   ```
   
**1.8 ❤️ Layout matches design (Perfect Pixel)**  
- 1:1 block placement  
- Up to 5px text tolerance  
- 1–2px adjustments allowed for poor designs

**1.9 ❤️ Cross-browser compatibility**  
- Works in Chrome, Opera, Firefox, Safari, Edge  
- Tools: BrowserShots, Browserling, BrowserStack, LambdaTest

**1.10 ❤️ Handles content overflow gracefully**  
When adding more text to elements: <br />
- Text and images should not break layout  
- Overflow should not break the grid

## 2. GIT

**2.1 ❤️ The site should have a GitHub repository**  

**2.2 ❤️ There's no system file like `.DS_Store` or `Thumbs.db` in the repository**  

**2.3 ❤️ There are no commits in the target branch (usually `main`)**  

**2.4 💛 Commit messages are descriptive**  
✅ good: "fix validation in contact form"  
❌ bad: "fix", "sdfsdf"  
Use the imperative mood  
✅ good: "fix validation"  
❌ bad: "fixed validation"

**2.5 💛 Each commit is a logical unit**  
Don't commit more than described.

**2.6 💚 Commits are atomic**  
Logical units, the smallest possible size.

**2.7 💚 Commit message no longer than 60 symbols**  
To be visible in GitHub UI.

## 3. Nunjucks

**3.1 ❤️ The project is structured using Nunjucks templates**  
- **Layouts (`layouts/`)** contain the base structure (`base.njk`).  
- **Partials (`partials/`)** store reusable components (header, footer, product cards, etc.).  
- **Text content is moved to `data.json`** for better management of dynamic data.  

**3.2 💛 Loops, variables, and dynamic data are used in Nunjucks**  
- **Variables are created** using `{% set %}` or fetched from `data.json`.  
- **Loops (`{% for %}`)** are used to generate lists of elements (e.g., products, reviews).  
- **Conditional statements (`{% if %}`)** are used to check for data presence or to display different blocks.  
 

## 4. HTML

**4.1 ❤️ The document must begin with `<!DOCTYPE HTML>`.**  
A correct doctype ensures the pages display according to standards.   

**4.2 ❤️ Each page must have the lang attribute set according to the page's language.**

**4.3 ❤️ The document must have a specified encoding.**  
UTF-8 is universal and compatible; it is the current standard.  

**4.4 ❤️ Title Tag must be set on all pages.**  
SEO: Google trims titles between 472 to 482 pixels, so the title length should be around 55 characters.  
`<title>` must be unique on each page.  

**4.5 ❤️ All elements must be marked up and styled.**

**4.6 ❤️ No gross markup errors.**  
❌ *Gross errors:*  
- Using tags other than `<a>` for links  
- Using `<span>` for large layout blocks  
- Using `<br>` for line breaks in text  

✅ *Not gross errors:*  
- Absence of semantic tags  
- Violating the hierarchy of headings  

**4.7 ❤️ Semantic Markup**  
Use semantic tags like `<header>, <main>, <footer>, <nav>`, etc.  
Headers should use `<h1>` to `<h6>`, paragraphs `<p>`, and `<div>` for containers.  

❌ *Bad:*  
```html
<div class="hr"></div>
<div class="header"></div>
```

✅ *Good:*  
```html
<hr>
<header></header>
```

**4.8 ❤️ The layout must be valid.**  
HTML must pass validation at [w3.org validator](https://validator.w3.org/)

**4.9 ❤️ All pages should be linked and checked for broken links.**

**4.10 ❤️ Each page must have an `<h1>` tag that is different from the page title.**

**4.11 💛 The heading tree structure is maintained.**  
From the headings, a table of contents can be formed like in a book.  
Heading levels go in order from top to bottom and are not skipped.  
Check it on [yoksel.github.io/html-tree](https://yoksel.github.io/html-tree)

**4.12 💛 External links should have the attribute `target="_blank"`.**

**4.13 💛 Use the minimum possible number of HTML elements.**  
No unnecessary wrappers in the markup.  
There should be no empty blocks for presentational purposes. Use pseudo-elements for this.  
🚩 If an element has no styles or they can be transferred to the nearest enclosing element.

**4.14 💛 The logo on internal pages should lead to the home page.**  
On the home page, the logo should not lead to any page.

**4.15 💚 Description meta tag must be set**  
The `<meta type="description">` must be unique and less than 150 characters.  
It appears in search engines below the title.  

## 5. BEM

**5.1 ❤️ All independent components are defined as separate blocks.**  
Each block is autonomous and does not depend on others.

**5.2 ❤️ All subordinate parts are correctly defined as elements.**  
All internal parts of a block are properly described using elements (`block__element`).

**5.3 ❤️ BEM element not used outside of related block**

**5.4 ❤️ Modifiers correctly describe states or variations.**  
Modifiers reflect states, sizes, types, or other variations of a block or element.

**5.5 ❤️ Modifiers must not include:**  
- Colors: Instead of `block--red`, use a more abstract name like `block--danger`  
- Numbers: Instead of `block--1`, use descriptive names like `block--first`  
- Tag names: Instead of `block--div`, use meaningful modifiers like `block--highlighted`

**5.6 ❤️ Modifiers cannot be used as the only class on a tag.**  
❌ Bad:  
```html
<div class="block--active"></div>
```  
✅ Good:  
```html
<div class="block block--active"></div>
```

**5.7 ❤️ BEM syntax rules are followed.**  
Correct format is used: `block`, `block__element`, `block--modifier`.  
No errors such as:  
- Nested elements (`block__element__subelement`)  
- Use of global classes (`active` instead of `block--active`)

**5.8 ❤️ Block, element, and modifier names must be meaningful.**  
Each class should logically explain its purpose:  
❌ Bad: `block--style1`  
✅ Good: `block--disabled`

**5.9 ❤️ Classes are named correctly:**  
- No transliteration in class names, attributes, etc.  
- Only lowercase letters are used  
- If a class name consists of several words, use hyphens between the words: `slider-block`, etc.  
- Do not use presentational classes that specify styles (`fz-15`, `color-green`, `block-left`)  
- The class name should reflect the purpose (semantics) of the block, not its appearance

## 6. Images

**6.1 ❤️ Correct Image Format**  
Use **WEBP** for photos, and **SVG** for low-color images and icons.

**6.2 ❤️ Extract images without style filters from the design.**  
Shadows, rounded corners, filters, blend modes, gradients, transparency, and other effects should be added using **CSS**, not embedded in the image.

**6.3 ❤️ Image Insertion**  
- Use `<img>` for **content images** (e.g. product photos, blog illustrations)  
- Use `background-image` for **decorative images** (e.g. icons, backgrounds, UI decoration)

**6.4 ❤️ Specify dimensions for all images.**  
Do not use `px` inside the `width` and `height` attributes.  
✅ Example:  
```html
<img src="example.jpg" width="100" height="100">
```

**6.5 ❤️ Provide alt text for all images.**  
Accessibility is essential. Use short and descriptive `alt` attributes.  
More: [Alt Texts — Axess Lab](https://axesslab.com/alt-texts/)  
✅ Example:  
```html
<img src="example.jpg" alt="photographer with nikon camera">
```

**6.6 ❤️ Use vector sprite**  
Combine multiple icons into a single SVG sprite to optimize loading and maintain consistency.

**6.7 💚 Favicon icons display correctly.**  
- Formats: `.ico`, `.png`, `.svg`  
- Sizes: `16x16`, `32x32`, `48x48`, `64x64`

## 7. Forms

**7.1 ❤️ Appropriate types for input are specified.**  
This is especially important for mobile devices as they use different keyboards for different input types.  
[http://mobileinputtypes.com](http://mobileinputtypes.com)

**7.2 ❤️ Each form element should have a `<label>`.**  
If there is no explicitly set text for the label, then add it to the markup and hide it accessibly.

**7.3 ❤️ Basic HTML form validation should be implemented.**  
- The form cannot be submitted with empty fields.  
- Data in fields must match the field format.

**7.4 💛 Resizing `<textarea>` should not break the layout.**

## 8. Preprocessor

**8.1 ❤️ SCSS preprocessor is used**  
All styles must be written using SCSS syntax.

**8.2 ❤️ Styles are split into components**  
SCSS files should be separated by responsibility:  
- `_variables.scss`, `_mixins.scss`, `_buttons.scss`, `_header.scss`, etc.  
- Use `@use` in the main file.

**8.3 ❤️ Custom properties and/or SCSS variables are used for colors and fonts**  
Define all color and font values as variables using SCSS or native CSS variables:  
- SCSS example:  
  ```scss
  $primary-color: #ff6347;
  $font-main: 'Roboto', Arial, sans-serif;
  ```
- CSS example:  
  ```css
  :root {
    --primary-color: #ff6347;
    --font-main: 'Roboto', sans-serif;
  }
  ```

**8.4 💛 Mixins are used where appropriate**  
Use mixins to avoid repeating styles (e.g., media queries, vendor prefixes):  
```scss
@mixin flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

**8.5 💛 No magic numbers**  
Avoid hardcoded values without context.  
Each value should be:
- Named and reusable  
- Explained in a comment if it seems arbitrary  
- Derived from a variable or calculation

✅ Good:  
```css
margin-bottom: $section-spacing;
```

❌ Bad:  
```css
margin-bottom: 73px; // ??? why
```

## 9. CSS

**9.1 ❤️ Single CSS File**  
Use a single CSS file for all pages (e.g., `style.css`).  
`Normalize.css` should be included as an additional file.

**9.2 ❤️ All fonts used in the design are connected to the pages.**  
Preferably loaded from Google Fonts.

**9.3 ❤️ Provide fallback fonts and family types at the end of the font list.**  
Example:  
```css
font-family: Roboto, Arial, sans-serif;
```

**9.4 ❤️ Do not use `!important` in CSS.**  
❌ Bad:  
```css
.link { color: red !important; }
```  
✅ Good:  
```css
.selector .link { color: red; }
```

**9.5 ❤️ Do not use `#id` for styling.**  
❌ Bad:  
```css
#link { color: red; }
```  
✅ Good:  
```css
.link { color: red; }
```

**9.6 ❤️ Use consistent units for element sizes and positioning.**  
Do not mix `px` and `em`.  
If font-size/height is in `em`, then padding/margin should also be in `em`.

❌ Bad:  
```css
.link {
  font-size: 12px;
  line-height: 2em;
}
.text {
  padding: 8px;
  margin: 2.5em;
}
```  
✅ Good:  
```css
.link {
  font-size: 12px;
  line-height: 2px;
}
.text {
  padding: 8px;
  margin: 2.5px;
}
```

**9.7 ❤️ Use appropriate properties for animations.**  
Prefer `transform`, `translate`, `rotate`, `scale`, `opacity`.  
Avoid repaint-triggering properties like `width`, `height`, `position`, `padding`, `margin`.

❌ Bad:  
```css
.link:hover {
  left: 50px;
}
```  
✅ Good:  
```css
.link:hover {
  translate: 50px;
}
```

**9.8 ❤️ All element states from the style guide are implemented.**

**9.9 ❤️ Links must respond to `:hover`, `:active`, and `:focus`.**  
If not defined in design, use underline, color change, etc.

**9.10 💛 Avoid nesting selectors more than two levels deep.**  
❌ Bad:  
```css
.header .nav .nav-item .nav-link {}
```  
✅ Good:  
```css
.nav-link {}
.header .nav-link {}
.footer .nav-link {}
```

**9.11 💛 Avoid styling tags directly (except `body`, `ul`, `a`, `img`).**  
❌ Bad:  
```css
section {}
header {}
```  
✅ Good:  
```css
body {}
ul {}
a {}
img {}
.page-header {}
```

**9.12 💛 Elements with background images should have a matching background color**  
Especially important for text contrast.  
Example:  
```
section {
  background-image: url(sunset.jpg);
  background-color: orange;
}
```

**9.13 💛 Colors should be in a consistent format (hex or rgba).**  
Avoid named colors.  
❌ Bad:  
```css
.link {
  color: black;
}
```  
✅ Good:  
```css
.link {
  color: #000;
}
```

**9.14 💛 Interactions (`:hover`, `:active`, `:focus`) should not change document flow.**  
Elements near the interactive one should not shift.

**9.15 💚 Include Normalize.css**  
[https://necolas.github.io/normalize.css/](https://necolas.github.io/normalize.css/)  
Should be linked **before** the main stylesheet.

## 10. Layout

**10.1 ❤️ Use flex or grid for layouts**  
Do not use tables or absolute positioning for layout purposes.

**10.2 ❤️ Responsive adaptive layout is implemented.**  
All pages must adapt gracefully to different screen sizes.  
Layouts should reflow and resize content properly without breaking.

**10.3 ❤️ No horizontal scroll on the full page.**  
The main document (`html` and `body`) must not scroll sideways on any screen size.  
Overflow should be handled inside specific containers if needed.

**10.4 ❤️ Burger menu works on mobile.**  
The navigation menu must be hidden behind a burger icon on small screens and must open/close correctly on tap.

**10.5 ❤️ Filter panel opens correctly on mobile.**  
If the page includes a filter section, it must be collapsible and function properly on smaller viewports.

**10.6 ❤️ Horizontal scroll is enabled for specific blocks.**  
On the homepage, sections indicated in the design (e.g., carousels or card strips) should scroll horizontally **on mobile only**, without affecting the rest of the page.

**10.7 ❤️ Breakpoints are well chosen.**  
Use media queries that reflect real device widths (not arbitrary pixels).  
Ensure content looks good across common breakpoints from Figma.

**10.8 ❤️ Consistent spacing and alignment.**  
Padding and margins should remain visually balanced across breakpoints.  
Avoid excessive gaps or cramped areas, especially on mobile.

**10.9 ❤️ Interactive elements are accessible on mobile.**  
Touch targets (e.g., buttons, links, toggles) must be large enough to tap easily.  
Key interactions like scrolling, menu toggling, and filters should feel smooth and intuitive.