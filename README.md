# LaTeX-in-ICM-MCM

> **⚠️ 个人收藏项目** - 本仓库为美赛/数学建模 LaTeX 模板收集整理，来源于网络和个人使用经验，模板质量和文档仅供参考，不保证符合比赛官方要求。

数学建模 LaTeX 模板集合，涵盖 ICM/MCM 美赛论文模板、信件模板、海报模板等。

## 关于本库

### 📚 项目定位

**数学建模 LaTeX 模板收藏库**

这是我个人整理的仓库，收集了数学建模过程中使用的 LaTeX 模板以及一些常见问题解决方案，主要基于 easyMCM 模板进行改动和调整。

### 🎯 适用人群

- 数学建模参赛选手（美赛 ICM/MCM）
- LaTeX 学习者
- 需要学术论文模板的同学

### 📊 库统计

- **模板类型**：3类
  - 🔸 美赛论文模板（easyMCM）
  - 🔸 信件模板
  - 🔸 海报模板
- **示例文档**：完整排版示例 + 简洁模板

### ⚠️ 免责声明

- 本库模板来源于网络收集和个人整理
- 部分模板来自开源社区分享
- **模板质量参差不齐，不保证符合比赛官方格式要求**
- **不保证模板的完整性、准确性和可用性**
- 使用本库模板造成的任何问题（包括但不限于格式错误、编译失败、比赛违规等），作者不承担责任
- 使用前请自行验证模板是否符合比赛要求
- 如有侵权请联系删除

### 📮 联系方式

- GitHub Issue：https://github.com/1077491728/LaTeX-in-ICM-MCM/issues

## 模板列表

### 📄 美赛论文模板

| 模板 | 说明 | 推荐度 | 备注 |
|------|------|--------|------|
| [temple/](./temple) | 简洁模板，适合快速开始 | ⭐⭐⭐ | 推荐使用 |
| [Latex模板/](./Latex模板) | 完整排版示例，含较多文字内容 | ⭐⭐ | 参考用 |

### 📝 其他模板

| 模板 | 说明 | 位置 |
|------|------|------|
| Letter | 信件模板 | [Memos/Letter/](./Memos/Letter) |
| XJTLU Poster | 海报模板 | [Memos/XJTLU-Poster-Template-main/](./Memos/XJTLU-Poster-Template-main) |

## 目录结构

```
LaTeX-in-ICM-MCM/
├── # 📄 美赛论文模板
├── temple/                 # 简洁模板（推荐）
│   ├── easymcm.sty         # easyMCM 样式文件
│   ├── main.tex            # 主文件
│   ├── main.pdf            # 编译输出
│   ├── part_1_pre.tex      # 摘要、问题重述
│   ├── part_2_model.tex    # 模型建立
│   ├── part_3_conclusion.tex # 结论
│   ├── part_4_Appendix.tex # 附录
│   ├── new_command.tex     # 自定义命令
│   └── img/                # 图片资源
│
├── Latex模板/              # 完整示例（参考）
│   ├── easymcm.sty
│   ├── main.tex / main.pdf
│   ├── part_1_pre.tex
│   ├── part_2_model.tex
│   ├── part_3_Conclusion.tex
│   ├── part_4_appendix.tex
│   ├── new_command.tex
│   ├── img/
│   └── test/               # 测试文件（非正式）
│
├── # 📝 其他模板
├── Memos/
│   ├── Letter/             # 信件模板
│   └── XJTLU-Poster-Template-main/  # 海报模板
│
└── README.md
```

## ⚠️ 重要提示

> **本仓库为个人收集整理的模板库，模板质量和文档仅供参考。**
>
> - 模板来源于网络收集和开源社区
> - 质量参差不齐，未经充分验证
> - **不保证符合任何比赛的官方格式要求**
> - 使用前请务必自行验证和测试
> - 部分宏包（如 `minted`）需要配合环境调整后使用
> - 部分宏包需要联合使用（如 `hyperref` 与 `cleveref`），改动时请斟酌
> - 如遇问题请自行调试，作者不承担任何责任

---

**最后更新**：2025-12-07
**模板类型**：3类（美赛论文、信件、海报）
