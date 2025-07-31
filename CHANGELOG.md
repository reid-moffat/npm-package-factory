# npm-package-factory

## 2.3.0

### Minor Changes

- 2ef5038:
  - Improved test workflow with matrix testing
  - Add linting workflow
  - Minor polishing to generated files

## 2.2.0

### Minor Changes

- b81382c: Updated spacing for README badges

## 2.1.0

### Minor Changes

- c4757a9:
  - Added badges to the README generation
  - Install changesets when generating the package
  - Added newlines to the end of generated files
  - Added badges to this package's README
  - Added repository URL to this package
  - Fixed package name in installation example

## 2.0.0

### Major Changes

- 1ee383e: First major stable release 🎉
  - Script runs with npx through the command line
  - Prompts the user for a package name, validating it's available
  - Prompts the user for a package directory, defaulting to the current one
  - Shows which dependencies will be used
  - Creates the files required, with CI, changeset management, typescript, tests, and more
