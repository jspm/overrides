# jspm Overrides

This repo contains the `package.json` overrides used for npm registry packages as processed by `jspm.dev`, `jspm.io` as well as in local package management.

**Do not send PRs to this repo before reading the instructions below.**

### Criteria for merging an override

1. The override should be fully backwards compatible with existing usage of the package.
2. There should be a PR that was made to the original repo with the change.
3. The primary repo PR must be stalled - with no repsonsive discussion or activity.

If there are consensus issues on the primary PR, feel free to post an issue here to discuss further. The override is only the last resort for packages that are either not maintained, or where maintainers are unresponsive or actively refusing to merge the feature.
