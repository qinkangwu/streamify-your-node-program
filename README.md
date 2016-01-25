# Node Stream
对[Node.js]中[stream]模块的学习积累和理解。

- [什么是流](docs/what-is-stream.md)
- [为什么使用流](docs/when-to-use-stream.md)
- [Readable](docs/readable.md)
  - [如何创建](docs/readable.md#如何创建)
    - [end事件](docs/readable.md#end事件)
  - [如何使用](docs/readable.md#如何使用)
    - [flowing模式](docs/readable.md#flowing模式)
    - [paused模式](docs/readable.md#paused模式)
- [Writable](docs/writable.md)
  - [创建与使用](docs/writable.md#创建与使用)
  - [finish事件](docs/writable.md#finish事件)
- [objectMode](docs/objectMode.md)
  - [对Readable的影响](docs/objectMode.md#对readable的影响)
  - [对Writable的影响](docs/objectMode.md#对writable的影响)
  - [什么时候用objectMode](docs/objectMode.md#什么时候用objectmode)
- [highWaterMark](docs/highWaterMark.md)
  - [Readable中的缓存](docs/highWaterMark.md#readable中的缓存)
  - [Writable中的缓存](docs/highWaterMark.md#writable中的缓存)
- [Duplex和Transform](docs/duplex-and-transform.md)
  - [Duplex](docs/pipe.md#duplex)
  - [Transform](docs/pipe.md#transform)
  - [Transform与Duplex比较](docs/pipe.md#transform与duplex比较)
- [pipe](docs/pipe.md)
  - [pipe的使用](docs/pipe.md#pipe的使用)
  - [从push到pull](docs/pipe.md#从push到pull)
  - [pipeline](docs/pipe.md#pipeline)
- [Node实现的CommonJS规范](docs/node-module.md)
- 实战技巧
  - [browserify](docs/browserify.md)
    - [需求](docs/browserify.md#需求)
    - [pipeline设计](docs/browserify.md#pipeline设计)
    - [插件机制](docs/browserify.md#插件机制)
    - [Transform机制](docs/browserify.md#transform机制)
  - [tools](docs/tools.md)

[Node.js]: https://nodejs.org/
[stream]: https://nodejs.org/api/stream.html

