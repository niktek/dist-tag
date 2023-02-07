Setup
- pnpm i -D @changesets/cli
- pnpm changeset init
- add NPM_TOKEN as an automation token from npm
- add GITHUB_TOKEN to allow for PR to be created - there is no value created, just the request for it in the workflow

To create a version:
npx changeset version