# GatsbyJS

1. `npm install -g gatsby-cli`
2. `gatsby new <PROJECT_TITLE>`

# GIT

## Initialize and upload to github repository

1. `git init`
2. `git add origin <GITHUB_REPOSITORY>`
3. `git push origin master`

## Make a new branch

1. `git branch <NAME_OF_BRANCH>`
2. `git checkout <NAME_OF_BRANCH>`
3. `git merge <NAME_OF_BRANCH>`

Useful commands:

- `git log --oneline`
  See the commit status
- `git branch -a`
  See all branches and which we are using at the moment
  - `git branch -d <NAME_OF_BRANCH>`
    Delete an merged branch
  - `git branch -D <NAME_OF_BRANCH>`
    Delete an unmerged branch
    - `git checkout -b <NAME_OF_BRANCH>`

# Install SASS

1. `npm install -save node-sass gatsby-plugin-sass`
2. Add `plugins: [`gatsby-plugin-sass`],` to `gatsby-config.js`
