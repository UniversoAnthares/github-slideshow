# GitHub slideshow

> **Legacy course repository:** GitHub Learning Lab was deprecated and its course repositories were archived on September 1, 2022. The Learning Lab bot, issue-based lessons, and pull-request comments described by the original README are no longer active.

For a current beginner course, use [GitHub Skills – Introduction to GitHub](https://github.com/skills/introduction-to-github).

This repository contains a small [reveal.js](https://github.com/hakimel/reveal.js/) slide deck. The reveal.js runtime is kept in the tracked `node_modules/reveal.js` directory, so no npm install is required for the checked-in presentation assets.

## Local development

The build uses Ruby, Bundler, Jekyll, and HTML Proofer. From the repository root:

```sh
./script/setup
./script/server
```

To build and validate the generated site without starting a server:

```sh
./script/cibuild
```

The staging script publishes to an external service and requires that service's credentials; it is not needed for local development.
