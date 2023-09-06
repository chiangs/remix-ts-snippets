# Remix Snippets

Welcome! This is the repo for the `remix-ts-snippets` extension for Visual Studio Code.

- [Remix Snippets](#remix-snippets)
  - [Packaging and Publishing](#packaging-and-publishing)
  - [Features](#features)

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
| Links                           | `rmx:links` |
| Action                          | `rmx:action`|
| Loader                          | `rmx:loader`|
| ErrorBoundary                   | `rmx:error` |
| Basic component                 | `rmx:bc`    |
| Basic component w/ props        | `rmx:bcp`   |
| Route component                 | `rmx:rc`    |
| Route component with everything | `rmx:rca`   |

