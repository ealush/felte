# @felte/solid

## 0.3.0

### Minor Changes

- 6fe19bf: BREAKING: Felte core now only needs a store factory to work. Framework integrations do not need to provide all stores but only a factory function that creates an observable.

### Patch Changes

- 6fe19bf: Add support for warnings
- 6fe19bf: Change build output from umd to cjs, since Felte is not planned to be used as a global import, a umd build is not necessary.
- 6fe19bf: Clean up subscriptions if Felte wasn't used by registering the form using `form()`
- Updated dependencies [6fe19bf]
- Updated dependencies [6fe19bf]
- Updated dependencies [6fe19bf]
  - @felte/core@0.3.0

## 0.2.7

### Patch Changes

- 4b637d0: Add `setInitialValues` helper and `isDirty` store
- Updated dependencies [4b637d0]
- Updated dependencies [5d7b58d]
  - @felte/core@0.2.7

## 0.2.6

### Patch Changes

- Updated dependencies [e324a45]
  - @felte/core@0.2.6

## 0.2.5

### Patch Changes

- Updated dependencies [1807c09]
  - @felte/core@0.2.5

## 0.2.4

### Patch Changes

- 14b3645: Add `transform` feature
- Updated dependencies [14b3645]
  - @felte/core@0.2.4

## 0.2.3

### Patch Changes

- Updated dependencies [3dcfe7c]
  - @felte/core@0.2.3

## 0.2.2

### Patch Changes

- Updated dependencies [e1afd46]
  - @felte/core@0.2.2

## 0.2.1

### Patch Changes

- 096f9a5: Pass a `context` to `onSubmit` calls
- f79c67f: Listen to programmatic changes of inputs
- Updated dependencies [096f9a5]
- Updated dependencies [f79c67f]
  - @felte/core@0.2.1

## 0.2.0

### Minor Changes

- 2d3b213: BREAKING: Remove `reporter` configuration option in favor of `extend`.

### Patch Changes

- Updated dependencies [2d3b213]
- Updated dependencies [de71f43]
  - @felte/core@0.2.0

## 0.1.9

### Patch Changes

- 5bb4a02: Add data-felte-ignore attribute to make Felte completely ignore an input
- Updated dependencies [5bb4a02]
  - @felte/core@0.1.6

## 0.1.8

### Patch Changes

- Updated dependencies [6b8aafb]
  - @felte/core@0.1.5

## 0.1.7

### Patch Changes

- 16ff018: Export ES module as default
- Updated dependencies [16ff018]
  - @felte/core@0.1.4

## 0.1.6

### Patch Changes

- e6034c0: Use `Record<string, any>` for config type in order to allow interfaces to be passed as types
- Updated dependencies [e6034c0]
  - @felte/core@0.1.3

## 0.1.5

### Patch Changes

- Updated dependencies [8049209]
  - @felte/core@0.1.2

## 0.1.4

### Patch Changes

- 4e28835: Fix isValid setter

## 0.1.3

### Patch Changes

- 3118b72: Use @felte/core instead of @felte/common

## 0.1.2

### Patch Changes

- Fix store behaviour on multi inputs

## 0.1.1

### Patch Changes

- Fix issues due to mutability of common functions
- Updated dependencies [undefined]
  - @felte/core@0.1.1

## 0.1.0

### Minor Changes

- 809f9af: Refactor to use a common core
- 809f9af: Add SolidJS wrapper

### Patch Changes

- Updated dependencies [809f9af]
  - @felte/core@0.1.0
