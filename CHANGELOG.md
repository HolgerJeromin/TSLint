# Changelog

## 0.4

**2017-06-07**

- Resolve [#3 System.ArgumentException on a single ts file with no project/solution](https://github.com/vladeck/TSLint/issues/3)
(support for dragged or explicitly opened `.ts` files).
- Support linting even when there is no solution/project associated to the opened `.ts` file
(when the `tslint.cmd` and `tslint.json` are somewhere in the path of the opened `.ts` file)

## 0.3.1

**2017-06-07**

- Resolve [#2 Support configuration files](https://github.com/vladeck/TSLint/issues/2) (better `extends` support).

## 0.3

**2017-05-31**

- Add support for Visual Studio 2015.

## 0.2.2

**2017-05-25**

- Cache project/solution and tslint.cmd path pairs when linting (small performance improvement).

## 0.2.1

**2017-05-23**

- Support local installation of `tslint` relative to the opened document's solution (project's `tslint` takes precedence).

## 0.2

**2017-05-23**

- Support local installation of `tslint` relative to the opened document's project.

## 0.1

**2017-05-23**

- First release