# Task Submissions

## How to submit tasks as Git Submodules

Use the following Git command to add collaborators repo in to the task as a submodule:

```sh
git submodule add { URL of the Repository } { Name of the Collaborator }
```

## How to pull all added submodules at once

If it is the first time, use `--init` option.

```sh
git submodule update --init --recursive
```

otherwise, use one of the following commands to pull all submodules from remotes.

```sh
git submodule update --recursive
```

```sh
git pull --recurse-submodules
```
