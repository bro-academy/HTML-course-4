# Lesson 5. Introduction to CSS

**[Presentation 1](presentations/presentation-5-1-css.pdf)**<br />
**[Presentation 2](presentations/presentation-5-2-css.pdf)**<br />
**[Manual](manuals/manual-5-css.pdf)**<br /> 

**Part 1:** <br />
**[Group 1 video](https://drive.google.com/file/d/1b77Ye3Dp6DfRdDHp3fJjax4U0iB7K_PN/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/1YfdfzHqi8UL2Tw1LL4SCSTOWRj4n4IoY/view?usp=sharing)**<br />

**Part 2:** <br />
**[Group 1 video](https://drive.google.com/file/d/1f3MwrpqZpuwj_c0DochkIcnaZdT9CAVY/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/1kmlzLsFs6evaeaR4Cw8cT1W5TcEGYE_s/view?usp=sharing)**<br />

# Homework

1. Add fonts using [Google Fonts](https://fonts.google.com/).
2. Open file `style.css` and write basic styles for the marked-up blocks using Emmet.
      - font-*: font type / font weight / font size 
      - text properties: letter spacing / text align / text decoration / line height
      - text color
      - borders / border radius
      - list-style 
      - opacity  
      - background-color

3. Optional: Connect [normalize.css](https://necolas.github.io/normalize.css/) to your project as a separate file, use `<link>` tag in `<head>`.

## Criteria CSS

❤️ **Single CSS File** <br />
Use a single CSS file for all pages (style.css). <br />
Normalize.css should be included as an additional file. 

❤️ **All fonts used in the design are connected to the pages.** <br />
Preferably from Google Fonts. 

❤️ **Provide fallback fonts and family types at the end of the font list.** 
For example:  ```font-family: Roboto, Arial, sans-serif;``` 

❤️ **Do not use !important in CSS.** <br />

❤️ **Do not use #id for styling.** <br />

💛 **Include Normalize.css** <br />
https://necolas.github.io/normalize.css/  <br />
Normalize.css should be linked before the main style file. 

💛 **Avoid nesting selectors more than two levels deep.**  <br />

💛 **Avoid styling tags directly** <br />
except for body, ul, a, img. <br />

💛 **Colors should be in a consistent format (hex or rgba).** <br />
Color notation is either in hex ```(#000)``` or rgba if there is transparency. <br />
Keywords are not used. <br />

## Additional homework:

1. Complete one of the courses to reinforce the theory:
   - [Scaler](https://www.scaler.com/topics/css/) modules 1-3. It takes about two hours to complete, a lot of theory without practice.
   - [Free code camp](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-basic-css-by-building-a-cafe-menu/step-1) A detailed course where you simultaneously markup and style based on a single cohesive project. Complete if you want to practice alongside theory. The first 10 steps are only markup, then CSS starts.

### Games

**[CSS Speedrun](https://css-speedrun.netlify.app/)**: An interactive platform where users can improve their CSS skills by completing a series of speed tasks. The tasks become increasingly difficult, testing knowledge from basic to advanced CSS topics.

**[CSS Diner on Flukeout.github.io](https://flukeout.github.io/)**: An interactive game designed to learn and practice using CSS selectors. Players go through different levels where the task is to correctly select elements on the "plate" using CSS selectors. This is a fun and effective way to get acquainted with various types of selectors and their application in real situations.

# Demos

🟢 **[Example of the + Selector](https://codepen.io/russweakley/pen/zYRvEOp)**: Illustrates how the "+" selector can be used to style elements that immediately follow other elements.

🟢 **[Examples of the letter-spacing Value](http://russmaxdesign.github.io/html-css-tests/sample-letter-spacing/index.htm)**: Provides various examples of using the `letter-spacing` property to adjust the spacing between letters, allowing the creation of more readable or stylistically unique text.

🟢 **[Examples of the line-height Value](http://russmaxdesign.github.io/html-css-tests/sample-line-height/index.htm)**: Demonstrates how different `line-height` values affect the visual perception of text blocks, helping to optimize readability and aesthetic appeal.

**[Underlines](https://codepen.io/michellebarker/pen/xxxjNYa?editors=1100)**: Various ways to style text underlines.

**[Writing Modes](https://codepen.io/michellebarker/pen/vYOmrGe)**: Examples of using different writing modes in CSS that can significantly change the layout and orientation of text and elements on the page.

**[How to Style the cite Attribute of the blockquote Tag](https://codepen.io/russweakley/pen/YzLrOQy)**: A guide on styling citations using CSS.

**[Text-indent](http://russmaxdesign.github.io/html-css-tests/sample-text-indent/index.htm)**: Shows how to use the `text-indent` property to add indentation to the first line of a text block, which can be useful for styling paragraphs or quotes.

**[Tables in CSS](http://russmaxdesign.github.io/html-css-tests/sample-display-table/index.htm)**: Explains how to use the `display: table`, `table-row`, and `table-cell` properties to create layouts that mimic the behavior of HTML tables, but using regular blocks for more flexible design.

# Tools

**[Specificity Calc](https://specificity.keegan.st/)**: An online calculator for determining the specificity of CSS selectors. This tool helps developers understand which styles will be applied to an element based on selector specificity.

**[CSS Selectors Cheatsheet](https://frontend30.com/css-selectors-cheatsheet/)**: An interactive exercise to test understanding of CSS selectors. The exercises increase in complexity, covering more advanced selectors and pseudo-classes.

**[Symbols to Copy](https://symbols.wentin.net/)**: A resource offering various symbols for copying. It can be useful for developers and designers who need unique symbols for their projects.

**[PX to EM Converter](https://www.w3schools.com/cssref/css_pxtoemconversion.php)**: A tool from W3Schools for converting pixels to em. This helps in adaptive web development, easing the transition from absolute to relative units of measurement.

**[CSS Peeper](https://chrome.google.com/webstore/detail/css-peeper/mbnbehikldjhnfehhnaidhjhoofhpehk?hl=en)**: An extension for Google Chrome that allows users to view the CSS properties of elements on a web page without needing to open developer tools.

# Courses

**[Learn CSS: Introduction on Codecademy](https://www.codecademy.com/learn/learn-css-introduction)**: An introductory course on CSS, offering the basics of cascading style sheets, including selectors, units of measurement, and how they are applied to style HTML elements.

**[Learn CSS on Codecademy](https://www.codecademy.com/learn/learn-css)**: A comprehensive course on CSS, covering everything from basic principles to advanced topics like animation, flexbox, and grid layouts. This course is designed for developers of all levels looking to deepen their understanding and improve their skills in creating web styles.

**[Learn CSS: Typography and Fonts on Codecademy](https://www.codecademy.com/learn/learn-css-typography-and-fonts)**: This course focuses on typography and fonts in CSS, teaching how to improve the readability and visual style of content on web pages.

**[Learn Color Design on Codecademy](https://www.codecademy.com/learn/learn-color-design)**: A course on color design, providing in-depth knowledge of color theory, its impact on design, and best practices for using color in web development.

**[Learn CSS: Colors on Codecademy](https://www.codecademy.com/learn/learn-css-colors)**: A course specializing in using colors in CSS. Students learn various ways to define colors and apply them to web page elements.

**[Learn HTML: Tables on Codecademy](https://www.codecademy.com/learn/learn-html-tables)**: A course dedicated to creating and styling tables in HTML. Participants learn how to structure tabular data for users and search engines.

# Additional materials

🟢 **[How to Learn CSS: A Comprehensive Guide](https://www.smashingmagazine.com/2019/01/how-to-learn-css/)**: An extensive guide from Smashing Magazine offering strategies, resources, and advice for beginners in learning CSS.

🟢 **[CSS Best Practice](https://www.slideshare.net/maxdesign/css-best-practice)**: A presentation with best CSS practices, including approaches to organizing and optimizing code.

🟢 **[The Secret Weapon to Learning CSS](https://css-tricks.com/the-secret-weapon-to-learning-css/)**: Get acquainted with the "secret weapon" from CSS-Tricks for learning CSS and effective learning methods.

🟢 **[The CSS Mindset](https://mxb.dev/blog/the-css-mindset/)**: An article discussing the specific approach to CSS development and the mindset necessary for successful work with CSS.

## How to use Figma with CSS styles  

🟢 **[Figma for Developers: How to Work with a Design File](https://www.frontendmentor.io/articles/figma-for-developers-how-to-work-with-a-design-file-m6CZKZ1rC1)**: Frontend Mentor provides a guide on how developers can effectively collaborate using Figma, including tips on navigating and extracting assets from design files.

🟢 **[Explore Text Properties](https://help.figma.com/hc/en-us/articles/360039956634-Explore-text-properties)**: This article details the various text properties available in Figma, helping users understand how to style and adjust text elements within their designs.

🟢 **[View and Adjust Colors in a Mixed Selection](https://help.figma.com/hc/en-us/articles/360042553434-View-and-adjust-colors-in-a-mixed-selection)**: This article covers how to manage and edit colors when working with multiple selected objects in Figma, ensuring consistency and accuracy.

🟢 **[Adjust Corner Radius and Smoothing](https://help.figma.com/hc/en-us/articles/360050986854-Adjust-corner-radius-and-smoothing)**: Instructions on how to customize corner radii and smoothing for shapes in Figma, allowing for precise control over the appearance of rounded edges.

🟢 **[Add Fills to Text and Shape Layers](https://help.figma.com/hc/en-us/articles/360040623954-Add-fills-to-text-and-shape-layers)**: This article explains how to apply fill colors to text and shape layers in Figma, enhancing the visual appeal of your designs.

**[Free Alternative for Figma Dev Mode or Zeplin](https://pxcode.medium.com/free-alternative-for-figma-dev-mode-or-zeplin-4307fb370026)**: A Medium article discussing free alternatives to Figma's Dev Mode and Zeplin for developers looking to collaborate with designers without incurring additional costs.

**[How to Inspect and Get Code from Figma Design Files](https://www.youtube.com/watch?v=184wrgSS_zU)**: A YouTube video tutorial on how to inspect design elements and extract code snippets from Figma, aimed at developers working on front-end implementation.

**[Figma for Developers | Figma Tutorial (2022)](https://www.youtube.com/watch?v=fZ-OU_7aBv4)**: A YouTube tutorial offering a comprehensive walkthrough on how developers can utilize Figma, covering essential features and workflows.

**[Color Models in Figma Design](https://help.figma.com/hc/en-us/articles/360043042113-Color-models-in-Figma-design)**: Figma Help Center explains the different color models supported in Figma, such as RGB, HEX, and HSL, and how to use them in your designs.

**[Guide to Dev Mode](https://help.figma.com/hc/en-us/articles/15023124644247-Guide-to-Dev-Mode)**: Figma Help Center article explaining Dev Mode, a feature designed to streamline collaboration between designers and developers by providing necessary tools and information.

## Connecting Styles

**[CSS Tutorial](https://devdojo.com/guide/css/how-to-use)**: A tutorial on CSS, offering basic knowledge and practical skills for using CSS to style web pages.

**[The `<link>` Tag in HTML](https://www.scaler.com/topics/link-tag-in-html/)**: This article explains the use of the `<link>` tag to link external styles and other resources to the web page. It demonstrates how to properly use this tag to connect style sheets, favicon icons, and other elements.

 **[The `<style>` Tag in HTML](https://www.scaler.com/topics/html/style-tag-in-html/)**: An overview of using the `<style>` tag to add internal styles directly in HTML documents.

 **[The `style` Attribute in HTML](https://www.scaler.com/topics/style-attribute-in-html/)**: An overview of the `style` attribute for directly applying CSS styles to individual HTML elements.

## Normalization

**[Default Browser Styles](https://www.w3schools.com/cssref/css_default_values.php)**: W3Schools offers an overview of default styles for various HTML elements in browsers, helping to understand which styles are applied to elements by default.

**[Body Margin 8px: The Origin Story](https://www.miriamsuzanne.com/2022/07/04/body-margin-8px/)**: An interesting article about the origin of the standard 8px margin for the body tag and its impact on web page styling.

**[Normalize.css GitHub Page](https://github.com/necolas/normalize.css/)**: The official page of the Normalize.css project on GitHub, where you can download the latest version of the library and read the documentation.

**[A Modern CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/)**: Josh Comeau shares his approach to creating a custom CSS Reset, providing a stable foundation for starting website development and improving cross-browser compatibility.

## References

🟢 **[CSS Reference on Codrops](https://tympanus.net/codrops/css_reference/)**: An extensive and detailed CSS reference guide offering explanations and examples of various CSS properties and selectors. A great resource for in-depth understanding and experimentation with CSS.

🟢 **[CSS Almanac on CSS-Tricks](https://css-tricks.com/almanac/)**: A CSS reference from CSS-Tricks offering detailed articles on properties, selectors, and other CSS features. Includes code examples and practical advice.

**[List of All CSS Properties on Web4College](https://www.web4college.com/css-play/)**: A complete list of CSS properties presented in an easy-to-review format. Helps quickly find necessary properties and learn about new ones.

**[CSS Guidelines](https://cssguidelin.es/)**: Tips and recommendations for writing clean, sustainable, and easily maintainable CSS code. Offers best practices and coding standards for professionals.

## Selectors

🟢 **[Syntax and Selectors Cheatsheets](https://www.codecademy.com/learn/learn-css-introduction/modules/syntax-and-selectors/cheatsheet)**: A cheat sheet on CSS syntax and selectors from Codecademy, providing quick access to key concepts.

🟢 **[Learn CSS Fundamentals Combinators](https://www.slideshare.net/inarocket/11-learn-css-fundamentals-combinators)**: A presentation explaining how CSS combinator selectors work, allowing the construction of complex selectors based on relationships between elements.

 **[Understanding the CSS Property Value Syntax on Smashing Magazine](https://www.smashingmagazine.com/2016/05/understanding-the-css-property-value-syntax/)**: A deep dive into the syntax of CSS property values. The article explains how to interpret and use different types of values found in CSS, improving the understanding of the language's nuances.

 **[Attribute Selectors: Splicing HTML DNA with CSS](https://www.smashingmagazine.com/2018/10/attribute-selectors-splicing-html-dna-css/)**: A deep dive into the world of CSS attribute selectors, revealing their possibilities and usage examples.

 **[Styling External Links with Attribute Selectors](https://css-irl.info/styling-external-links-with-attribute-selectors/)**: A guide on styling external links using attribute selectors, enhancing the user interface.

 **[The Truth About CSS Selector Performance](https://css-tricks.com/the-truth-about-css-selector-performance/)**: An article on CSS-Tricks examining the performance of various CSS selectors and offering optimization recommendations.

### Specificity

🟢 **[What Is CSS Specificity? on Tuts+](https://webdesign.tutsplus.com/what-is-css-specificity--cms-34141t)**: A brief introduction to the concept of specificity in CSS, providing basic information on how styles are applied based on selector weight.

🟢 **[Understanding Specificity in CSS on matuzo.at](https://www.matuzo.at/blog/2022/specificity/)**: A deep understanding of the concept of specificity in CSS. The article details how style priority is determined and its impact on cascading CSS rules.

 **[Understanding CSS Specificity on Tuts+](https://webdesign.tutsplus.com/understanding-css-specificity--CRS-201051c)**: A detailed video explanation of selector specificity in CSS, illustrating how rules determine which styles will be applied to an element.

### Inheritance

🟢 **[CSS Inheritance, the Cascade, and Global Scope: Your New Old Worst Best Friends](https://www.smashingmagazine.com/2016/11/css-inheritance-cascade-global-scope-new-old-worst-best-friends/)**: This article on Smashing Magazine dives deep into the mechanisms of CSS inheritance and cascading, and their impact on global scope. Through thorough analysis, it shows how these concepts can be both your best friends and worst enemies in the development process.

**[Understanding CSS Inheritance: `inherit`, `initial`, `unset`, and `revert` Keywords](https://webdesign.tutsplus.com/understanding-css-inheritance-inherit-initial-unset-and-revert-keywords--cms-34233t)**: This article on Tuts+ explains the concepts of inheritance in CSS and introduces the keywords `inherit`, `initial`, `unset`, and `revert`. Knowing these keywords extends the ability to manage inheritance and allows for more precise style adjustments.

 **[More About Inheritance on SlideShare by inarocket](https://www.slideshare.net/inarocket/14-learn-css-fundamentals-inheritance)**: A presentation presenting the basic principles of inheritance in CSS, explaining how properties are passed from parent elements to child elements. This is crucial for understanding how to build effective and maintainable styles.

 **[CSS Inheritance Presentation on SlideShare by anuradhay_2004](https://www.slideshare.net/anuradhay_2004/css-inheritance)**: Another helpful presentation dedicated to inheritance in CSS. It details how various CSS properties behave when inherited and how this knowledge can be used to optimize your styles.

### Properties

🟢 **[Shorthand Properties in CSS on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties)**: An overview and examples of using shorthand properties in CSS, which help simplify and reduce the volume of code.

🟢 **[CSS Borders on DevDojo](https://devdojo.com/guide/css/borders)**: The basics of using borders in CSS, including various styles, thicknesses, and colors. Ideal for creating separators, element frames, and other decorative effects.

### Working with Text

 **[Learn CSS Typography: Fonts, Sizes, Spacing, and More on Tuts+](https://webdesign.tutsplus.com/start-here-learn-css-typography--CRS-200512c)**: An introductory video guide to typography in CSS, covering working with fonts, sizes, line heights, and other important aspects of text styling.

 **[Better CSS Drop Caps with `initial-letter`](https://webdesign.tutsplus.com/better-css-drop-caps-with-initial-letter--cms-26350t)**: Learn how to use the `initial-letter` property in CSS to create stylish large initial letters in text, adding elegance and emphasis to the beginning of paragraphs.

 **[Balancing Text Wrap in CSS on iShadeed](https://ishadeed.com/article/css-text-wrap-balance)**: Methods and techniques for balancing text wrap in CSS, contributing to a more pleasant visual perception of text blocks.

 **[How to Tame Line Height in CSS](https://css-tricks.com/how-to-tame-line-height-in-css/)**: A guide to controlling line height in CSS, which is crucial for creating ideal text content.

 **[The Hidden Power of `text-align`](https://ishadeed.com/article/the-hidden-power-text-align)**: Examining various aspects of the `text-align` property and its application beyond text alignment.

## Colors

🟢 **[Color Formats in CSS on JoshWComeau](https://www.joshwcomeau.com/css/color-formats/)**: A detailed overview of color formats in CSS, explaining how and when to use each of them for the best results in design.

 **[Nerd's Guide to Color on the Web on CSS-Tricks](https://css-tricks.com/nerds-guide-color-web/)**: An in-depth analysis of using color in web design, offering tips on choosing and combining colors to create a harmonious interface.

 **[Complete List of Color Keywords in CSS on W3.org](https://www.w3.org/wiki/CSS/Properties/color/keywords)**: The official list of keywords representing colors in CSS provided by W3C. This resource offers a full range of color identifiers that can be used to quickly style elements without memorizing color codes.

  **[CSS `::caret-color` on SamanthaMing](https://www.samanthaming.com/tidbits/31-css-caret-color/)**: A discussion on the `caret-color` property in CSS, which allows changing the cursor (caret) color in input fields, enhancing the user interface and adaptation to the site style.

### HEX

🟢 **[Transparency Values for HEXA on Gist by lopspower](https://gist.github.com/lopspower/03fb1cc0ac9f32ef38f4)**: A handy resource presenting transparency values in HEX format (HEXA), which adds two additional characters to the traditional HEX color code to indicate the level of transparency. This list covers a wide range of values from full transparency to full opacity, making it easy to select the right transparency level for colors in your CSS styles.

### RGB

🟢 **[The Power of RGBA in CSS on iShadeed](https://ishadeed.com/article/the-power-of-rgba)**: This article delves into the possibilities of using RGBA (Red, Green, Blue, Alpha) in CSS. It discusses how applying transparency through the alpha channel allows for more flexible and dynamic design solutions, including semi-transparent backgrounds, gradients, and shadows, improving user interaction with interface elements.

### HSL

 **[HSL Colors in CSS on Smashing Magazine](https://www.smashingmagazine.com/2021/07/hsl-colors-css/)**: An overview of using HSL in CSS, demonstrating how HSL simplifies working with color, providing a more flexible and accessible approach to styling.

### OKLCH

 **[OKLCH Color Spaces and Gamuts in CSS on Smashing Magazine](https://www.smashingmagazine.com/2023/08/oklch-color-spaces-gamuts-css/)**: This article provides a deep understanding of OKLCH color spaces and their use in CSS for achieving more accurate and versatile color representation on web pages. It discusses the advantages of OKLCH over traditional models like RGB and HSL, including improved color perception and a wider color gamut.

 **[OKLCH in CSS: Why We Moved from RGB and HSL on Evil Martians](https://evilmartians.com/chronicles/oklch-in-css-why-quit-rgb-hsl)**: An overview of the reasons for transitioning from using RGB and HSL to OKLCH in CSS. The article discusses how OKLCH provides more intuitive and perception-oriented color management, allowing designers and developers to achieve more accurate and consistent color solutions in web design.

 **[OK, OKLCH: A Color Picker Made to Help Think Perceptively on Evil Martians](https://evilmartians.com/chronicles/oklch-a-color-picker-made-to-help-think-perceptively)**: Introducing a tool for selecting colors based on OKLCH, created to help with color perception. This tool offers a unique approach to color selection, emphasizing color perception, making it useful for designers and developers aiming to create accessible and visually appealing content.

### Tools

 **[Color Tools and Resources for CSS on Smashing Magazine](https://www.smashingmagazine.com/2021/07/color-tools-resources/)**: A comprehensive list of tools and resources for working with colors in CSS. This article reviews various online tools, libraries, and guides that help with color selection, creating color schemes, and converting color values, making the design process more convenient and efficient.

 **[OKLCH Color Picker & Converter](https://oklch.com/#70,0.1,357,100)**: A tool for selecting and converting colors in the OKLCH format. It allows easy conversion of color values between different formats and selecting colors based on perception, which is especially useful when working with modern web technologies and design.

 **[Colord](https://colord.omgovich.ru/)**: A powerful color converter supporting many color schemes. Colord helps translate colors between different formats, such as HEX, RGB, HSL, OKLCH, and many others, facilitating the process of working with color in web development and design.

## Units of Measurement

🟢 **[Using Viewport Units in CSS on iShadeed](https://ishadeed.com/article/viewport-units)**: An explanation of the benefits of using viewport units in CSS to create designs perfectly adapted to the user's screen size. The article includes examples and best practices.

🟢 **[New Viewport Units in CSS on iShadeed](https://ishadeed.com/article/new-viewport-units)**: Introducing new viewport units proposed for CSS and their potential to improve the adaptability and flexibility of web design.

🟢 **[CSS Absolute Units on Smashing Magazine](https://www.smashingmagazine.com/2021/07/css-absolute-units/)**: All about absolute units of measurement in CSS, their features, and situations where their use is most appropriate for precise element sizing control.

## Fonts

🟢 **[A Comprehensive Guide to HTML Fonts and Web Fonts on Atatus](https://www.atatus.com/blog/a-comprehensive-guide-to-html-fonts-web-fonts/)**: A complete guide to using fonts in HTML and web fonts, covering the basics of working with fonts and integrating them into web design.

 **[CSS Fonts and Text Effects on SharkCoder](https://sharkcoder.com/typography/fonts)**: A tutorial on how to set fonts and format text using CSS, including creating impressive text effects.

  **[Best Practices for Fonts on web.dev](https://web.dev/articles/font-best-practices?hl=en)**: A set of recommendations for using fonts in web development, including tips on optimization and accessibility.

  **[Reduce Web Font Size on web.dev](https://web.dev/articles/reduce-webfont-size?hl=en)**: Strategies and practices for reducing web font sizes to speed up page loading and improve site performance.

   **[CSS Size-adjust for @font-face on web.dev](https://web.dev/articles/css-size-adjust?hl=en)**: An overview of the `size-adjust` property for `@font-face`, allowing size adjustment for improved readability and text consistency.

   **[Variable Fonts in Real Life on Evil Martians](https://evilmartians.com/chronicles/variable-fonts-in-real-life-how-to-use-and-love-them)**: A guide to using and the benefits of variable fonts in real projects, explaining how they can improve user experience and performance.


### Tools

 **[Search for Matching Web-Safe Fonts](https://web-safe-fonts.vercel.app/)**: A tool for finding web-safe fonts compatible with most browsers and devices.

**[What the Font](https://www.myfonts.com/WhatTheFont/)**: A service for identifying fonts from images, helping to find out the name of unknown fonts. In case of difficulties, it is suggested to consult the forum for expert help.

**[Identifont](http://www.identifont.com/)**: A tool for finding similar fonts if it is not possible to determine a specific font. The search is possible by image, popular fonts, and other characteristics.

**[Fount](https://fount.artequalswork.com/)**: A browser extension that allows users to identify fonts on any website. To use it, simply install the extension and activate it on the site of interest.

**[FontForge](https://fontforge.org/)**: An open-source font editor providing comprehensive tools for creating, editing, and converting fonts. FontForge supports creating fonts from scratch and importing characters from other formats.

**[FontBase](https://fontba.se/)**: A free font manager for Mac, Windows, and Linux, offering a convenient interface for viewing, managing, and quickly accessing installed fonts through a search and tagging system.

**[Tiny Helpers - Fonts](https://tiny-helpers.dev/fonts/)**: A collection of useful tools for working with fonts, covering various aspects of typography and simplifying tasks related to font selection, optimization, and integration into the web.

## Videos

**[How To Apply CSS Styles to HTML on Codecademy](https://www.codecademy.com/resources/videos/web-design/how-to-apply-css-styles-to-html)**: A video tutorial demonstrating the main ways to apply CSS styles to HTML, including inline styles, internal styles, and external style sheets. The lesson helps beginners understand the basics of linking HTML and CSS.

**[Learn CSS with Codecademy](https://www.codecademy.com/resources/videos/html-and-css/learn-css-with-codecademy)**: A video series dedicated to the basics of CSS. The videos cover a wide range of topics from an introduction to CSS to advanced styling techniques, offering viewers practical examples and tasks for reinforcing the material.

