# Lesson 9. Preprocessors

**[Presentation 1](presentations/presentation-9-preprocessors.pdf)**<br />
<!-- **[Manual](manuals/manual-9-preprocessors.pdf)**<br />  -->

**Part 1:** <br /> 
**[Group 1 video](https://drive.google.com/file/d/1hBCsdvxIbdhecLFR4KcMBZteI8-4MiG-/view)**<br />
<!-- **[Group 2 video]()**<br /> -->

<!-- **Part 2:** <br />
**[Group 1 video]()**<br />
**[Group 2 video]()**<br />  -->

# Homework

1. **Split your styles into multiple SCSS files**
- One BEM block = one SCSS file
- Use separate files for:
    - variables
    - mixins
    - base styles
    - components
2. **Move repeated values into SCSS variables**
3. **Use SCSS nesting**

## Criteria 

❤️ **SCSS preprocessor is used** <br />
❤️ **Styles are split into components** <br />
❤️ **SCSS variables are used for colors and fonts** <br />
💛 **Mixins are used where appropriate** <br />
💛 **No magic numbers (all values are explained or reusable)** <br />

# Additional Materials

## Courses 

**[Learn Sass: Mixins and Parent Selector (Codecademy)](https://www.codecademy.com/learn/learn-sass-mixins-and-the-parent-selector)**: A course dedicated to advanced features of the Sass preprocessor, including using mixins and the parent selector.

**[Learn Sass: Best Practices (Codecademy)](https://www.codecademy.com/learn/learn-sass-best-practices)**: A course that teaches best practices and techniques for working with Sass, improving the structure and organization of styles.

**[Learn Sass: Functions and Operations (Codecademy)](https://www.codecademy.com/learn/learn-sass-functions-and-operations)**: Learning functions and operations in Sass, allowing for the creation of more dynamic and adaptive styles.

**[Learn Sass: Fundamentals (Codecademy)](https://www.codecademy.com/learn/learn-sass-fundamentals)**: An introductory course on Sass, covering the basics of this powerful CSS preprocessor.

**[Learn Sass (Codecademy)](https://www.codecademy.com/learn/learn-sass)**: A comprehensive course on Sass, covering all aspects of working with this preprocessor, from basics to advanced techniques.

**[Store Data with Sass Variables (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/store-data-with-sass-variables)**:  
An introduction to using variables in Sass for storing values like colors, fonts, and sizes for more maintainable and scalable stylesheets.

**[Nest CSS with Sass (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/nest-css-with-sass)**:  
Learn how to nest selectors in Sass to reflect the structure of your HTML and keep related styles organized.

**[Create Reusable CSS with Mixins (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/create-reusable-css-with-mixins)**:  
Understand how to use mixins in Sass to avoid code repetition and create flexible, reusable style patterns.

**[Use @if and @else to Add Logic to Your Styles (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/use-if-and-else-to-add-logic-to-your-styles)**:  
A guide to adding conditional logic to your Sass styles using `@if` and `@else` statements for more dynamic CSS.

**[Use @for to Create a Sass Loop (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/use-for-to-create-a-sass-loop)**:  
Learn how to use `@for` loops in Sass to generate repetitive styles automatically and reduce manual code duplication.

**[Use @each to Map Over Items in a List (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/use-each-to-map-over-items-in-a-list)**:  
Explore how to loop over a list of values with `@each` to apply styles dynamically based on a set of predefined items.

**[Apply a Style Until a Condition is Met with @while (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/apply-a-style-until-a-condition-is-met-with-while)**:  
Use `@while` loops in Sass to repeatedly apply styles as long as a given condition remains true.

**[Split Your Styles into Smaller Chunks with Partials (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/split-your-styles-into-smaller-chunks-with-partials)**:  
Learn how to organize your SCSS by splitting your styles into partial files and importing them into a main stylesheet.

**[Extend One Set of CSS Styles to Another Element (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/sass/extend-one-set-of-css-styles-to-another-element)**:  
Discover how to use `@extend` to share and reuse styles between selectors without repeating the same code.

## 🧱 **CSS Preprocessors (Overview & Docs)**

**[What are CSS Preprocessors? (Raygun)](https://raygun.com/blog/css-preprocessors-examples/)**  
Intro article with examples of Sass, LESS, and Stylus, comparing syntax and use cases.

**[How to Use CSS Preprocessors (Medium)](https://medium.com/@aicontentpace/how-to-use-css-preprocessors-953ebc521e94)**  
A beginner-friendly guide on why and how to use preprocessors like Sass.

**[Sass Docs](https://sass-lang.com/)**  
The official Sass documentation — the go-to source for all features.

**[LESS Docs](http://lesscss.org/)**  
Official documentation for the LESS preprocessor.

**[Stylus Docs](http://stylus-lang.com/)**  
Official docs for Stylus — known for its minimal syntax.

### 💡 **Sass Features & Logic**

**[How to Write Loops with Preprocessors (CSS-Tricks)](https://css-tricks.com/how-to-write-loops-with-preprocessors/)**  
Examples of `@for`, `@each`, and `@while` in Sass.

**[The Main Features of Sass (Dev.to)](https://dev.to/timothyrobards/the-main-features-of-sass-47k2)**  
Overview of core Sass features: variables, nesting, mixins, functions, inheritance.

### 🧱 **BEM + Preprocessors**

**[BEM and SASS? What Are They And How To Use Them (PullRequest Blog)](https://www.pullrequest.com/blog/bem-and-sass-whats-the-difference-and-how-to-use-them/)**  
An overview of BEM methodology and the SASS preprocessor — explaining the difference between them and how to use both together to write cleaner, more maintainable CSS.

## 🎨 **CSS Custom Properties**

**[Using CSS Custom Properties (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascading_variables/Using_CSS_custom_properties)**  
The official MDN guide — everything you need to know about `--vars`.

**[A Complete Guide to Custom Properties (CSS-Tricks)](https://css-tricks.com/a-complete-guide-to-custom-properties/)**  
Deep dive with examples on theming, dynamic styles, fallbacks, and more.

**[7 Uses for CSS Custom Properties (CSS-IRL)](https://css-irl.info/7-uses-for-css-custom-properties/)**  
A list of creative, real-world use cases for CSS variables.

### 🧠 **Advanced CSS Logic (Inline Conditionals)**

**[CSS Conditionals (Lea Verou, part 1)](https://lea.verou.me/blog/2024/css-conditionals/)**  
Introduction to new inline conditionals in CSS — like `@if`, but natively.

**[CSS Conditionals Now (Lea Verou, part 2)](https://lea.verou.me/blog/2024/css-conditionals-now/)**  
Examples of what’s possible with the latest conditional CSS syntax.

### ⚖️ **CSS Custom Properties vs SCSS Variables**

**[CSS Custom Properties vs SCSS Variables (Frontendly)](https://frontendly.io/blog/css-custom-properties/)**  
Great breakdown comparing runtime (CSS) vs compile-time (SCSS) variables.

## 🧬 **CSS Nesting**

**[Using CSS Nesting (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_nesting/Using_CSS_nesting)**  
Official browser support and syntax guide.

**[CSS Nesting (Chrome Developers)](https://developer.chrome.com/docs/css-ui/css-nesting)**  
Overview of native CSS nesting, limitations, and best practices.

**[CSS Nesting Explained (Pivale)](https://www.pivale.co/blog/css-nesting)**  
Beginner-friendly explanation of how native CSS nesting works.

**[CSS Nesting (Ahmad Shadeed)](https://ishadeed.com/article/css-nesting/)**  
Detailed guide with examples and thoughts on real use cases.

**[CSS Nesting & UX (Ahmad Shadeed)](https://ishadeed.com/article/css-nesting-ux/)**  
How CSS nesting can affect user experience and maintainability.

## ❗ **Magic Numbers in CSS**

**[Magic Numbers in CSS (CSS-Tricks)](https://css-tricks.com/magic-numbers-in-css/)**  
A classic article explaining what magic numbers are, why they’re problematic, and how to avoid them with better layout techniques and thinking in context.

**[Magic Numbers in CSS (Code Readability)](https://www.codereadability.com/magic-numbers-in-css/)**  
A practical look at magic numbers in everyday CSS and how they hurt maintainability. Includes common causes and how to refactor your code to remove them.

## New CSS features

### 📏 **Container Queries**

**[CSS Container State Queries (Ahmad Shadeed)](https://ishadeed.com/article/css-state-queries/)**  
What container state queries are and how they can improve responsive design.

**[Complete Guide to Container Queries (Ahmad Shadeed)](https://ishadeed.com/article/css-container-query-guide/)**  
A full guide to working with `@container` rules and responsive components.

### 🔍 **`:has()` Pseudo-Class**

**[Guide to :has() (Ahmad Shadeed)](https://ishadeed.com/article/css-has-guide/)**  
Learn how the powerful `:has()` pseudo-class can replace JavaScript for some interactivity.

