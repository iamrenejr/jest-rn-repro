## Issue Encountered

Jest is failing to pass:

```
yarn run v1.9.4
$ ~/Documents/repos/Github/jest-rn-repro/node_modules/.bin/jest -u
 FAIL  src/__tests__/add.test.js
  ● Test suite failed to run

    Cannot find module 'warnOnce' from 'react-native-implementation.js'

      at Resolver.resolveModule (node_modules/jest-resolve/build/index.js:229:17)

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        1.784s
Ran all test suites.
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

## Expected behavior

Test doesn't fail due to `Cannot find module 'warnOnce' from 'react-native-implementation.js'`

## Steps to Reproduce

1. Clone this repository

2. `npm install`

3. `jest`, `npx jest`, or `yarn jest`
