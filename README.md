# Minimal reproduction of yarn npm audit error

Running `yarn` and `yarn npm audit -AR` results in the following error:

```sh
YN0001: TypeError: le.trim is not a function
    at /.yarn/releases/yarn-4.5.0.cjs:694:1891
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async AA.start (/.yarn/releases/yarn-4.5.0.cjs:199:6855)
    at async SC.execute (/.yarn/releases/yarn-4.5.0.cjs:694:1231)
    at async SC.validateAndExecute (/.yarn/releases/yarn-4.5.0.cjs:94:787)
    at async t.run (/.yarn/releases/yarn-4.5.0.cjs:98:3249)
    at async fPt (/.yarn/releases/yarn-4.5.0.cjs:735:7743)
    at async Wx (/.yarn/releases/yarn-4.5.0.cjs:736:142)
```
