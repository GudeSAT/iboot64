# iboot64patcher补丁工具

iBoot64Patcher

>修补iBoot64（+ SecureROM|AVPBooter）与通用补丁。

一、要求

1. macOS/Linux，

2.基本的编译工具，

3.解密的64位iBoot。

二、用法
用法： iBoot64Patcher [-p] <in> <out> [-e] [-b <boot-args>] [-a]

  -AVPBooter的申请补丁，

  -p 应用泛型补丁，

  -e 应用额外的补丁，

  -b 应用自定义引导参数。

$ iBoot64Patcher -p iBoot.RELEASE.bin iBoot.RELEASE.pwn -e -b "serial=3"

三、注意事项
>kairos是一种更好的方法（我的可用于测试目的），
> iBoot64Patcher 支持从 iOS 7 到 iOS 15 的任何 iBoots（无论是否经过 PACed），
