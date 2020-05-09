```sh-session
$ yarn
$ node file.js
/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:431
    throw new Error(`Configuration contains string/RegExp pattern, but no filename was passed to Babel`);
    ^

Error: Configuration contains string/RegExp pattern, but no filename was passed to Babel
    at matchPattern (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:431:11)
    at /Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:418:35
    at Array.some (<anonymous>)
    at matchesPatterns (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:418:19)
    at configFieldIsApplicable (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:400:10)
    at configIsApplicable (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:395:233)
    at /Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:245:9
    at Generator.next (<anonymous>)
    at buildRootChain (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/config-chain.js:90:27)
    at buildRootChain.next (<anonymous>)
    at loadPrivatePartialConfig (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/partial.js:95:62)
    at loadPrivatePartialConfig.next (<anonymous>)
    at loadFullConfig (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/config/full.js:57:46)
    at loadFullConfig.next (<anonymous>)
    at parse (/Users/simen/repos/babel-parse-exclude/node_modules/@babel/core/lib/parse.js:27:45)
    at parse.next (<anonymous>)
    at evaluateSync (/Users/simen/repos/babel-parse-exclude/node_modules/gensync/index.js:244:28)
    at sync (/Users/simen/repos/babel-parse-exclude/node_modules/gensync/index.js:84:14)
    at Object.<anonymous> (/Users/simen/repos/babel-parse-exclude/file.js:5:1)
    at Module._compile (internal/modules/cjs/loader.js:1133:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1153:10)
    at Module.load (internal/modules/cjs/loader.js:977:32)
    at Function.Module._load (internal/modules/cjs/loader.js:877:14)
    at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:74:12)
    at internal/main/run_main_module.js:18:47
```
