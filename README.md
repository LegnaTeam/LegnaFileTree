# 文件树生成器

一个基于 Python 和 Tkinter 的图形化文件树生成工具，可以快速创建项目目录结构。

## 功能特性

- 🖼️ 图形化界面操作
- 📁 支持多级目录结构生成
- 📝 支持文件创建
- 🔄 支持强制覆盖选项
- 🖱️ 支持路径浏览选择
- 🖥️ 跨平台支持（Windows/macOS/Linux）
- 🛡️ 路径安全检查
- 📋 示例模板快速生成

## 使用说明

### 界面说明

1. **输入区域**：输入文件树结构，支持以下格式：
   ```
   project/
   ├── src/
   │   ├── main.py
   │   └── utils/
   │       ├── __init__.py
   │       └── file_utils.py
   └── README.md
   ```

2. **输出路径**：
   - 手动输入或通过"浏览..."按钮选择
   - 支持本地路径和网络路径
   - 默认路径：`./output`

3. **生成选项**：
   - 强制覆盖：覆盖已存在的文件/目录
   - 生成示例：快速填充示例文件树结构

### 快速开始

1. 安装依赖：
   ```bash
   pip install tkinter ttkbootstrap
   ```

2. 运行程序：
   ```bash
   python main.py
   ```

3. 使用步骤：
   - 输入文件树结构或点击"生成示例"
   - 选择输出路径
   - 点击"生成文件树"按钮

### 路径支持

- 本地路径：`/path/to/project`
- 相对路径：`./output`
- Windows 网络路径：`\\server\share\project`
- macOS iCloud 路径：`/Users/username/Library/Mobile Documents/...`

## 开发环境

- Python 3.8+
- 依赖库：
  - `tkinter`
  - `ttkbootstrap`

## 许可证

MIT License

## 贡献指南

欢迎提交 Issue 和 Pull Request

## 示例截图

![示例截图](![image](https://github.com/user-attachments/assets/78d8fcdb-b159-4261-9197-bdafca52dc46)
