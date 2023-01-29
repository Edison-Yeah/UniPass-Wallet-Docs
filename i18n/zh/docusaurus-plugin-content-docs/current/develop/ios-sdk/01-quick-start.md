---
sidebar_position: 1
---

# 快速开始

| 更新版本 | 更新日期   | 默认使用URL           |  更新说明|
| -------- | -------------- | ---------------------------------- | -------------------------------------------------------------------------------------- |
| v0.0.1   | 2023.01.14     | https://testnet.wallet.unipass.id/ | 增加 登录 / 发送交易 / 签名消息 / 登出 等 API 方法

## 相关资料

[iOS SDK Github](https://github.com/UniPassID/UniPass-Swift-SDK)

[iOS Demo 源码](https://github.com/UniPassID/UniPass-Swift-SDK/tree/main/Example) 


## 系统要求

适用于 iOS 12.0 及以上版本

## 安装步骤

1. UniPassSDK 以及发布在 CocoaPods. 添加下方命令到您项目的 Podfile 中即可:

```
pod 'UniPassSDK'
```

2. 通过下方命令更新您项目的 Pod 依赖:

```
pod install
```

3. 设置应用的 bundle identifier

4. 在您的项目代码中引入 `UniPassSDK`

```swift
import UniPassSDK
```

