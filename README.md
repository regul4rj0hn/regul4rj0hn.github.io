# Table of Contents
- [Table of Contents](#table-of-contents)
- [Description](#description)
- [Getting started](#getting-started)
- [Folder structure](#folder-structure)
- [Publish to GitHub Pages](#publish-to-github-pages)

# Description

Proof of concept of simple static SPA site to host my (always out-of-date) resume.
- Uses latest Blazor WebAssembly.
- Hosted by GitHub Pages.
- Builds automatically on push with GitHub Actions.
- Custom domain by Google Domains.

# Getting started

- Install the [.NET Core 3.1 SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1).
- Clone this repository

  `git clone https://github.com/regul4rj0hn/regul4rj0hn.github.io.git`
- Change directory to the project folder

  `cd resume`
- Run the project

  `dotnet run`

# Folder structure
```
.
+-- .github
|  +-- GitHub Action for automatic deployment
+-- src
|  +-- source code for the Blazor app
+-- .gitignore
+-- LICENSE
+-- README.md
```

# Publish to GitHub Pages

- The project is automatically published to GitHub Pages on the gh-pages branch by GitHub Actions whenever there's a commit to master.
