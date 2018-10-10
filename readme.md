Jest `expect` typings from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/jest

This includes the entire `jest` namespace, but only declares `expect`, and not `beforeEach`, `it` etc.

Designed to be used alongside https://www.npmjs.com/package/expect

## Why?

The complete `@types/jest` typings conflict with `@types/mocha`, as they both try to declare different global types such as `beforeEach`, `it` etc
