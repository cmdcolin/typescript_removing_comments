# typescript removing comments

Some comments can encode semantic information. The comment "istanbul ignore next line" is used in code coverage sometimes

This repo is an example of the comment for istanbul ignore next line comment being removed

Note that this only happens with the es5 code setting in tsconfig, esnext and es6 both work

See [test.ts](test.ts) and [dist/test.js](dist/test.js) for detail


If you can restructure your code to not involve an async function then you can workaround this
