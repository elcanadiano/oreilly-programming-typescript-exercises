# Various Exercises related to "Programming Typescript - Making Your JavaScript Applications Scale"

The purpose of this repository is to document my solutions for the following
book, "Programming Typescript - Making Your JavaScript Applications Scale."

It is meant to be a read-only repostitory and not meant to be reflective of
optimal solutions for these exercises.

## Audibles

### Chapter 2

Because this book was written before `tslint` was deemed deprecated, the
documentation still refers to it. Today, `tslint` has been deprecated in favour
of direct TypeScript

Instead, for the initial setup, I recommend:

```
npm install --save-dev typescript @typescript-eslint/parser @types/node @typescript-eslint/eslint-plugin
```