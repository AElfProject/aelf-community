# Pull request

For any non trivial modification of the code, the pull requests should be associated with an issue that was previously discussed. During the time you implement and are not yet ready for review, prefix the PR's title with [WIP] and also don't forget to do the following:

- add a description in the pull request saying which issue you are fixing/implementing.

- be as explicit as possible about the changes in the description.

- add the tests corresponding to your modifications.

- pull requests should be made against the dev branch.

When you are ready for a review by the core team, just remove [WIP] from your PR's title and others will review. This will either lead to a discussion or to a refactor of the code. The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit tests are run automatically. The CI passing is a pre-condition for the PR to be merged as well as the approval from the core team.

