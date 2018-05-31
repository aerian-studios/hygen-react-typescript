# React TypeScript code generator

A [Hygen](https://www.hygen.io) generator module for TypeScript React. To install, first make sure you have installed hygen and hygen-add:

```sh
npm i -g hygen hygen-add
```

Then install this package:

```sh
hygen-add react-typescript
```

This will install the templates in the `_templates` directory. You can then use hygen to generate React components. It will create an SFC by default, unless you also pass the `--class` flag, in which case it creates a PureComponent. It generates files for the component, stylesheet, style typings, tests and storybook, as well as an index file so that you can import from the directory root. You can uninstall the package at this point: the templates will remain (and should be checked into your repo).

Usage:

```sh
hygen component new [--class] --name NAME
```

It camel-cases the name automatically if you haven't.
