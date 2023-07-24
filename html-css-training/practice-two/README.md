# HTML-CSS-PRACTICE_TWO 

## Target: 

- Apply knowledge to responsive practice one design
- Used media queries for popular screen size

## Design on figma: 
[Figma](https://www.figma.com/file/6QbJ3zCbwFEIqDrHuYegS1/NinjaMail-(Community)-Thao's-practice?node-id=1%3A30&mode=dev)


## Information: 
- Time line: 13/07/2023 -> 20/07/2023
- Editor: Visual Studio Code

- Support cross browser: 
  - Chrome (114.0.5735.199)
  - Edge (114.0.1823.79)
  - Firefox (114.0.2)

- Screens ([refer here](https://getbootstrap.com/docs/5.0/layout/breakpoints/))
  - XX-Large devices (larger desktops, 1400px and down)
  - X-Large devices (large desktops, 1200px and down)
  - Large devices (desktops, 992px and down)
  - Medium devices (tablets, 768px and down)
  - Small devices (landscape phones, 576px and down)
  - Portrait tablets and large phones (Small devices, 320px and down) 

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
- cd html-css-training/practice-two 
- pnpm install
- pnpm run dev
- For components page, please run pnpm run components
- Open http://localhost:1234 to see the local website.

## Folder structure 
practice-two
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
        |-- abstracts
            |-- index.css
            |-- variables.css
        |-- bases
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
        |-- index.css
    |-- index.html
|-- .editorconfig.js
|-- .gitignore
|-- .posthtmlrc
|-- package.json
|-- pnpm-lock.yaml
|-- README.md


