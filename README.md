## Free Exercise DB

Over 800+ exercises and imagery, Completely open Public Domain and in JSON format

### Why?

I started building another fitness related app and was looking for free/open source exercise lists and imagery I stumbled upon
[exercises.json](https://github.com/wrkout/exercises.json) which was amazing though the data wasn't structured the way I wanted it and I also wanted a free browsable/searchable frontend to the data inspired by [this issue](https://github.com/wrkout/exercises.json/issues/5) so I restructured the data and built a simple frontend to it :)

### Where is it?

All exercises are in `JSON` format under [exercises](./exercises)

### Browsable frontend

There is a simple searchable/browsable frontend to the data written in [vuejs](https://vuejs.org/)  available at [https://yuhonas.github.io/free-exercise-db/](https://yuhonas.github.io/free-exercise-db/), all related code is in the [site](./site) directory


#### Setup

```sh
npm install
```

#### Compile and Hot-Reload for Development

```sh
npm run dev
```

#### Compile and Minify for Production

```sh
npm run build
```

#### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

#### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

#### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

### Contribute
Contributions are always welcome! Please read the contribution guidelines first.

### Special Thanks 🙇
To [Ollie Jennings](https://github.com/OllieJennings) for the original dataset at [exercises.json](https://github.com/wrkout/exercises.json)