# Welcome!

## Advantages of Jekyll
- Static site means no database to hack!
- Fully customisable with layout templates

## Instructions
- (setup ruby environment if necessary https://jekyllrb.com/docs/installation/)
- Create a new sites folder if necessary
- Run $ gem install jekyll bundler
- Run $ jekyll new [sitename]
- cd to new folder
- Run $ bundle exec jekyll serve

Site will now be viewable at http://localhost:4000 or http://127.0.0.1:4000/ with default jekyll setup (yay!)

You can copy the 'site' directory to a github repo to host it :)

## Changing the default layout
By default, Jekyll will install the default theme Minima. You can download the source files here to easily include them in your Jekyll site and override them. https://github.com/jekyll/minima

- Copy over the following folders:
  - includes
  - layouts
  - sass
  - assets
- Comment out line 14 in the gemfile which includes Minima
- Comment out line 29 in config.yml which says theme: minima
- Add "jekyll-seo-tag" to the config.yml file under plugins
- Add "jekyll-seo-tag" to the gemfile
- Run $ bundle update
- Make a change to a template file to test for changes
- Run $ bundle exec jekyll serve
- Changes will appear!

## Publishing on GitHub Pages
GitHub pages requires the github-pages plugin to be added both to the config.yml file, and the gemfile. Remember to run "bundle update" after making changes to these files. After publishing to GitHub you may get import errors with the sass setup - I had to copy over the breakpoint stylesheets so GitHub can compile the sass correctly, which can be downloaded from their repo: https://github.com/at-import/breakpoint
