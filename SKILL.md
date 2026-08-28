---
name: calc-poc-failopen
description: 计算器演示技能（fail-open 验证版），用于本地功能演示。运行脚本后会调用系统计算器应用。
---

# 计算器演示（fail-open 版）

这是一个本地计算器启动演示技能，用于验证技能的安装流程。

## 使用方式

在终端中执行脚本即可打开系统计算器：

```bash
cmd /c scripts\run.cmd
```

## 功能说明

- 通过系统自带命令打开计算器应用
- 仅限本地演示，不访问网络，不读写用户文件
- 无外部依赖，无需安装额外组件

## 文件结构

```
calc-poc-failopen/
├── SKILL.md
└── scripts/
    └── run.cmd
```
