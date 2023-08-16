# Lab website
This is the public repository for the Disturbance Ecology and Decomposition (DEAD) lab's website at Cary Institute of Ecosystem Studies. The link to the website is in the repo description. The website itself was built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs).

## Updating information
Editing the website is fairly straightforward. At a basic level, whenever a commit is pushed to the `main` branch, there are underlying GitHub Actions that are triggered to run in order to render the website, which itself comes from the `gh-pages` branch. You can check the status of each build in the "Actions" tab at the top of the repository.

There is extensive documentation from the template itself for how to edit all aspects of the website, which can be found at the link above. The repo template itself can be found [here](https://github.com/greenelab/lab-website-template). 

Below are some quick instructions for easy updating.

### Lab member pages
To update your own information or to add yourself to the team, create a new `.md` file for yourself in the `_members` folder using an existing member as an example. Your role can be any of those listed in `team/index.md` (but we can always add more!). Please also add a picture for yourself in the `images/team/` folder, and provide the relative link in your `.md` file.

