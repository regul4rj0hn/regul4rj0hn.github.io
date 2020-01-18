# Table of Contents
- [Table of Contents](#table-of-contents)
- [Description](#description)
- [Getting started](#getting-started)
- [Publish to GitHub Pages](#publish-to-github-pages)

# Description

Proof of concept project for creating a static resume page using Blazor WebAssembly hosted on GitHub Pages.

# Getting started

- Install the [.NET Core 3.1 SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1).
- Clone this repository

  `git clone https://github.com/regul4rj0hn/resume.git`
- Change directory to the project folder

  `cd resume`
- Run the project

  `dotnet run`

# Publish to GitHub Pages

- Publish the release version using the dotnet CLI

  `dotnet publish -c "Release"`
- Remove the previous contents of the docs folder

  `rm -rf docs/*`
- Copy the publish output into the docs folder

  `cp -r bin/Release/netstandard2.1/publish/resume/dist/* docs/`

- Add a .nojekyll file so that GH Pages doesn't ignore the _framework folder

  `touch docs/.nojekyll`
- Commit and push the changes