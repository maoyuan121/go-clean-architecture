此代码对应文章：Golang 简洁架构实战 https://www.luozhiyun.com/archives/640

在 go 里面 DI 的工具相对来说没有 java 这么方便，技术框架一般主要有：wire、dig、fx 等。
由于 wire 是使用代码生成来进行注入，性能会比较高，
并且它是 google 推出的 DI 框架，所以我们这里使用 wire 进行注入。
