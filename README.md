# Go 语言之旅

《Go 语言之旅》是官方 Go Tour 的中文翻译版。
请访问 https://tour.go-zh.org/ 开始学习。

## 下载/安装

要从源码安装本教程，首先请[设置一个工作空间](https://go-zh.org/doc/code.html)并执行

	$ go get -u github.com/Go-zh/tour

这会在你工作空间的 `bin` 目录中创建一个可离线执行的 `tour` 文件。

（如果安装过程中出现 `package` 或 `import` 字样的错误提示，那么说明依赖库的导入路径又挂了。这时请猛戳 @OlingCat 并督促其解决= =||）

> 注：如果在 bin 目录下执行 tour 报错 `Couldn't find tour files: could not find go-tour content; check $GOROOT and $GOPATH`，需要切换到源码目录下执行 tour。

	$ cd $GOPATH/src/golang.org/x/tools/ && $GOPATH/bin/tour

## 贡献方式

贡献方式应遵循与 Go 项目相同的流程：http://go-zh.org/doc/contribute.html

要在本地测试 tour 服务，请参考 [Go App Engine 官方文档](https://cloud.google.com/appengine/docs/standard/go111/runtime)。

## 问题报告/发送补丁

本教程中文版直接托管在 Github 上，提交更改请直接发送 PR。

问题报告请在 github.com/Go-zh/tour/issues 上发起。

## 授权许可

除特别声明外，go-tour 源码文件均采用 BSD 风格的授权许可分发，许可内容见 `LICENSE` 文件。
