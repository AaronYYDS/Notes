# docker-compose arm64版本
## 有条件的建议自行编译吧 以下为使用方法

```
sudo curl -L "https://github.com/AaronYYDS/docker-compose-aarch64/releases/download/main/docker-compose-Linux-aarch64" -o /usr/local/bin/docker-compose
```
## 将可执行权限应用于二进制文件：
```
sudo chmod +x /usr/local/bin/docker-compose
```
## 创建软链：
```
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```
## 测试是否安装成功：
```
root@aaron:~# docker-compose -version
docker-compose version 1.22.0, build e20d808e
```
