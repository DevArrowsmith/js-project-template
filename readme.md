# JS Project Boilerplate 🛠

## Introduction

I created this repo for the quick commencement of web projects using <span style="color:crimson">HTML</span>, <span style="color:cornflowerblue">CSS</span> & <span style="color:goldenrod">JavaScript</span> with <span style="color:mediumspringgreen">Jest</span> for test-driven development..

---

## Setup

### 1. Installation

1. [Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this [repo](https://github.com/DevArrowsmith/js-project-boilerplate).
2. In the terminal, in the root of this project, run `npm i` to install node modules including [jest](https://jestjs.io/).

### 2. Commit to GitHub
1. **<span style="color:orange">Delete this readme before you make your first commit!<span>** Alternatively add it to `.gitignore`.
2. Create a new GitHub repo for your new project.
3. Change the origin of this repo to the new GitHub repo. To do this, in the terminal run the following commands from this project's root:
    ```
    git remote rm origin
    git remote add origin [link to the new repo]
    git config main.remote origin
    git config main.merge refs/heads/main
    ```
4. Add, commit and post.
    ```
    git add .
    git commit -m "Initialised project using js-project-boilerplate (https://github.com/DevArrowsmith/js-project-boilerplate)"
    git push
    ```

### 2. Update `index.html`
1. Change your project's `<title>`.
2. Replace the boilerplate content of the `<body>`.
3. Consider choosing an alternative [font set](https://fonts.google.com/).

### 3. Delete content you won't use.
- If you don't plan to use javascript you won't need the `src` and `test` directories. 
- You can also uninstall jest. Run this command from the project's root:
    ```
    npm uninstall jest
    ```


### 4. Start your project.
Here are some tips:
- Start by writing all of your semantic HTML.
- Next apply styling. 
    - Take a [mobile-first approach](https://internetingishard.netlify.app/html-and-css/responsive-design/index.html). 
    - Consider starting by storing important variables to `root:` ([see this guide](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)).
- When you're ready to add some JavaScript **use test-driven development**. Start with a [user story](https://www.mountaingoatsoftware.com/agile/user-stories) then follow the [red-green-refactor cycle](https://www.codecademy.com/articles/tdd-red-green-refactor).


---

## Next Steps

I'd like to expand this repo. Here are some ideas:

- Include a/several template HTML files with more content, such as headers, footers, navbars.
- Include CSS and JS files for the above, with test suites.
- These can be stored in this repo, or as distinct projects.
- Think/talk about useful node packages.
- Think about style guides.