# eslint-config-kiwicom-cypress

ESLint configuration for Cypress at Kiwi.com

This repo by itself exists as a proof of concept and a fast solution to aching problem, allowing us to move quickly.

Ultimate goal is to adjust & use [eslint-config-kiwicom](https://github.com/kiwicom/eslint-config-kiwicom) eventually.

#### Main differences to eslint-config-kiwicom :read-this:

* **No Prettier** as we prefer conceptual consistency over formatting consistency. [More reasing](https://strajk.github.io/QA-Academy/#/./cypress-best-practices?id=readability-gt-prettier)
* **Allow using of functions before definitiom** as we like to define helper functions at the end of the file
* **Spellchecking** as it useful, but could be slow on whole codebase.
* **Strict & opinionated rules specific to Cypress** as it's being develop rapidly and we don't wanna bother all other teams with it.  

## Links

* https://github.com/kiwicom/eslint-config-kiwicom-cypress
* https://www.npmjs.com/package/@kiwicom/eslint-config-kiwicom-cypress

## Usage

```
npx install-peerdeps --dev @kiwicom/eslint-config-kiwicom-cypress
```

Add `"extends": "@kiwicom/eslint-config-kiwicom-cypress"` to your `.eslintrc`


## Goals 


## Contributing

#### Publish

TODO: Smarter, nicer, more elegant solution.

```
npm publish
```
