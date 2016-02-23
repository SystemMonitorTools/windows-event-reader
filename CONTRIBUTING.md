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

# Running the Tests

You'll want to make sure you add new tests for any new features you contribute and that you don't break any existing tests.

Tests are written in the [`./test`](./test) folder. You'll need to be working on a modern Windows operating system for developing
code in this module.

After you've forked and clone the repo execute the following to start the tests:

```
npm install
grunt test
```

These are the same tests that are ran in Appveyor CI. Happy coding!
