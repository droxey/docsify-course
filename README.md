# docsify-course

🌟Everything required to add a Docsify site to Make School course repos.

## Step by Step

1. Install `docsify-cli`: `npm install -g docsify-cli`
1. Download the latest release in the Releases tab.
1. Unzip the downloaded file.
1. Move `_navbar.md`, `_sidebar.md`, `.nojekyll`, `index.html`, and the `Web` folder to your local repository.
1. Update `_sidebar.md` with course materials that you want searchable. See example [here](https://github.com/Make-School-Courses/BEW-2.5-Strongly-Typed-Ecosystems/blob/master/_sidebar.md).
  * Need to link a lot of materials? You can use my `tocsify` [npm package](https://github.com/droxey/tocsify) to check your repo directory for `.md` files and generate a list of links for your sidebar: 
    * Install `npm install -g tocsify`
    * Run in root of repo: `tocsify . --maxdepth=1 --file=_sidebar.md --headers=false`
1. Open `index.html` in a text editor.
1. Update lines `6` through 11 `index.html` with relevant descriptions for your course.
1. Replace `REPO_NAME` on lines `40` and `63` with the repo name for your course (ex: `BEW-2.5-Strongly-Typed-Ecosystems`)
1. Add, commit, and push your changes.
1. Navigate to the Settings tab of your course repository.
1. Scroll down to the GitHub Pages settings, select `master` in the drop-down, and submit to enable the GitHub pages site for your repo.
1. Click the resulting link to test.
