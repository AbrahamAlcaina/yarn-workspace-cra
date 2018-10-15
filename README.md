# yarn-workspace-cra
demo of setting up a cra app within a yarn workspace

This only works with yarn workspaces (https://yarnpkg.com/lang/en/docs/workspaces/).  
Make sure you use node >= 8.10 and yarn >= 1.8.

1. Add workspaces entry to the main package.json
1. Set name and main entries to package.json in both admin/ and common/
1. In admin/'s package.json add dependency to common/
1. In common/ add babel related depdencies and scripts.
1. Add lerna in main package.json and add lerna.json
1. To start/build in dev mode, run yarn start/yarn build in the main directory.
