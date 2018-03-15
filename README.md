# Setup

1. Make sure Ruby is installed.
2. Make sure Bundler is installed: `gem install bundler`.
3. Install the project dependencies: `bundle install`.

# Running docs locally

- Using middleman: `bundle exec middleman server`.
- Using Vagrant: `vagrant up`.

The docs will be up at http://localhost:4567.

# Deploying to Github

1. Commit and push all your changes.
2. Deploy: `./deploy.sh`.

# Upgrading Slate

1. Make sure you're on the main branch and everything commited and pushed.
2. Add the upstream remote if it doesn't already exist: `git add remote upstream git@github.com:lord/slate.git`.
3. Fetch and rebase upstream: `git fetch upstream && git rebase upstream/master`
