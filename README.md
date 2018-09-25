# Taiga

A simple and streamlined static site generator.

> ⚠ Taiga is an early work in progress and is not available yet. The details below are preliminary.

## Features

- Write your content in Markdown and easily organize it with folders
- Build themes with Handlebars, Sass, and the latest JS
- Optimize all of your assets
- Preview your site in any browser, on any device
- Refresh previewing browsers when you make changes
- Generate favicons, SEO tags, and structured data
- **All with zero configuration**

## Getting Started from Scratch

1. Install [Node.js](https://nodejs.org).
2. Install the Taiga command line interface.
```
npm install -g taiga
```
3. Create a new project.
```
taiga create my-website
```
4. Enter the directory where your project was created.
```
cd my-website
```
5. Start up a development environment.
```
taiga develop
```

## Commands

### `taiga create <name> [theme]`
Create a new website.

- **name** -  The name of your website & project directory.
- **theme** - Start with a different theme hosted on GitHub, Bitbucket, or Gitlab.

### `taiga develop`
Start a development server that renders your project and makes a live browser preview available.

### `taiga build`
Render production files for your project without starting a development server.
