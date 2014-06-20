# Compare Gem versions across various apps

It's intended to highlight where diferent apps have fallen out of sync with shared gems

## Config

Pass configuration as query params, supported params are;

* `token` - A Github API token
* `repos` - A comma-seperated list of repository names, qualified with user, eg `dsingleton/compare-gem-versions`
* `gems` - A comma-seperated list of gem names
* `refresh` - How often to update, in seconds [_optional_, defaults to `60`]
* `at` - A treeish (tag, branch, etc) to check against, [_optional_, defaults to `master`]
