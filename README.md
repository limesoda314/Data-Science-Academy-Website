## Data Science Academy Website 

## Setup

### Clone the github into folder `dsa-website-repo`
`git clone git@github.com:limesoda314/Data-Science-Academy-Website.git dsa-website-repo`

### Install Node
- Follow the tutorial to download and install node: https://nodejs.org/en/download

### Install dependencies (packages)

First, move into the repository
`cd ./dsa-website-repo`

Now, install the packages
`npm install`

This will read `packages.json` and install all the required packages to run the website locally.

## Running

First, move into the repository, if you are not already in it.
`cd ./dsa-website-repo`

### Run development mode
`npm run dev`

### Create and run the build
`npm run build`

## Development

1. Check if issue already exists
  - Go into issues and check BOTH the closed and open issues to see if any exist. Open an old one if it already exists.

2. If no issue exists, create a new issue, and note down its number

3. Create a new branch
   - `git checkout -b <git-username>/issue<issue-number>`
   
4. After development, push branch
    - `git push --set-upstream origin <git-username>/issue<issue-number>`
    
WARNING: Please keep in mind that pushing to `main` branch will create a new Netlify production build and be visible to all our users on https://data-science-academy-ucr.netlify.app/. **DO NOT** push to `main` unless you've tested your own development branch and it works.
