---
icon: down-to-line
---

# Installation

Download our library from our [private npm registry.](https://npmregistry.viewzenlabs.in) Please contact support@viewzenlabs.com for access credentials.

## Create a <mark style="color:blue;">.nvmrc</mark> file

To download ViewZen Visual library from our private npm registry. Create a .nvmrc file with the following content.

```
registry=https://npmregistry.viewzenlabs.in
```

## Install <mark style="color:blue;">@viewzen/visual</mark> Angular Library

```sh
npm i @viewzen/visual@17
```

## Styles

themes and styles are important component of our library. Styles can be imported at <mark style="color:blue;">angular.json</mark>

```json
"build": {
  "options": {
    "styles": [
      "src/styles.scss",
      ...,
      "node_modules/@viewzen/visual/assets/css/visual.css"
    ],
    ...
  }
}
```
