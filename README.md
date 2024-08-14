```
npm install
node .
```

```
(node:73502) Warning: To load an ES module, set "type": "module" in the package.json or use the .mjs extension.
(Use `node --trace-warnings ...` to show where the warning was created)
/Users/antonioivanovski/dev/iden3-invalid-build/node_modules/@iden3/js-iden3-core/dist/node/esm/index.js:1
export * from './claim';
^^^^^^

SyntaxError: Unexpected token 'export'
    at internalCompileFunction (node:internal/vm:77:18)
    at wrapSafe (node:internal/modules/cjs/loader:1288:20)
    at Module._compile (node:internal/modules/cjs/loader:1340:27)
    at Module._extensions..js (node:internal/modules/cjs/loader:1435:10)
    at Module.load (node:internal/modules/cjs/loader:1207:32)
    at Module._load (node:internal/modules/cjs/loader:1023:12)
    at cjsLoader (node:internal/modules/esm/translators:356:17)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/translators:305:7)
    at ModuleJob.run (node:internal/modules/esm/module_job:218:25)
    at async ModuleLoader.import (node:internal/modules/esm/loader:329:24)

Node.js v20.11.0
```