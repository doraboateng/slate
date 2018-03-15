# Setup

- Make sure Ruby is installed.
- Make sure Bundler is installed: `gem install bundler`.
- Install the project dependencies: `bundle install --path ./vendor/bundle`.

# Running locally

- Using middleman: `bundle exec middleman server`.
- Using Vagrant: `vagrant up`.

The docs will be up at http://localhost:4567.

# Deploying

1. Commit and push all your changes.
2. Run `./deploy.sh`.

# Upgrading Slate

1. Make sure you're on the main branch, and everything is committed and pushed.
2. Add the upstream remote if it doesn't already exist: `git remote add upstream git@github.com:lord/slate.git`.
3. Rebase the upstream branch into our main one: `git fetch upstream && git rebase upstream/master`.
