# sshexec

远程执行ssh命令的go脚本，部署后可以直接命令行使用

使用步骤：

### 直接运行可执行文件

```
git clone  https://github.com/liqiang311/sshexec.git
cd sshexec
./sshexec -h
```

### 若运行错误，则使用go进行编译

```
git clone  https://github.com/liqiang311/sshexec.git
cd sshexec
rm sshexec
go build
./sshexec -h
```

## 执行

`./sshexec -h`若正常，则显示

```
Usage of ./sshexec:
  -e string
        command line
  -i string
        IP
  -p string
        password
  -u string
        username
```

移动到系统执行目录下：

```
mv sshexec /usr/local/bin/
```
