## Backroads App

The Backroads App is a travel and tour booking application built with React. It provides users with an intuitive interface to explore and book various travel packages. The project is divided into two main versions:

- **backroads-js-version**: A working project using HTML, CSS, and JavaScript.
- **backroads-react-version**: A fully functional React application.
  **Online Live:**

### Features

- Browse and book travel packages
- Responsive design for seamless experience across devices
- Integration with third-party services for booking and payments
- User authentication and profile management

## Getting Started

To get started with the React version of the Backroads App:

1. Navigate to the project folder.
2. Install the dependencies:

```sh
   npm install
```

3. Start the development server:

```sh
npm start
```

4. For backroads-html file as javascript version, go to that folder, run:

```sh
open index.html
```

## Continuous Deployment

- fix warnings (About Section)

- netlify account
- github account
- basic git commands :

  - remove existing git repo
    - Mac : rm -rf .git
    - Windows : rmdir -Force -Recurse .git
    - Windows : rd /s /q .git
  - setup new repo
    - git init
      create an empty git repository
    - git add
      adds new or changed files in your working directory
      to the Git staging area
    - git add .
      adds entire project
      apart from files/directories specified in .gitignore
    - git commit -m "first commit"
      A shortcut command that immediately creates a commit
      with a passed commit message.
    - push to github
      git remote add origin git@github.com:your-profile/repo-name.git
      git branch -M main
      git push -u origin main

## Warnings "Gotcha"

- Netlify treats warnings as errors
