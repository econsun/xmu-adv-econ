# 基本信息

仓库作者：Paul Sun

联系方式：econsunrq@outlook.com

许可证：CC BY-NC-SA 4.0

本仓库用于存放

1. LaTeX 作业模板（英文），使用 `xeLaTeX` 编译

2. 厦门大学经济学科研究生高级经济学课程（八高）作业

如有帮助，欢迎 star；如有问题，欢迎 issue。任何模板使用问题，任何作业问题，都可通过邮箱与我联系。

# 仓库信息

### 仓库结构

```
xmu-adv-econ/
│
├── readme.md         # 说明文件
├── licence           # 许可证文件 (CC BY-NC-SA 4.0)
│
├── _src              # 模板代码
│   ├── 0_main.tex        # 主文件
│   ├── 1_pkg.tex         # 宏包设置
│   ├── 2_tcb.tex         # tcolorbar
│   ├── 3_macro.tex       # 自定义宏
│   └── 4_cover.tex       # 作业封面
│
├── coursename/       # 作业文件
│   ├── crsname-hw-1.pdf  # 第 1 次作业
│   ├── crsname-hw-2.pdf  # 第 2 次作业
│   └── ...               # 其他作业
└── ...               # 其他课程
```

### 获得仓库

**方式一**：以 zip 格式下载仓库

**方式二**：在终端中使用命令克隆仓库

```terminal
git@github.com:econsun/xmu-adv-econ.git
```

# 模板信息

本模板以简洁实用为设计理念，使用 Palatino 风格字体，尽可能对代码详细注释，帮助使用。

- 已完成功能：目录、页眉、列表、数学、图片、链接、引用、注脚、参考文献、自定义环境

- 计划中功能：表格、中文支持