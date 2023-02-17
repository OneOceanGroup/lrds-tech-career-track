# OneOcean Engineering Career Path
[Confluence page](https://oneocean.atlassian.net/wiki/spaces/GEOD/pages/11097604185/Tech+Career+path+v2)
[Trello Board](https://oneocean.atlassian.net/jira/core/projects/DEVCULT/board)

# How to contribute
Live Demo [here](https://oneoceangroup.github.io/lrds-tech-career-track/)


## Setup

1. Install [Jekyll](https://jekyllrb.com/docs/installation/)
2. Fork the repo 
3. Open a WSL2 Command on Windows and navigate to the fork (usually `/mnt/c/.../lrds-tech-career-track`)
4. Run the Jekyll build with `bundle exec jekyll serve --force-polling --livereload`. This will bundle the static site, run a web server with live-reload enabled
5. Visit the site at http://127.0.0.1:4000/
   1. example of the first page done at: http://127.0.0.1:4000/sw/level0.html

## Contribute

1. Clone the repo
2. Branch the main trunk
3. Do your changes
   1. ideally use a markdown editor to update each different levels (ex. [Typora](https://typora.io/))
4. Push your branch and open a Pull-Request
5. When the PR is approved and merged, changes will be automatically push to the Live Demo [here](https://oneoceangroup.github.io/lrds-tech-career-track/) 

## Theme
Based on a fork from the [Zendesk Garden Jekyll Theme](https://zendesk.github.io/jekyll-theme-zendesk-garden/getting_started.html)

## TO DO: 

- [x] Update the Readme with how to contribute
- [x] Improve the GitHub Actions pipelines to automatically deploy to gh-pages
- [x] Continue the importation of all SW levels
- [x] Add a sidebar navigation
- [x] Improve the Global Layout (maybe choose another Jekyll base theme) to reflect the LRDS/OO look
- [ ] Review each Craft and Responsibilities
