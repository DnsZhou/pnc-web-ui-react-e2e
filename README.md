# PNC Web UI React End-to-End Tests

## Bootstrapping

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). Too see more details about bootstrapping, open [documentation/bootstrapping.md](./documentation/bootstrapping.md)

## Changelog

[Changelog](https://github.com/project-ncl/pnc-web-ui-e2e-test/wiki/Changelog)

## Prerequisites

1. `Node.js` version >= 14
2. `NPM` version >= 7
3. `Prettier`

## Workflows

Contribute using [GitHub flow](https://guides.github.com/introduction/flow/), once new Pull request is created, [GitHub Workflows](https://github.com/project-ncl/pnc-web-ui-e2e-test/tree/main/.github/workflows) are started and jobs consisting of building and testing are executed.

To see more details about scripts added by Create React App, open [documentation/README_CRA.md](./documentation/README_CRA.md)

First prepare project locally:

```bash
git clone <yourGitForkUrl> pnc-web-ui-e2e-test
cd ./pnc-web-ui-e2e-test/
npm install
```

Then choose one of the following options:

**1) Development**

```bash
npx cypress open   # Opens Cypress in the interactive GUI.
```
