# deno_base

A minimal boilerplate for modules and programs written for [Deno](https://github.com/denoland/deno).

- Running scripts with yarn or npm
- Linting with ESLint
- Write and run tests with [Deno's standard testing library](https://github.com/denoland/deno_std/tree/master/testing).

## Getting Started

Clone this repository to a custom directory

```sh
git clone https://github.com/fnky/deno_base.git new_project
```

## Keeping up-to-date

If you'd like to be able to update from the repository, you can point the `upstream` to this repository.

```sh
# rename origin to upstream
git remove rename origin upstream
# verify the change
git remote -v
```

And then fetch and merge changes from upstream, whenver you want.

```
# Fetch all commits from upstream
git fetch upstream master
# See changes between current branch and upstream branch
git diff master upstream/master
# Merge changes
git merge upstream/master
```

## Writing and running tests

1. Create a file and name it something like `example_test.ts`.
2. Import the test inside `tests.ts`.
    ```
    import "./example_test.ts";
    ```
3. Run `yarn test`.

## LICENSE

MIT
