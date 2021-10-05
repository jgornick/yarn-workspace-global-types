# yarn-workspace-global-types

Steps to reproduce:

* Clone repository (`git clone git@github.com:jgornick/yarn-workspace-global-types.git`)
* Install dependencies (`yarn`)
* In VSCode, open index.test.ts to see `jest` isn't found

> Remove tsconfig.json `typeRoots` for `jest` to be found.
