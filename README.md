# 🌟 docsify-course

Everything required to add a Docsify site to ACS course repos.

<!-- omit in toc -->
## Table of Contents

1. [Features](#features)
1. [Prerequisites](#prerequisites)
1. [Installation](#installation)
1. [Deployment](#deployment)
1. [Additional Resources](#additional-resources)

## Features

Includes the following features built in:

* Websites available offline.
* Ability to search and display any `.md` file in your repo linked in `_sidebar.md`.
* Syntax highlighting for multiple programming languages
* Emojis in the following format `:100:`.
* Added functionality: Copy to Clipboard function, flexible alerting.

## Prerequisites

1. **Install `docsify-cli`: `npm install -g docsify-cli`.**
1. _(Optional)_ Install `npm install -g tocsify` to generate directory-based sidebars.

## Installation

1. **Download the latest release** in the Releases tab.
1. **Unzip** the downloaded file.
1. **Move `_navbar.md`, `_sidebar.md`, `.nojekyll`, `index.html`, and the `Web` folder to your local course repository**.
1. **IMPORTANT**: **Update `_sidebar.md` with course materials that you want searchable.**m
1. **Open `index.html`** in a text editor.
    1. Scroll down and **replace `REPO_NAME`** on **lines `24-27` and `43`** with the **repo name for your course** (ex: `BEW-2.5-Strongly-Typed-Ecosystems`)
    1. Finally, **update lines `6` through `11` and `41`** with **relevant information** for your course.
1. use `<!-- tabs:start -->` and `<!-- tabs:end -->` to tabulate sections of your syllabus.
1. **Test locally** by running `docsify serve .` in the root of the repo.
1. Add, commit, and **push your changes to `origin/master`**.

## Deployment

1. Navigate to the **Settings tab** of your course repository.
1. Scroll down to the **GitHub Pages settings**.
    1. Select `master` in the **Source drop-down**.
    1. **Submit to enable GitHub Pages** for your repo.
1. Click the **resulting `https://tech-at-du.github.io` link** to test the deployment.

## Additional Resources

- [Docsify Documentation](https://docsify.js.org)
