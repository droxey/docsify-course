# docsify-course

🌟Everything required to add a Docsify site to Make School course repos.

## Prerequisites

**1. Install `docsify-cli`: `npm install -g docsify-cli`.**
1. _(Optional)_ Install `npm install -g tocsify` to generate directory-based sidebars.

## Update Your Repo - Step by Step

1. **Download the latest release** in the Releases tab.
1. **Unzip** the downloaded file.
1. **Move `_navbar.md`, `_sidebar.md`, `.nojekyll`, `index.html`, and the `Web` folder to your local course repository**.
1. **IMPORTANT**: **Update `_sidebar.md` with course materials that you want searchable.** 
   * See example [here](https://github.com/Make-School-Courses/BEW-2.5-Strongly-Typed-Ecosystems/blob/master/_sidebar.md).
   * _Need to link a lot of materials?_
      * Use my `tocsify` [npm package](https://github.com/droxey/tocsify) to check your repo directory for `.md` files and generate a list of links for your sidebar: `tocsify . --maxdepth=1 --file=_sidebar.md --headers=false`
1. **Open `index.html`** in a text editor.
    1. Scroll down and **replace `REPO_NAME`** on **lines `40` and `63`** with the **repo name for your course** (ex: `BEW-2.5-Strongly-Typed-Ecosystems`)
    1. Finally, **scroll up and update lines `6` through `11` in `index.html`** with **relevant descriptions** for your course.
1. **Test locally** by running `docsify serve .` in the root of the repo.
1. Add, commit, and **push your changes to `origin/master`**.

## Deployment

1. Navigate to the **Settings tab** of your course repository.
1. Scroll down to the **GitHub Pages settings**.
    1. Select `master` in the **Source drop-down**.
    1. **Submit to enable GitHub Pages** for your repo.
1. Click the **resulting `https://Make-School-Courses.github.io` link** to test the deployment.
