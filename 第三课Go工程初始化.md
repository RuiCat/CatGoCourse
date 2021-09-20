# 第三课Go工程初始化

## 创建目录

* 创建 src/第三课 当作项目目录
* 在命令行下打开目录执行命令:
    > go mod init main

* 生成 go.mod 文件用于管理工程
* 新建 main.go 文件开始编写代码

``` go
// package 定义包名 main 包名
package main

// import 引用库 fmt 库名
import "fmt"

// func 定义函数 main 函数名
func main() {
 // fmt 包名 . 调用 Print 函数,并且输出定义的字符串
 fmt.Print("Hello Golang~~")
}
```

* 打开 mian.go 文件 F5 测试运行
    > 调试控制台输出字符串基础工程创建完毕
