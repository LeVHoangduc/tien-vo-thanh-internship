# HTML-CSS-PRACTICE_ONE 
Introduce dashboard app landing page

## Target: 
- Understand HTML/CSS properties and use them correctly
- Slice from Sketch to HTML/CSS
- Understand the concepts of Flex


## Design on figma: 
[Figma](https://www.figma.com/file/6QbJ3zCbwFEIqDrHuYegS1/NinjaMail-(Community)-Thao's-practice?node-id=1%3A30&mode=dev)


## Information: 
- Time line: 21/06/2023 -> 07/05/2023
- Editor: Visual Studio Code
- Supported browser: Chrome lasted


## Project convention: 
### Branch name format
`<prefix>/short-desc
`

- ex: feat/header-section

- ex: fix/header-section

### Commit format: 

`<type>[optional scope]: <description>
`

- ex: feat: allow provided config object to extend other configs
- ex: fix: prevent racing of requests

### PR format:

 `Title: <prefix>/short-desc`

- ex: Feat/header-section

- ex: Fix/header-section

### Prerequisites: Nodejs, pnpm
### Guide:

`Deployment`

1. get keys vercel token from my account
2. Install the [Vercel CLI](https://vercel.com/cli)
`npm i -g vercel`
- vercel login (login with your account)
- vercel link (create a new Vercel project)
3. add keys to project.json
4. add VERCEL_TOKEN, VERCEL_ORG_ID, and VERCEL_PROJECT_ID to GitHub 
5. Create .github/workflows [guides](https://vercel.com/guides/how-can-i-use-github-actions-with-vercel#configuring-github-actions-for-vercel)
6. [Configuring Projects with vercel.json](https://vercel.com/docs/concepts/projects/project-configuration#)
7. Enable GitHub Actions and Deploy

`Run app`
- git clone https://github.com/thanhnguyen-agilityio/tien-vo-thanh-internship.git
- cd html-css-training/practice-one 
- pnpm install
- pnpm run dev
- For components page, please run pnpm run components
- Open http://localhost:1234 to see the local website.

## Folder structure 
practice-one
~~~
|-- src
    |-- assets
        |-- fonts
            |-- ...
        |-- images
            |-- ...
    |-- partials
        |-- components
            |-- ...
        |-- ...
    |-- styles
        |-- abtracts
            |-- index.css
            |-- variables.css
        |-- base
            |-- index.css
            |-- reset.css
            |-- typography.css
        |-- common
            |-- index.css
        |-- components
            |-- index.css
        |-- layouts
            |-- footer.css
            |-- header.css
            |-- index.css
        |-- sections
            |-- index.css
            |-- ...
    |-- index.html
    |-- index.css
|-- .editorconfig.js
|-- .gitignore
|-- .posthtmlrc
|-- package.json
|-- pnpm-lock.yaml
|-- README.md


