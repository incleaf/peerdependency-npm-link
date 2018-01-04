# peerdependency-npm-link

Following commands will prevent the build result having duplicated `react` dependency:

```shell
$ (main) npm link ../react-hello-world
$ (react-hello-world) npm link ../main/node_modules/react
```

## References

- https://github.com/npm/npm/issues/5875
- https://github.com/nodejs/node/pull/6537
- http://codetunnel.io/you-can-finally-npm-link-packages-that-contain-peer-dependencies/
- https://stackoverflow.com/questions/31169760/how-to-avoid-react-loading-twice-with-webpack-when-developing/38818358#38818358
- https://stackoverflow.com/questions/25684309/npm-peerdependencies-during-development/25800501#25800501
