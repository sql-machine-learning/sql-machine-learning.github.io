# Setting up your GitHub Pages site locally with Jekyll

1. Open Terminal in project root directory.
1. Check whether you have Ruby 2.1.0 or higher installed:
   ```
   $ ruby --version
   > ruby 2.X.X
   ```
1. Install Bundler:
   ```
   $ gem install bundler
   # Installs the Bundler gem
   ```
1. Install Jekyll and other [dependencies](https://pages.github.com/versions/) from the GitHub Pages gem:
   ```
   $ bundle install
   > Fetching gem metadata from https://rubygems.org/............
   > Fetching version metadata from https://rubygems.org/...
   > Fetching dependency metadata from https://rubygems.org/..
   > Resolving dependencies...
   ```
1. Run your Jekyll site locally:
   ```
   $ bundle exec jekyll serve
   > Configuration file: /Users/octocat/my-site/_config.yml
   >            Source: /Users/octocat/my-site
   >       Destination: /Users/octocat/my-site/_site
   > Incremental build: disabled. Enable with --incremental
   >      Generating...
   >                    done in 0.309 seconds.
   > Auto-regeneration: enabled for '/Users/octocat/my-site'
   > Configuration file: /Users/octocat/my-site/_config.yml
   >    Server address: http://127.0.0.1:4000/
   >  Server running... press ctrl-c to stop.
   ```
1. Preview your local Jekyll site in your web browser at http://localhost:4000.

