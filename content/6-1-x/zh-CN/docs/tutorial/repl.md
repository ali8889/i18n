# 交互式解释器 (REPL)

读取(Read)-运算(Eval)-输出(Print)-循环(Loop) (REPL) 是很简单的, 交互式的计算机编程环境，它采用单个用户输入，运算并返回结果给用户。

在这里 `repl` 模块提供了一个 REPL 的实现, 可以这样使用:

* 如果你的 `electron` 或 `electron-prebuilt` 已经安装为本地项目依赖项:

  ```sh
  ./node_modules/.bin/electron --interactive
  ```
* 如果你的 `electron` 或 `electron-prebuilt` 已经为全局方式安装:

  ```sh
  electron --interactive
  ```

This only creates a REPL for the main process. You can use the Console tab of the Dev Tools to get a REPL for the renderer processes.

**注意:** `electron --interactive` 在 Windows 上不可用.

更多的内容可以在这里找到 [Node.js REPL docs](https://nodejs.org/dist/latest/docs/api/repl.html).
