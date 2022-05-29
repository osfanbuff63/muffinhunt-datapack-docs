# Contributing

Contributions are always welcome! You can fork this repo and get started using the GitHub UI, but here's how to do it locally. You will need [Git](https://git-scm.com/downloads), [Ruby](https://www.ruby-lang.org/en/), and RubyGems installed (this should be installed with Ruby, at least on Windows devices).

## Setting up

1. Clone this repo (`git clone https://github.com/your-username/muffinhunt-datapack-docs.git`) (this is assuming you forked the repo)
2. Open the directory that you cloned the repository to in a terminal window (if you already have one open, `cd` over)
3. Run `gem install bundler`. This will install bundler, which manages Ruby dependencies.
4. Run `bundle install`. This will take the gems in our `Gemfile` and install them locally.

You can now make changes to this repo as you like! To test out your changes:

## Testing

1. If you made any changes to `Gemfile` or `Gemfile.lock`, run `bundle install`.
2. Run `bundle exec jekyll serve`. This builds the site using Jekyll.
3. Assuming that succeeded, in your browser of choice, navigate to `http://localhost:4000`. You should see the site all deployed!

Now, we'll create a pull request and commit our changes. This is assuming you have the [GitHub CLI](https://cli.github.com/) installed (which is highly recommended), but you can create a pull request in your browser as well.

## Commiting and creating Pull Requests

1. Run `git checkout -b your-branch-name`. This will create a new branch for your changes. Replace `your-branch-name` with any name for the branch. This is recommended, but not needed especially if you are only making one change.
2. Then run `git push --set-upstream` to publish your branch.
3. Run `git add .`. This adds all files you changed for commiting.
4. Run `git commit -m "Your message here"` (replace "Your message here" with your message **BUT KEEP THE QUOTES!**)
5. Run `git push origin`. This pushes your changes to your fork.
6. Now, let's create a pull request. You will need the GitHub CLI installed from here on out, otherwise use your browser. Run `gh pr create`.
7. Follow the steps. If it asks you for which pull request template to use, you can just use whichever you like.
8. If you mess up, you can always select `Open in browser`. Once that is complete, navigate to [the GitHub PR list](https://github.com/osfanmuffin/muffinhunt-datapack-docs/pulls) and see your new pull request!
