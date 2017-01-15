```
yarn
./node_modules/.bin/eslint x.js
```

^ Passes

Remove the `flowtype/define-flow-type` rule, and it'll fail on `'T' is not defined  no-undef`.
