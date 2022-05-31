# Go_Study
I learning go here.
报错一：
go: cannot find main module
解决：（项目根目录下）go mod init

报错二：
# runtime/internal/sys
/usr/local/go/src/runtime/internal/sys/consts.go:13:7: StackGuardMultiplier redeclared in this block......
解决：（版本问题）卸载重装，参考：https://www.likecs.com/show-203613068.html