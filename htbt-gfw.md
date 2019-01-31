# htbt-gfw

## Step 1： 下载软件

1. shadowsocksr
2. [Windows端](https://github.com/shadowsocksr-backup/shadowsocksr-csharp)
3. [Android 端](https://github.com/shadowsocksr-backup/shadowsocksr-android)
4. [Mac OS 端](https://github.com/shadowsocks/ShadowsocksX-NG)
5. iOS端：
   - 将App Store 账号更换成美区、港区等，购买“shadowrocket”，关于换区以及购买App问题可以自行搜索。
   - 下载PP助手，搜索“shadowrocket”。

## Step 2：购买服务器

[海外服务器购买商 - Vultr](https://www.vultr.com/?ref=7641106)

## Step 3：远程访问

- Windows用户：使用 **Xshell** 远程SSH访问并配置linux主机，如何访问自行搜索。

  [Xshell-百度网盘](https://pan.baidu.com/s/1etu4V3zgyTOSukzzy2k_-w)  密码:z0k1

- Mac OS 用户：使用自带的 **终端** 远程SSH访问并配置linux主机。

## Step 4：配置服务器

- 本脚本需要Linux root账户权限才能正常安装运行，所以如果不是 root账号，请先切换为root；如果是 root账号，那么请跳过

  ```powershell
  sudo su
  ```

- 输入上面代码回车后会提示你输入当前用户的密码，输入并回车后，没有报错就继续下面的步骤安装ShadowsocksR。

  ```powershell
  wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
  ```

- 下载运行后会提示你输入数字来选择要做什么。

参考资料：[CentOS/Debian/Ubuntu ShadowsocksR 单/多端口 一键管理脚本](https://doubibackup.com/z2a4lk3l.html)

### 推荐阅读

[htbt-gfw](https://program-think.blogspot.com/2009/05/how-to-break-through-gfw.html)

[逗比根据地1](https://doubmirror.cf/) 

[逗比根据地2](https://doubibackup.com/) 
