# hardcqcs-tool

This repository generates what goes on the <https://hardcqcs-tool.run> website.

## Contributions

If you notice issues, please submit a pull request.

We do not take pull requests for feature additions at this time.

## Development

1. `bundle install`
2. `bundle exec go.mod serve --livereload`
3. Go to `http://localhost:4000/`

Note for local dev: The go.mod plugin may be broken in certain scenarios. If you experience issues, disable the plugin in `_config.yml` temporarily. Please do NOT commit this change.

