进制转换器

https://img.shields.io/badge/Python-3.6+-blue.svg
https://img.shields.io/badge/License-MIT-green.svg
https://img.shields.io/badge/Author-XiaoYao-orange.svg
https://img.shields.io/badge/Organization-Alfadi联盟-purple.svg

一个简单易用的进制转换工具，支持二进制、八进制、十进制和十六进制之间的相互转换。

✨ 功能特点

· 🔄 全面转换：支持二进制、八进制、十进制、十六进制之间的所有组合转换
· 🎯 用户友好：简洁的命令行交互界面，操作简单直观
· 🛡️ 错误处理：完善的输入验证和错误提示机制
· 📝 清晰输出：转换结果格式清晰，易于阅读
· 🐍 纯Python：无需额外依赖，开箱即用

📋 支持的转换类型

源进制 目标进制 支持情况
二进制 八进制 ✅
二进制 十进制 ✅
二进制 十六进制 ✅
八进制 二进制 ✅
八进制 十进制 ✅
八进制 十六进制 ✅
十进制 二进制 ✅
十进制 八进制 ✅
十进制 十六进制 ✅
十六进制 二进制 ✅
十六进制 八进制 ✅
十六进制 十进制 ✅

🚀 快速开始

环境要求

· Python 3.6 或更高版本

使用方法

1. 克隆仓库
   ```bash
   git clone https://github.com/XiaoYao/base-converter.git
   cd base-converter
   ```
2. 运行程序
   ```bash
   python base_converter.py
   ```
3. 按照提示操作
   ```
   ==================================================
   进制转换器
   作者: XiaoYao
   组织: Alfadi联盟
   ==================================================
   
   请选择源进制:
   1. 二进制
   2. 八进制
   3. 十进制
   4. 十六进制
   5. 退出
   
   请输入选择 (1-5): 1
   请选择目标进制 (1-4): 3
   请输入要转换的数字 (基数为2): 1010
   转换结果: 10
   ```

📖 使用示例

二进制转十进制

```
输入: 1010 (二进制)
输出: 10 (十进制)
```

十六进制转二进制

```
输入: A1F (十六进制)
输出: 101000011111 (二进制)
```

十进制转八进制

```
输入: 255 (十进制)
输出: 377 (八进制)
```

🛠️ 核心函数

```python
# 二进制转十进制
binary_to_decimal("1010")  # 返回: 10

# 十进制转十六进制
decimal_to_hexadecimal(255)  # 返回: "FF"

# 通用转换函数
convert_number("A1", 16, 2)  # 十六进制"A1"转二进制
```

📁 项目结构

```
base-converter/
│
├── base_converter.py    # 主程序文件
├── README.md           # 项目说明文档
```

👥 贡献者

· XiaoYao - 项目作者 & 主要开发者

组织

· Alfadi联盟

📄 许可证

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。

🤝 贡献指南

我们欢迎各种形式的贡献！请参考以下步骤：

1. Fork 本仓库
2. 创建功能分支 (git checkout -b feature/AmazingFeature)
3. 提交更改 (git commit -m 'Add some AmazingFeature')
4. 推送到分支 (git push origin feature/AmazingFeature)
5. 开启 Pull Request

🐛 问题反馈

如果您遇到任何问题或有改进建议，请通过 GitHub Issues 提交。

📞 联系我们

· 作者: XiaoYao
· 组织: Alfadi联盟
· 邮箱: ADAxyao@gmail.com
