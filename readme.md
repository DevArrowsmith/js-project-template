# JS Project Template 🛠

## Introduction

I created this template for the quick commencement of web projects using <span style="color:crimson">HTML</span>, <span style="color:cornflowerblue">CSS</span> & <span style="color:goldenrod">JavaScript</span> with <span style="color:mediumspringgreen">Jest</span> for test-driven development.



---

## Setup

### 1. Installation

The simplest way to use [this repo](https://github.com/DevArrowsmith/js-project-boilerplate) is to [clone it as a template using this guide](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template).

### 2. Remove obsolete content.
1. Delete this readme. Alternatively add it to `.gitignore`.
2. If you won't be using JavaScript in your project delete the `src` directory and uninstall Jest by running the command `npm uninstall jest` in a terminal from root.

### 2. Update `index.html` & `index.css`
1. Change your project's `<title>`.
2. Delete the boilerplate content of the `<body>`.
3. Delete the contents of `index.css` to remove styling.

### 3. Start your project.
Here are some tips:
- Start by writing all of your semantic HTML. **All of it.**
- Next apply styling.
    - Plan your styling before you start it. As a general rule the more decisions you make in advance the fewer stylistic incompatibilities you'll find later on, and the less incongruous your site will look.
    - Take a [mobile-first approach](https://internetingishard.netlify.app/html-and-css/responsive-design/index.html). 
    - Consider starting by [choosing a font set](https://fonts.google.com/) and storing important variables to `root:` ([see this guide](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)).
- When you're ready to add some JavaScript **use test-driven development**. Start with a [user story](https://www.mountaingoatsoftware.com/agile/user-stories) then follow the [red-green-refactor cycle](https://www.codecademy.com/articles/tdd-red-green-refactor).


---

## Next Steps

I'd like to expand this repo. Here are some ideas:

- Include several template HTML files with more content, such as headers, footers, navbars, forms, for quick creation of comprehensive websites.
- Include CSS and JS files for the above, with test suites.
- These can be stored in this repo, or as distinct projects. I think I'd prefer to store them here then trim this template down when it's used.
- Think/talk about useful node packages.
- Think about style guides.