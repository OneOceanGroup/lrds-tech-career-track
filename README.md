# LRDS Tech Career Track
LRDS new Tech career track for all software engineers

# How to contribute
Live Demo at: https://oneoceangroup.github.io/lrds-tech-career-track/

## Setup

1. Install [Jekyll](https://jekyllrb.com/docs/installation/)
2. Fork the repo 
3. Open a WSL2 Command on Windows and navigate to the fork (usually `/mnt/c/.../lrds-tech-career-track`)
4. Run the Jekyll build with `bundle exec jekyll serve --force-polling --livereload`. This will bundle the static site, run a web server with live-reload enabled
5. Visit the site at http://127.0.0.1:4000/
   1. example of the first page done at: http://127.0.0.1:4000/sw/level0.html




## Contribute

1. Branch the main trunk
2. Do your changes
   1. ideally use a markdown editor to update each different levels (I’m using [Typora](https://typora.io/))
3. Push your branch and open a Pull-Request
4. When the PR is approved, update the `gh-pages` branch (until we found a way to make this automatically)
   1. `git checkout gh-pages`
   2. `git rebase master`
   3. `git push origin gh-pages`




## TO DO: 

- [x] Update the Readme with how to contribute
- [ ] Improve the GitHub Actions pipelines to automatically deploy to gh-pages
- [ ] Continue the importation of all SW levels
- [ ] Add a sidebar navigation
- [ ] Improve the Global Layout (maybe choose another Jekyll base theme) to reflect the LRDS/OO look
