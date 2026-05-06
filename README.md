# hmosworld.github.io

## HMOS Gesture Demo

本项目为GitHub Pages搭建的线上域名服务，聚焦于鸿蒙代码工坊客户端「一抓一放」手势交互示例，展示了基于`Applinking` 技术实现的鸿蒙风格手势交互效果。可直观参考集成于鸿蒙代码工坊客户端的sample[抓一抓](https://gitcode.com/HarmonyOS_Samples/GesturesShare)以及 [APP LINKING](https://developer.huawei.com/consumer/cn/doc/harmonyos-guides/app-linking-startupapp)。

## 项目结构

``` bash
hmos-world.github.io/
├── README.md               # 项目说明文档
└── gesture/                # 手势演示核心目录
    ├── README.md
    ├── index.html          # 演示页面入口
    ├── index.css           # 页面样式文件
    ├── index.js            # 手势交互逻辑
    ├── .well-known/        # 应用关联配置目录
    │   └── applinking.json # App Linking 配置文件
    └── imgs/               # 静态图片资源
        └── startIcon.png   # 演示启动图标
```

## 访问方式

1. 在线访问：https://hmos-world.github.io/gesture/
2. 本地运行：

```bash
# 克隆仓库
git clone https://github.com/HMOS-World/hmos-world.github.io.git
# 进入 gesture 目录
cd hmos-world.github.io/gesture
# 直接打开 index.html 文件（推荐使用本地服务器，如 VS Code Live Server）
```
