# Contributing Guidelines

We love improvements to our tools! EDGI has general [guidelines for contributing][edgi-contributing] and a [code of conduct][edgi-conduct] for all of our organizational repos.

## Here are some notes specific to this project:
### Issues
* Ideally, make an issue to describe what's being fixed/improved/added before you do any work + tag relevant people. This should help foster good design & scoping such that the right work gets done. Should also build understanding across the team of what work is being done.
* Comment on an issue or self-assign to claim it if you're working on something, and ideally update as you go (or even better, start a draft pull request)
* It's ok to stop working on an issue if you don't have capacity, just make sure to comment & unassign yourself so others know 

### Working
* See this explanation of the basic steps for working on a change in Github: https://guides.github.com/introduction/flow/
* Always work in a branch and make a pull request to merge to master
* Keep your branches/pull requests focused on just one issue at a time so they can be reviewed/merged efficiently and straightforwardly. E.g. if you are adding a new functionality/code block and also need to add text context to several other parts of a notebook, do these separate tasks in separate branches from master and make them separate pull requests to master.
* Push your branch to github early in the process and start a draft PR tagged with the relevant issue, but use the "Draft" feature or otherwise label the PR as "Draft" until it is ready for review

### Review & merge
* Tag all relevant people in the PR when ready for review (and if it's important or urgent consider also posting to Slack)
* One approving review is sufficient to merge in most cases (at your discretion)
* If nobody comments in 3 days, it's ok to merge your own review

### Specific practices for Jupyter notebooks
* Before committing a Jupyter notebook, clear outputs from cells (in Jupyter: Cell > All Output > Clear)

<!-- Links -->
[edgi-conduct]: https://github.com/edgi-govdata-archiving/overview/blob/master/CONDUCT.md
[edgi-contributing]: https://github.com/edgi-govdata-archiving/overview/blob/master/CONTRIBUTING.md