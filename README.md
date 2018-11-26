# Example Component Library - React

## Getting Started

1. Clone the project: `git clone git@github.com:garmeeh/example-component-library.git`
2. Setup project: `yarn install`
3. Run `yarn start`

Running `yarn start` will spin up Storybook and navigating to http://localhost:9001/ you will be able to see the example packages showcased in Storybook. One of the packages, `wireframe-ui`, uses our components and adds a UI to them. This is then published to give us a type of wire frame component library.

## Scripts

A look at some of the scripts that are available:

- To [bootstrap](https://github.com/lerna/lerna#bootstrap) your packages and start your UI development environment run:

```
yarn start
```

- Builds all of your packages ready for publishing:

```
yarn build
```

- Run all your packages tests and generate coverage report:

```
yarn test
```

- To export your storybook as a static app:

```
yarn export-static-storybook
```

- It will be placed in `.out/` To test locally after export:

```
cd .out
python -m SimpleHTTPServer
```

- Create a new release of the packages that have been updated. Prompts for a new version and updates all the packages on git and npm:

```
yarn publish-packages
```
