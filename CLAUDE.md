# SignHook - 签名助手 Xposed 模块

## 项目概述
SignHook 是一个 Xposed 模块，用于修改应用签名信息，解决第三方登录问题。

## 技术栈
- **开发语言**: Java/Kotlin
- **Hook 框架**: [YukiHookAPI](https://github.com/fankes/YukiHookAPI)

## 环境要求
- Android 8.0+
- 已安装 Xposed 框架

## 使用说明
1. 初次进入下拉刷新即可获取应用
2. 在右上角添加作用域包名
3. 在 LSPosed 框架内勾选需要作用的应用
4. 填写伪造签名值
5. 重启作用域包名的应用才会生效

## 常见问题
- 读取签名错误：注意要从内部存储里选择 APK，不是"最近"或者其他地方
- 内置问题：注意是针对要登录/分享的平台，如 QQ、微信等

## 构建命令
```bash
./gradlew assembleRelease
```

## 免责声明
该 Xposed 模块仅供学习交流使用，使用者必须自行承担使用该模块所带来的风险和责任。

## 作者
xihan123
