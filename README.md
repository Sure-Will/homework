# homework 🧠💻

这里是我的 C/C++ 练习与作业仓库（Visual Studio 解决方案：`homework.slnx`）。
主要内容包括：课堂作业（按题号划分）与少量算法/LeetCode 练习。

## 目录结构 📂

- `homework.slnx`  
  Visual Studio 解决方案入口（包含多个题目项目）

- `1/` ~ `60/`  
  每个文件夹对应一道作业题（通常包含：
  - `xx.cpp`：代码
  - `xx.vcxproj` / `xx.vcxproj.filters`：VS 项目文件）

- `LC 27 Remove Element/`  
  LeetCode 练习项目（示例：LC 27）

> 说明：`x64/`、`Debug/`、`.vs/` 等编译产物不会上传（已在 `.gitignore` 忽略）。

## 如何在 Visual Studio 中运行 ▶️

1. 用 Visual Studio 打开 `homework.slnx`
2. 在“解决方案资源管理器”里右键某个项目 → **设为启动项目**
3. 按 `F5`（调试运行）或 `Ctrl + F5`（不调试运行）

## Git 常用命令（我自己用）🧰

```bash
git add .
git commit -m "update"
git push
