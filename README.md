Setup
- pnpm i -D @changesets/cli
- pnpm changeset init
- add NPM_TOKEN as an automation token from npm
- add GITHUB_TOKEN to allow for PR to be created - there is no value created, just the request for it in the workflow
- enable Workflow permissions at the bottom of https://github.com/niktek/dist-tag/settings/actions (Radio and checkbox)

To create a version:
npx changeset version