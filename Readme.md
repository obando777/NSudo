﻿# NSudo - 一个强大的系统管理工具
> 注意：NSudo基于raymai97的超级命令提示符，关于raymai97的超级命令提示符，请参阅 [这里](http://bbs.pcbeta.com/viewthread-1508863-1-1.html "这里")

> Notice: NSudo is based on SuperCMD by Raymai97.Visit [here](http://bbs.pcbeta.com/viewthread-1508863-1-1.html "here") for more information about SuperCMD

## 使用方法 Usage
双击 ```NSudo.bat``` 自动打开相应架构的 NSudo ，根据提示操作即可

## 命令行选项 Command Line Options
> 使用 NSudo.exe -? 可以显示和这里一样的内容

```
格式: NSudo [ -U ] [ -P ] [ -M ] 命令行或常用任务名
  -U:[ T | S | C | P | D ] 用户
        T TrustedInstaller
        S System
        C 当前用户
        P 当前进程
        D 当前进程(降权)

  -P:[ E | D ] 特权
        E 启用全部特权
        D 禁用所有特权
        PS: 如果想以默认特权方式的话，请不要包含-P参数

  -M:[ S | H | M | L ] 完整性
        S 系统
        H 高
        M 中
        L 低
        PS: 如果想以默认完整性方式的话，请不要包含-M参数

  -? 显示该内容

  例子：以TrustedInstaller权限，启用所有特权，完整性默认运行命令提示符
                NSudo -U:T -P:E cmd
```

例子：以TrustedInstaller权限，启用所有特权，完整性默认运行命令提示符```NSudo -U:T -P:E cmd```
关于常用列表的自定义,可以使用记事本等工具编辑ShortCutList.ini；格式如下
```
[标题]
 CommandLine=命令行
```
PS：NSudo已经支持调用当前程序目录下的可执行文件啦！
举个例子：1、我要建立一个标题为"记事本",命令行为"c:\windows\system32\notepad.exe"的项目，可以这样做
```
[记事本]
CommandLine=c:\windows\system32\notepad.exe
```
或
```
[记事本]
CommandLine=%SYSTEMROOT%\notepad.exe
```
甚至
```
[记事本]
CommandLine=notepad
```
如果要使用引号嵌套的话；请加转义符，例如：```NSudo -u:t "cmd /c ren \"E:\班级视频 《ONE》\d.txt\" x.exe"```

## NSudo 许可协议 (NSudo License)
[NSudo 许可协议 (简体中文)](https://github.com/M2Team/NSudo/wiki/NSudo-%E8%AE%B8%E5%8F%AF%E5%8D%8F%E8%AE%AE-(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87))
[NSudo License (English)](https://github.com/M2Team/NSudo/wiki/NSudo-License-(English))

## 更新日志 Changelogs
参见 ```[Changelog.md](https://github.com/M2Team/NSudo/blob/master/Changelog.md "Changelog.md")```

## 捐赠 Donate
如果您想捐赠此项目，请使用 [支付宝 Alipay](https://alipay.com) 向我们的帐号  ```wxh32lkk@live.cn``` 进行付款。你们的捐赠是我（们）开发的动力（之一，还有我们的爱好~）。

## 下载 Download
下载地址：http://zh-cn.b0.upaiyun.com/NSudo/NSudo%204.0.zip

## MDL论坛根据地 MDL Post
(http://forums.mydigitallife.info/threads/59268-M2-Team-NSudo-(New-Version-4-0)

## 交流 Communication
如果碰到什么问题，可以在NSudo官方群（QQ群：```466078631```）探讨

## 感谢名单 (Thanks)
[感谢名单 (简体中文)](https://github.com/M2Team/NSudo/wiki/%E6%84%9F%E8%B0%A2%E5%90%8D%E5%8D%95-(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87))
[Thanks (English)](https://github.com/M2Team/NSudo/wiki/Thanks-(English))

##Have a good time -- M2-Team参上