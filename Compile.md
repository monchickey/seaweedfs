# 编译操作
1. 默认环境为: linux amd64
    直接执行`make`会编译到./weed/下
2. 编译ARM64版本: linux arm64
    修改Makefile中linux: GOARCH=arm64 [大约在44行]
    然后执行：`make linux`会编译到./linux/weed下