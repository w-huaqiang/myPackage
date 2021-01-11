# wPackage 
平时写的一些库，可以在开发中使用

### wLog
为日志库
使用
```go
package main

import "github.com/w-huaqiang/wPackage/wLog/wlog"

func main() {

	testString := "hahaha"
	log := wlog.NewWlog("wanghuaqiang.log", "Warning")
	//log := wlog.NewWlog(os.Stdout, "Info")

	log.Debug("debug log")
	log.Info("info log")
	log.Warning("warning log")
	log.Error("error log")
	log.Fatal("fatal log")

	log.Warning("jilurizhi %s", testString)

}
```
