# Lesson 8. Bundlers and templating 

**[Presentation 1](presentations/presentation-8-bundlers.pdf)**<br />
**[Presentation 2](presentations/presentation-8-templating.pdf)**<br />
**[Manual](manuals/manual-8-bundlers.pdf)**<br /> 
<!-- **[Manual](manuals/manual-8-templating.pdf)**<br />  -->

**Part 1: Bundlers** <br /> 
**[Group 1 video](https://drive.google.com/file/d/13g9c_Y1nAfJNX3lQchftC__sRSakatnw/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/14EYym_Eg5LRRFxnx80nVRvoYIiwMafGz/view?usp=sharing)**<br />

**Part 2: Templating** <br />
**[Group 1 video](https://drive.google.com/file/d/13mKjLyg4L1_QlAwEC5E000fvellJZpUQ/view?usp=sharing)**<br />
**[Group 2 video](https://drive.google.com/file/d/1XcdMFg4ms5o1UeBWwBnT8S2LnnKThdG1/view?usp=sharing)**<br /> 

# Homework

**Part 1:Set Up Gulp Build**
1. Copy the necessary Gulp configuration files (`gulpfile.js`, `package.json`, etc.) to your project.
2. Organize your project files:
- Move all images to the `src/images/static` folder.
- Copy the styles from your existing CSS file and place them in `src/styles/style.scss`.

**Part 2: Create HTML Templates Using Nunjucks**
1. Set up the templates folder structure:
- `src/templates/` → Main folder for all `.njk` files.
- `src/templates/layouts/` → Base structure for pages (`base.njk`).
- `src/templates/pages/` → Separate folder for each page (`index.njk`, `about.njk`, etc.).
- `src/templates/partials/` → Components (e.g., header, footer, product cards).
- `src/templates/data.json` → Store dynamic data (e.g., product lists, user profiles).

2. Implement the Nunjucks templating system:
- Create a base template (`base.njk`) with `{% block %}` sections for content.
- Use `{% extends %}` to inherit the layout structure.
- Include reusable components (header, footer) with `{% include %}`.
- Work with variables and loops (`{% for %}`, `{% if %}`) to generate dynamic content.

## Criteria 

❤️ **Gulp is used as a build tool**  
   - The project is set up with **Gulp** for automation tasks.  

❤️ **Public and node_modules folders should not be in the GitHub repository**  
   - The `.gitignore` file is configured to exclude **automatically generated build files**.  

❤️ **The project builds correctly**  
   - After running `npm start` or `npm run dev`, the project should build **without critical errors**.  
   - The final files should be correctly placed in `public/` **without manual intervention**.  
   - The build process **should stop** if critical errors occur.  

❤️ **No errors (`error`) in the console during the build process**  
   - The console should not show **red error messages (`error`)**.  
   - All dependencies should be installed, and plugins should be correctly configured.  

❤️ **The project is structured using Nunjucks templates**  
   - **Layouts (`layouts/`)** contain the base structure (`base.njk`).  
   - **Partials (`partials/`)** store reusable components (header, footer, product cards, etc.).  
   - **Text content is moved to `data.json`** for better management of dynamic data.  

💛 **No warnings (`warning`) in the console during the build process**  
   - The console should not show **yellow warning messages (`warning`)**, such as **package incompatibilities or missing dependencies**.  
   - The code should follow best practices and be validated with linters (`stylelint`, `eslint`, `htmllint`).  

💛 **Loops, variables, and dynamic data are used in Nunjucks**  
   - **Variables are created** using `{% set %}` or fetched from `data.json`.  
   - **Loops (`{% for %}`)** are used to generate lists of elements (e.g., products, reviews).  
   - **Conditional statements (`{% if %}`)** are used to check for data presence or to display different blocks.  


# Additional Materials

**[Learn Build Tools (Codecademy)](https://www.codecademy.com/learn/learn-build-tools)**: A course on build tools in modern web development, including Webpack and other systems.

## **📌 Nunjucks Basics**
- **[Nunjucks Templating Language (Mozilla)](https://mozilla.github.io/nunjucks/)**  
  Official **Nunjucks** documentation by Mozilla. Covers key concepts such as template inheritance, blocks, includes, variables, and filters.  

- **[Killer Features of Nunjucks (CSS-Tricks)](https://css-tricks.com/killer-features-of-nunjucks/)**  
  A breakdown of **Nunjucks' powerful features**, including `{% block %}`, `{% include %}`, `{% extends %}`, filters, and macros.  

- **[Building a Static Site with Nunjucks (Smashing Magazine)](https://www.smashingmagazine.com/2018/03/static-site-with-nunjucks/)**  
  A practical guide on **using Gulp and Nunjucks** to create a static website.  

- **[Nunjucks Video Course (YouTube Playlist)](https://www.youtube.com/playlist?list=PL_wra5HCV9SlMXNY8PSbht5fbTmAtCccI)**  
  A series of **video tutorials** explaining Nunjucks step by step.  

- **[Getting Started with Nunjucks in Eleventy (Learn Eleventy From Scratch)](https://learneleventyfromscratch.com/lesson/3.html#getting-started-with-nunjucks)**  
  A guide on how **Nunjucks integrates with Eleventy**, a modern static site generator.  

---

## **⚡ Gulp & Build Automation**
- **[Gulp – A Toolkit to Automate Your Workflow (Medium)](https://medium.com/@niranjanky14/gulp-a-toolkit-to-automate-and-enhance-your-workflow-ec3aa0a101bf)**  
  Introduction to **Gulp**, its advantages, installation process, and essential tasks like compiling SCSS, processing Nunjucks, and live reloading.  

- **[Official Gulp Documentation](https://gulpjs.com/)**  
  The complete **Gulp.js** reference, including examples, API documentation, and setup guides.  

- **[Gulp for Beginners (CSS-Tricks)](https://css-tricks.com/gulp-for-beginners/)**  
  A beginner-friendly tutorial covering **the basics of Gulp**, how to set up `gulpfile.js`, and automate tasks.  

---

## **📦 Understanding npm & package.json**
- **[Node.js & npm (Official Site)](https://nodejs.org/en/learn/getting-started/an-introduction-to-the-npm-package-manager)**  
  A **beginner’s guide** to **npm**, package management, and working with dependencies.  

- **[The Basics of package.json (Nodesource)](https://nodesource.com/blog/the-basics-of-package-json)**  
  Explanation of **package.json structure**, including dependencies, scripts, and configurations.  

- **[What is package.json and How to Use It? (HeyNode)](https://heynode.com/tutorial/what-packagejson/)**  
  A detailed overview of **key fields in package.json**, such as `dependencies`, `devDependencies`, and `scripts`.  

- **[Difference Between Dependencies, devDependencies, and peerDependencies (GeeksForGeeks)](https://www.geeksforgeeks.org/difference-between-dependencies-devdependencies-and-peerdependencies/)**  
  How to manage **different types of dependencies** in npm projects.  

- **[Absolute Beginner’s Guide to Using npm (Nodesource)](https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm)**  
  A step-by-step introduction to **npm**, including installation, commands, and updating packages.  

- **[A Complete Beginner’s Guide to npm (CSS-Tricks)](https://css-tricks.com/a-complete-beginners-guide-to-npm/)**  
  An in-depth article on **npm features, package management, and best practices**.  

---

## **🔗 Additional Resources**
- **[Source Maps – What They Are and How They Work (Web.dev)](https://web.dev/articles/source-maps)**  
  A detailed guide on **source maps**, explaining how they help **debug minified code**.  

- **[Volta – A Node.js Version Manager](https://docs.volta.sh/guide/getting-started)**  
  A tool for **managing Node.js versions** and dependencies in projects.  

- **[Node.js vs. npm – What’s the Difference? (HostAdvice)](https://hostadvice.com/blog/web-hosting/node-js/node-js-vs-npm/)**  
  Understanding the difference between **Node.js and npm**, and why both are essential in web development.  
