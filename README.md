# renovate-test


#### the current behavior

When create a update for the package2's devDependencies `eslint`. It will throw an error, the error log is here. Because of for lerna v7, there is no bootstrap command.
```
lerna notice cli v7.0.2
ERR! bootstrap The "bootstrap" command was removed by default in v7, and is no longer maintained.
ERR! bootstrap Learn more about this change at https://lerna.js.org/docs/legacy-package-management
```

#### expected behavior

For expected, https://github.com/yanguoyu/renovate-test/pull/3 should run success.