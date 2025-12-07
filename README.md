# LaTeX-in-ICM-MCM

> **个人收藏仓库** - 本仓库为美赛/数学建模 LaTeX 模板收集整理，来源于网络和个人使用经验，仅供学习参考。

数学建模过程中使用的 LaTeX 模板以及一些常见问题解决方案。

## 免责声明

- 本仓库代码/模板来源于网络收集和个人整理
- **不保证模板的完整性、准确性和可用性**
- **不保证符合任何比赛的官方格式要求**
- 使用本仓库内容造成的任何问题（包括但不限于格式错误、编译失败、比赛违规等），作者不承担任何责任
- 使用前请自行验证模板是否符合比赛要求
- 如有侵权请联系删除

## 目录结构

```
LaTeX-in-ICM-MCM/
├── Latex模板/              # 完整排版示例（含较多文字内容）
│   ├── easymcm.sty         # easyMCM 模板样式文件
│   ├── main.tex            # 主文件
│   ├── main.pdf            # 编译输出 PDF
│   ├── part_1_pre.tex      # 第一部分：摘要、问题重述等
│   ├── part_2_model.tex    # 第二部分：模型建立
│   ├── part_3_Conclusion.tex # 第三部分：结论
│   ├── part_4_appendix.tex # 第四部分：附录
│   ├── new_command.tex     # 自定义命令
│   ├── img/                # 图片资源
│   ├── test/               # 测试文件（非正式）
│   └── _minted-main/       # minted 代码高亮缓存
│
├── temple/                 # 简洁模板（推荐使用）
│   ├── easymcm.sty         # easyMCM 模板样式文件
│   ├── main.tex            # 主文件
│   ├── main.pdf            # 编译输出 PDF
│   ├── part_1_pre.tex      # 第一部分
│   ├── part_2_model.tex    # 第二部分
│   ├── part_3_conclusion.tex # 第三部分
│   ├── part_4_Appendix.tex # 第四部分
│   ├── new_command.tex     # 自定义命令
│   └── img/                # 图片资源
│
├── Memos/                  # 其他模板
│   ├── Letter/             # 信件模板
│   └── XJTLU-Poster-Template-main/  # 海报模板
│
└── README.md
```

## 使用说明

### 推荐使用

- **简洁模板**：`temple/` 文件夹，适合快速开始
- **完整示例**：`Latex模板/` 文件夹，有较多排版示例可参考

### 模板基础

使用的整体模板是 easyMCM 模板，在基础模板上进行了改动以及调整，同时收集了部分好用的 LaTeX 代码。

### 注意事项

- 部分宏包（如 `minted`）需要配合环境以及调整代码后使用
- 部分宏包需要联合使用（如 `hyperref` 与 `cleveref`），改动时请斟酌
- `test` 文件仅用于测试使用，非正式模板

## 联系方式

如有模板使用问题请提 Issue。

---

**最后更新**：2025-12-07
