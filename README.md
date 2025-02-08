
<img width="1163" alt="Screenshot 2025-02-08 at 23 51 28" src="https://github.com/user-attachments/assets/d1aaa78e-e93c-4708-bf61-26b57b276686" /><img width="1206" alt="Screenshot 2025-02-08 at 23 51 48" src="https://github.com/user-attachments/assets/bb6af9af-7deb-479f-9e7a-1df1a6a985e2" /><img width="1170" alt="Screenshot 2025-02-08 at 23 52 02" src="https://github.com/user-attachments/assets/a0edbced-62da-4570-b90c-3eb842878012" /><img width="1191" alt="Screenshot 2025-02-08 at 23 52 19" src="https://github.com/user-attachments/assets/94b117d1-cf8b-4c80-b33d-05b9d74f725a" /><img width="1162" alt="Screenshot 2025-02-08 at 23 52 34" src="https://github.com/user-attachments/assets/0a21250d-ee71-49bf-98ad-5e7dd63a256c" />

## Backroads App

The Backroads App is a travel and tour booking landing page application built with React. It provides users with an intuitive interface to explore and book various travel packages. The project is divided into two main versions:

- **backroads-js-version**: A working project using HTML, CSS, and JavaScript.
- **backroads-react-version**: A fully functional React application.
  
**Online Live:** https://backroads-arnob.netlify.app/

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
