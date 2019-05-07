# GO Trace

http trace for golang

GO trace 是穿云组件中针对 go 语言的无侵入式探针。

具体实现方法为
修改 Go 的 Runtime，生成打包用的 Go 程序，线上业务代码 build 时使用，编译出来的程序即具有 trace 能力。
