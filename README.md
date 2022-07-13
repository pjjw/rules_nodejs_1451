Sample configuration for issue https://github.com/bazelbuild/rules_nodejs/issues/1451

Updated for rules_js, behavior still as described in the bug.

```shell
npm run-script ng # (1) >>>> FAIL: RUNFILES environment variable is not set. <<<<
npm run-script ok # (2) OK. Shows usage info for lorem-ipsum tool
```
