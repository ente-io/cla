# CLA

Configuration and state for the [CLA assistant GitHub action](https://github.com/contributor-assistant/github-action)

## Configuring a new repository

Follow the instructions in https://github.com/contributor-assistant/github-action.

tl;dr;

1. Copy `.github/workflows/cla.yml` and `CLA.md` from this repository into the
   target repository.

2. Add a `PERSONAL_ACCESS_TOKEN` in the target repository's GitHub secrets.

That's it. The bot will automatically check new PRs to ensure that all folks who
have commits have already signed the CLA. 

The signatures are kept in this repository.

To rerun the bot, include the word "recheck" in a comment.
