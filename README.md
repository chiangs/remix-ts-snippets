# Remix Snippets

Welcome! This is the repo for the `remix-ts-snippets` extension for Visual Studio Code.

- [Remix Snippets](#remix-snippets)
  - [Packaging and Publishing](#packaging-and-publishing)
  - [Features](#features)
  - [Release Notes](#release-notes)
    - [1.2.3](#123)
    - [1.2.2](#122)
    - [1.1.3](#113)
    - [1.1.2](#112)
    - [1.1.0](#110)
    - [1.0.0](#100)

## Packaging and Publishing

```sh
vsce package
vsce publish
```

## Features

All the snippets utilise the arrow function syntax. I made all the ones I use most often, but feel free to request for any you are missing via issues.

They include the import statements and have default positions for you to fill in missing info after insertion.

All commands start with `rmx:`. 

| Function                        | Command     |
| --------------------------------|------------ |
| Meta                            | `rmx:meta`  |
| Meta v2                         | `rmx:meta2` |
| Links                           | `rmx:links` |
| Action                          | `rmx:action`|
| Loader                          | `rmx:loader`|
| ErrorBoundary                   | `rmx:error` |
| CatchBoundary                   | `rmx:catch` |
| Basic component                 | `rmx:bc`    |
| Basic component w/ props        | `rmx:bcp`   |
| Route component                 | `rmx:rc`    |
| Route component with everything | `rmx:rca`   |

## Release Notes

### 1.2.3

Updated args typing for Actions and Loaders.

### 1.2.2

Updated route component snippet to export default on component. 

Added v2:

`rmx:meta2`

`rmx:rca2`

### 1.1.3

Update `rmx:bcp` to have a return since it's likely there will be additional logic when given props.

### 1.1.2

Fix ActionFunction naming and imports.

### 1.1.0

Update of README with commands and fix language support in manifest.

### 1.0.0

Initial release of ***Remix TS Snippets***.