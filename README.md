# Tic-Tac-Toe（三子棋游戏）
A classic Tic-Tac-Toe game implemented in C language, supporting human vs human gameplay with clear interactive prompts.

## 项目介绍
本项目基于 C 语言实现经典的三子棋游戏，核心逻辑包含棋盘初始化、落子判定、胜负判断、棋盘打印等功能，代码结构清晰，适合 C 语言入门学习。

## 运行方式
### 编译环境
- Visual Studio 2019/2022 或 GCC（MinGW）
- Windows 系统（代码适配 Windows 命令行交互）

### 操作步骤
1. 下载仓库中所有 `.c`（game.c/text.c）和 `.h`（game.h）文件；
2. 使用 Visual Studio 打开 `Tic-Tac-Toe.sln` 工程，或通过 GCC 编译：
   ```bash
   gcc game.c text.c -o Tic-Tac-Toe.exe
