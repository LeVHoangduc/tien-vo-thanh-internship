# HTML-CSS-PRACTICE_ONE #
Introduce dashboard app landing page

## Target: ##
- Understand HTML/CSS properties and use them correctly
- Slice from Sketch to HTML/CSS
- Understand the concepts of Flex


## Design on figma: ##
[Figma](https://www.figma.com/file/6QbJ3zCbwFEIqDrHuYegS1/NinjaMail-(Community)-Thao's-practice?node-id=1%3A30&mode=dev)


## Information: ##
- Time line: 21/06/2023 -> 07/05/2023
- Editor: Visual Studio Code
- Supported browser: Chrome lasted


## Project convention: ##
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

- Prerequisites: Nodejs, pnpm
### Guide:
- cd vô folder project
- install package: pnpm install
- run app: pnpm run dev
- run component page: pnpm run components

## Folder structure ##
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


