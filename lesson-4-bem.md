# Lesson 4. Naming methodologies: BEM

**[Presentation](presentations/presentation-4-bem.pdf)**<br />
**[Manual](manuals/manual-4-bem.pdf)**<br /> 

**Part 1:** <br /> 
**[Group 1 video](https://drive.google.com/file/d/136k0cBVlbYtJDJ8D8-6Ej7Ha0-PZZs62/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/1dvqm-6OQsGcLAZksTcQr_Md-VNSutDJJ/view?usp=sharing)**<br />

<!-- **Part 2:** <br /> -->
<!-- **[Group 1 video]()**<br /> -->
<!-- **[Group 2 video]()**<br />  -->

# Homework

Take your existing HTML markup (homepage and blogpage). Using the BEM methodology, assign correct classes to blocks, elements, and modifiers.

1. Identify blocks.
  Find independent components in your interface (e.g., a product card, a button, a menu).

2. Identify elements.
  Find subordinate parts of blocks (e.g., the product card title, menu items, or a button icon).

3. Add modifiers.
  If certain blocks or elements have variations (e.g., an active button state or a highlighted card), add modifiers to represent these variations.

Use correct syntax.
  * Block: block.
  * Element: block__element.
  * Modifier: block--modifier 

## Criteria 

❤️ All independent components are defined as separate blocks. <br /> 
Each block is autonomous and does not depend on others. <br /> 

❤️ All subordinate parts are correctly defined as elements. <br /> 
All internal parts of a block are properly described using elements (block__element). <br /> 

❤️ BEM element not used outside of related block <br /> 

❤️ Modifiers correctly describe states or variations. <br /> 
Modifiers reflect states, sizes, types, or other variations of a block or element. <br /> 

❤️ Modifiers must not include: <br /> 
* Colors: Instead of `block--red`, use a more abstract name like `block--danger`.
* Numbers: Instead of `block--1`, use descriptive names like `block--first`.
* Tag names: Instead of `block--div`, use meaningful modifiers like `block--highlighted`.

❤️ Modifiers cannot be used as the only class on a tag. <br /> 
* Bad: `<div class="block--active"></div>`
* Good: `<div class="block block--active"></div>`

❤️ BEM syntax rules are followed: <br /> 
Correct format is used: `block, block__element, block--modifier`. <br /> 
No errors such as:
  * Nested elements (`block__element__subelement`).
  * Use of global classes (`active` instead of `block--active`).

❤️ Block, element, and modifier names must be meaningful. <br /> 
Each class should logically explain its purpose:
  * Bad: `block--style1`.
  * Good: `block--disabled`.

❤️ Classes are named correctly: <br /> 
* No transliteration in class names, attributes, etc.
* Only lowercase letters are used.
* If a class name consists of several words, use hyphens between the words: slider-block, etc.
* Do not use presentational classes that specify styles (fz-15, color-green, block-left).
* The class name should reflect the purpose (semantics) of the block, not its appearance.

# **🎨 BEM Demos & CodePen Examples**
These demos provide practical examples of various CSS methodologies, aiding in the understanding and application of structured and maintainable CSS in your projects. 

- [**BEM Example 1 – BroAcademy**](https://codepen.io/broacademy/pen/ZYzpRjq?editors=1100)  
- [**BEM Example 5 – BroAcademy**](https://codepen.io/broacademy/pen/yyBaEQq?editors=1100)  
  *Two similar examples showcasing how modifiers work in BEM. Demonstrates different states of a component using BEM naming conventions.*

- 🟢 [**BEM Example 3 – MattIn4D**](https://codepen.io/MattIn4D/pen/AYyxqO?editors=1000)  
  *An example of using modifiers in BEM. Shows how modifying a class can affect the appearance and behavior of a component.*

- [**BEM Example 4 – BroAcademy**](https://codepen.io/broacademy/pen/ByBLVGZ?editors=1000)  
  *A product card component structured with BEM. Demonstrates how to separate blocks, elements, and modifiers effectively.*

- [**BEM Example 6 – BroAcademy**](https://codepen.io/broacademy/pen/GgKjGPr?editors=1000)  
  *A form with multiple elements built using BEM. Highlights the proper structuring of form fields and their corresponding elements.*

- [**BEM Example 7 – Robertegna**](https://codepen.io/robertegna/pen/YqGRJp?editors=1000)  
  *Explains BEM methodology through a house analogy. A great conceptual example illustrating how blocks, elements, and modifiers work together.*

- 🟢 [**BEM Example 8 – Victorjeman**](https://codepen.io/victorjeman/pen/qNNzQY?editors=1000)  
  *Another product card example built with BEM. Demonstrates clean structuring and separation of styles for a reusable UI component.*

- [**BEM Example 9 – BroAcademy**](https://codepen.io/broacademy/pen/dPbpKrY?editors=1000)  
  *An example of navigation built using BEM methodology. Showcases how to structure menus and navigation links properly.*

<!-- - [**BEM Example 10 – Nikazawila**](https://codepen.io/nikazawila/pen/XJXowd?editors=1000)   -->

- [**BEM Example 12 – Ehkoo**](https://codepen.io/ehkoo/pen/KbmGEq?editors=1000)  
  *A comparison between BEM and Atomic CSS. Shows the structural differences between the two methodologies and their impact on CSS organization.*

- [**BEM Example 13 – Jeffharbers**](https://codepen.io/jeffharbers/pen/rLyjba?editors=1000)  
  *A product card with modifiers. Demonstrates how to adjust styles dynamically by applying BEM modifiers to elements.*

- [**BEM Example 14 – HQDrone**](https://codepen.io/hqdrone/pen/QWEWpQp?editors=1000)  
  *A mini website example structured using BEM. Focus on how classes are applied rather than the markup itself. Uses Yandex-style BEM naming with underscores `_` for modifiers instead of `--`.*

---

## **🎨 SMACSS Demos**

- [**SMACSS Example 1**](https://codepen.io/smacss-exemples/pen/WNrbzX)  
  *Demonstrates a dashboard layout following SMACSS principles, focusing on the categorization of styles for better modularity.*

- [**SMACSS Example 2 – Savemuse**](https://codepen.io/savemuse/pen/gWVpvd)  
  *Illustrates a user profile card designed with SMACSS methodology, showcasing the separation of base, layout, and module styles.*

---

## **🎨 OOCSS Demos**

- [**OOCSS Example 1 – Zach Harkey**](https://codepen.io/zachharkey/pen/AxOGpz)  
  *Features a media object pattern implemented using OOCSS, emphasizing the reuse of visual patterns and separation of structure from skin.*

- [**OOCSS Example 2 – Colin**](https://codepen.io/colin/pen/DGVOBQ?editors=1000)  
  *Presents a list item grid layout applying OOCSS principles, highlighting the flexibility and scalability of component-based design.*

---

## **🎨 Atomic CSS Demos**

- [**Atomic CSS Example 1 – Okmutjxd**](https://codepen.io/okmutjxd-the-reactor/pen/jOgzRzz)  
  *Showcases a button styled with Atomic CSS, demonstrating the use of single-purpose classes for rapid UI development.*

- [**Atomic CSS Example 2 – TonyLe**](https://codepen.io/tonyle-geocomply/pen/xxjELYQ)  
  *Illustrates a card component built using Atomic CSS methodology, focusing on the composition of utility classes for consistent styling.*

- [**Atomic CSS Example 3 – Michai**](https://codepen.io/michai/pen/LGmvJM)  
  *Demonstrates a responsive grid system implemented with Atomic CSS, showcasing the application of utility classes for layout management.*


# Additional Materials

## **📌 BEM & CSS Methodologies: Resources for Further Learning**

### **📖 Official BEM Documentation**
- [**BEM Naming Convention**](https://en.bem.info/methodology/naming-convention/) – Official guide explaining how to name blocks, elements, and modifiers in BEM methodology.
- [**BEM HTML Methodology**](https://en.bem.info/methodology/html/) – Best practices for writing clean and structured HTML using BEM.
- [**BEM Block Modification**](https://en.bem.info/methodology/block-modification/) – Detailed explanation of how to modify blocks and elements using BEM modifiers.
- [**History of BEM**](https://en.bem.info/methodology/history/) – An overview of how and why BEM was created by Yandex and its evolution over time.

---

### **📝 Articles & Guides**
- 🟢 [**BEM by Example – Sparkbox**](https://sparkbox.com/foundry/bem_by_example) – A practical guide with code examples on how to implement BEM effectively.
- 🟢 [**Understanding CSS Naming Conventions (BEM, OOCSS, SMACSS, and SUIT CSS) – Frontend Mentor**](https://www.frontendmentor.io/articles/understanding-css-naming-conventions-bem-oocss-smacss-and-suit-css-V6ZZUYs1xz) – Compares BEM with other CSS methodologies and explains when to use each.
- [**About HTML Semantics & Front-End Architecture – Nicolas Gallagher**](https://nicolasgallagher.com/about-html-semantics-front-end-architecture/) – Discusses best practices in HTML semantics, front-end architecture, and includes insights on using BEM effectively.
- [**MindBEMding – Getting Your Head Round BEM Syntax – CSS Wizardry**](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) – A deep dive into BEM syntax and philosophy, making it easier to understand how to apply BEM in real-world projects.
- [**Learning to Love BEM – Mono Company**](https://mono.company/frontend/learning-to-love-bem/) – A personal perspective on transitioning to BEM and how it helps developers structure CSS better.
- [**CSS: BEM or Atomic Design? – Medium**](https://medium.com/@ConorJonOReilly/css-bem-or-atomic-design-a023beca1a03) – Discusses the differences between BEM and Atomic Design, helping developers choose the right approach.

---

### **⚡ Cheat Sheets & Tools**
- 🟢 [**BEM Cheat Sheet**](https://bem-cheat-sheet.9elements.com/) – A quick reference guide for naming conventions and structuring BEM classes correctly.
- [**BEM Naming Tool**](https://getbem.com/naming/) – An interactive tool that helps generate proper BEM class names.
- [**Emmet BEM Filter Documentation**](https://docs.emmet.io/filters/bem/) – Explains how to use Emmet shortcuts to quickly generate BEM-compliant HTML structures.

---
