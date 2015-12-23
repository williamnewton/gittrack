# Contributing

Contributions are always welcome! Be sure to follow the [github workflow](https://guides.github.com/introduction/flow/) when contributing to this project:

* Create an issue, or comment on an issue to indicate what you are working on. This avoids work duplication.
* Fork the repository and clone to your local machine
* You should already be on the default branch `master` - if not, check it out (`git checkout master`)
* Create a new branch for your feature/fix `git checkout -b my-new-feature`)
* Write your feature/fix
* Stage the changed files for a commit (`git add .`)
* Commit your files with a *useful* commit message ([example](https://github.com/Azure/azure-quickstart-templates/commit/53699fed9983d4adead63d9182566dec4b8430d4)) (`git commit`)
* Push your new branch to your GitHub Fork (`git push origin my-new-feature`)
* Visit this repository in GitHub and create a Pull Request.

# Pre-requisites

- Node.js (Testing using node 0.12.7). To make things easy I recommend using [nvm](https://www.npmjs.com/package/nvm)
-[Ember-CLI](https://www.npmjs.com/package/ember-cli)

# Running the App Locally

To run GitTrack, just do:

```
npm insatll && bower install
ember serve
```

Then open your browser, and go to `http://localhost:4200`

# Running the Tests

Tests are written in the [`./test`](./test) folder. Today the only tests that are being ran are simple 'ensure exists' tests. In the very near future we'll have component and integration tests. For now, I'm just manually validating changes.