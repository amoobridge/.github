## 项目

| 项目 | 说明 |
|---|---|
| [amoo-bridge-lite](https://github.com/amoobridge/amoo-bridge-lite) | StepBridge。让 AI 助手在用户本人授权的设备上完成文件、应用、界面结构、通知四类操作。一次 HTTP 调用一个工具，参数与返回都是扁平 JSON。 |
| [amoo-dsh](https://github.com/amoobridge/amoo-dsh) | Amoo DSH。把 DeepSeek Harness 引擎原样跑在 Android 本机回环上，界面用原生 Compose 复刻官方 Web UI。 |

## 共同点

- 引擎和接口只监听 `127.0.0.1`，不出设备
- 不修改第三方应用，不注入进程，不要求 root，不申请设备管理员
- 权限都对应系统里一个用户可见、可随时关闭的开关

## 参与

StepBridge 的构建环境依赖 step neo 手机的冷热分区，外部无法复现。文档修正和缺陷报告随时欢迎，代码改动请先开 issue 说明场景。

详见 [CONTRIBUTING.md](https://github.com/amoobridge/.github/blob/main/CONTRIBUTING.md)。

安全问题请走 [SECURITY.md](https://github.com/amoobridge/.github/blob/main/SECURITY.md) 的渠道，不要开公开 issue。

## 商标说明

Amoo DSH 是独立项目，与 DeepSeek 官方没有隶属关系，项目名不使用 DeepSeek Harness 商标。
