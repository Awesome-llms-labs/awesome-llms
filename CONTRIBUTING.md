# Contributing to awesome-llms

This repo is the meta-index of the Awesome-llms-labs family. Thanks for helping keep the map accurate!

## Adding a new list to the index

1. The list must live in the [Awesome-llms-labs](https://github.com/awesome-llms-labs) org and follow the house convention: public, MIT, machine-readable JSON in `data/`, docs, CONTRIBUTING, green CI.
2. Add one row to the README table (alphabetical by repo name) and one object to `data/index.json`.
3. Update `docs/family-guide.md` if the new list changes the map.

## index.json schema

| field | type | rules |
|---|---|---|
| `name` | string | display name, unique across the file |
| `repo` | string | repo slug under Awesome-llms-labs |
| `url` | string | `https://github.com/awesome-llms-labs/<repo>` |
| `description` | string | one line |
| `categories` | string[] | one or more lowercase tags |

## Style rules

- Descriptions stay one line; depth lives in the list's own repo.
- Links point at the org repos, never forks or mirrors.
- Never invent entries: only lists that actually exist (or are confirmed in progress) go in the index.
