# React 深入学习 - react 项目结构介绍

reactjs 基本没有什么第三方依赖，除了 facebook 内部的一些工具库 `fbjs`.

## reactjs 项目结构

```
.
├── fixtures
├── packages
└── scripts
```

从上图可以看出，react 项目根目录下的项目结构比较简单，从 <https://reactjs.org/docs/codebase-overview.html#top-level-folders> 可以了解到详细说明。

这里简单复述一下：

- packages 包含了 react 所有源码，这里要说明下，react 并不是一个单独的包，在他的项目仓库中维护了多个单独的 react 相关包。

- fixtures 包含了一些 react 的测试小工具

- scripts 是一些构建之类的脚本