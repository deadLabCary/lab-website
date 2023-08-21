Visit **[deadlabcary.github.io/lab-website](https://deadlabcary.github.io/lab-website)** 🚀

# Lab website
This is the public repository for the Disturbance Ecology and Decomposition (DEAD) lab's website at Cary Institute of Ecosystem Studies. The link to the website is in the repo description. The website itself was built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs).

## Updating information
Editing the website is fairly straightforward. At a basic level, whenever a commit is pushed to the `main` branch, there are underlying GitHub Actions that are triggered to run in order to render the website, which itself comes from the `gh-pages` branch. You can check the status of each build in the "Actions" tab at the top of the repository.

There is extensive documentation from the template itself for how to edit all aspects of the website, which can be found at the link above. The repo template itself can be found [here](https://github.com/greenelab/lab-website-template). 

Below are some quick instructions for easy updating.

### Lab member pages (Team)
To update your own information or to add yourself to the team, create a new `.md` file for yourself in the `_members` folder using an existing member as an example. Your role can be any of those listed in `team/index.md` (but we can always add more!). Please also add a picture for yourself in the `images/team/` folder, and provide the relative link in your `.md` file.

### Publications
Updating the publications list is super easy thanks to a bot that the template has. At a minimum, all you need is the DOI of the publication, and you can add the paper to `_data/sources.yaml`. If you want to add more information like pictures or buttons to appear, then you can do that as well following the format described in the template documentation [here](https://greene-lab.gitbook.io/lab-website-template-docs/basics/citations#examples).
- If you want to change the "Highlighted" publication, navigate to `/publications/index.md` and add the title of the desired paper in the `lookup= ` section.
