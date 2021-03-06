# Android-WhiteListTool
Android 启动白名单工具-用于帮助用户直达白名单管理

# 下载测试

<img src="https://raw.githubusercontent.com/xuehuayous/Android-WhiteListTool/master/app/qrcode.png" width="200" />

# 合作贡献

1. 如果下面列表没有不包含你测试的机型，那么来用GitHub进行一次团队合作吧😆~ [如何pull request](https://github.com/xuehuayous/Android-WhiteListTool/blob/master/pull_request.md)

2. 如果不支持你的机型，如何支持我的机型？

    找到手机的白名单，通过`adb`命令查看`activity`名称。
    
    ```
    // MAC
    adb shell dumpsys activity | grep "mFocusedActivity"
    // Windows
    adb shell dumpsys activity | findstr "mFocusedActivity"
    ```
    
    修改`WHITE_LIST.md`按照第一步`pull request`。

# 支持机型列表

## 华为

`P7-L07 EMUI 3.1(5.1.1)` `P8 GRA-CL00 EMUI 4.2.0(6.0)` `Mate9 EMUI 5.0(7.0)`

## 小米

`MIX 2 MIUI 10.0.1.0.ODECNFH(8.0.0)` `MIX 2s MIUI 9.6.7.0.ODECNFH(8.0.0)` `HM NOTE 1S CMCC MIUI 6.4.8.0.KHKCNCB(4.4.4)` `HM NOTE 1S CMCC MIUI 9.2.2.0.KHKCNEK(4.4.4)` `MI NOTE TE MIUI 9.2.3.0MXECNEK(6.0.1)` `MI 3W MIUI 10.1.1.0.MXDCNFI(6.0.1)`

## OPPO

`R15 PACM00 ColorOS 5.0(8.1.0)` `R7s ColorOS 2.1(4.4.4)` `R9t ColorOS 3.0.0(5.1)` `R17 PBEM00 cOLORos 5.2(8.1)`

## Vivo

`vivo X6D Funtouch OS_2.5(5.1)`

## Letv

`1s Letv X501 EUI 5.9.028s(6.0)`

## 锤子

`YQ601 smartisan os 4.2.6(5.1.1)`