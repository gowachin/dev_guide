## Release book version <insert version>

### Repo maintenance between releases

- [ ] Look at the issue tracker for [the dev guide](https://github.com/ropensci/dev_guide/issues) and for [software review meta](https://github.com/ropensci/software-review-meta/issues) for changes still to be made in the dev guide. Assign dev guide issues to milestones corresponding to versions, either the next one or the one after that, e.g. [version 0.3.0](https://github.com/ropensci/dev_guide/milestone/2). Encourage PRs, have them reviewed.

### 1 month prior to release

- [ ] Remind editors to open issues/PRs for items they want to see in the next version.

- [ ] Run [the `devguide_prerelease()` function](https://github.com/ropensci-org/devguider) from the `devguider` package.

- [ ] Ask editors for any feedback you need from them before release.

- [ ] For each contribution/change make sure the NEWS in Appendix.Rmd were updated.

- [ ] Plan a date for release in communication with rOpenSci's Community Manager who will give you a date for publishing a blog post / tech note.

### 2 weeks prior to release

- [ ] Draft a blog post / tech note about the release with enough advance for editors and then Community Manager to review it (2 weeks). [Example](https://github.com/ropensci/roweb3/pull/291), [General blog post instructions](https://github.com/ropensci/roweb2#contributing-a-blog-post), [specific instructions for release posts](#releaseblogpost). 

- [ ] Make a PR from the dev branch to the master branch, ping editors on GitHub and Slack. Mention the blog post draft in a comment on this PR.

### Release

- [ ] Check URLs using [the `devguide_urls()` function from the {devguider} package](https://github.com/ropensci-org/devguider)

- [ ] Check spelling using [the `devguide_spelling()` function from the {devguider} package](https://github.com/ropensci-org/devguider). Update the [WORDLIST](https://github.com/ropensci/dev_guide/blob/master/inst/WORDLIST) as necessary.

- [ ] Squash and merge the PR from dev to master.

- [ ] GitHub release, check Zenodo release.

- [ ] Re-build (for Zenodo metadata update in the book) or wait for daily build

- [ ] Re-create the dev branch

- [ ] Finish your blog post / tech note PR. Underline the most important aspects to be highlighted in tweets as part of the PR discussion.
