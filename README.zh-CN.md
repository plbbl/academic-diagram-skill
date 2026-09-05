<div align="center">

<h1>Academic Diagram</h1>
<h3>文字做减法，结构更清楚，图值得展示。</h3>

<p>一个精简的科研架构图／机制示意图 skill。<br>先理解论文，再看真实参考，用可编辑对象画，反复看图精修。</p>

<p><a href="README.md">English</a> · <strong>简体中文</strong></p>

<p>
  <img src="https://img.shields.io/badge/Showcase-6_figures-D2E5DF?style=flat-square&amp;labelColor=34444D" alt="Six showcase figures">
  <img src="https://img.shields.io/badge/Editable-draw.io_%2B_SVG-D9E6F1?style=flat-square&amp;labelColor=34444D" alt="Editable draw.io and SVG">
  <img src="https://img.shields.io/badge/References-30_figures-EEDAA2?style=flat-square&amp;labelColor=34444D" alt="Thirty reference figures">
</p>

<p><a href="#案例画廊">看案例</a> · <a href="#快速开始">开始使用</a> · <a href="examples/academic-diagram-showcase.pdf">展示 PDF</a> · <a href="SKILL.md">阅读 Skill</a></p>

</div>

---

## 案例画廊

**下面六张，都是用这个 skill 做的。** 基于公开论文方法与原图参考重新设计，不是作者原图、无记忆盲测或实验复现。token、波形、特征色块均为概念示意。[来源与简化说明 →](examples/README.md)

### 01 / MaskGCT · 语音生成

两个生成阶段，一份参考语音。从文本到声音，主线清楚。

<a href="examples/figures/02-maskgct.png"><img src="examples/figures/02-maskgct.png" width="100%" alt="MaskGCT: 两个生成阶段，一份参考语音。从文本到声音，主线清楚。"></a>

[PNG](examples/figures/02-maskgct.png) · [SVG](examples/figures/02-maskgct.drawio.svg) · [draw.io 源文件](examples/figures/02-maskgct.drawio) · [原论文 · ICLR 2025](https://proceedings.iclr.cc/paper_files/paper/2025/hash/74a31a3b862eb7f01defbbed8e5f0c69-Abstract-Conference.html)

---

### 02 / Janus · 多模态架构

分开的视觉编码器，共享的自回归模型，清晰的任务分工。

<a href="examples/figures/05-janus.png"><img src="examples/figures/05-janus.png" width="100%" alt="Janus: 分开的视觉编码器，共享的自回归模型，清晰的任务分工。"></a>

[PNG](examples/figures/05-janus.png) · [SVG](examples/figures/05-janus.drawio.svg) · [draw.io 源文件](examples/figures/05-janus.drawio) · [原论文 · CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/html/Wu_Janus_Decoupling_Visual_Encoding_for_Unified_Multimodal_Understanding_and_Generation_CVPR_2025_paper.html)

<sub>两条视觉路线对应不同任务，不是同时输入。生成侧编码器提供训练图像码；文生图推理从文本开始。</sub>

---

### 03 / CUT3R · 持久三维状态

读取当前图像，更新已有状态。用两条交互支路解释几何预测。

<a href="examples/figures/03-cut3r.png"><img src="examples/figures/03-cut3r.png" width="100%" alt="CUT3R: 读取当前图像，更新已有状态。用两条交互支路解释几何预测。"></a>

[PNG](examples/figures/03-cut3r.png) · [SVG](examples/figures/03-cut3r.drawio.svg) · [draw.io 源文件](examples/figures/03-cut3r.drawio) · [原论文 · CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Continuous_3D_Perception_Model_with_Persistent_State_CVPR_2025_paper.html)

---

### 04 / LoftUp · 特征上采样

坐标形成查询，低分辨率特征提供上下文。用网格与堆叠表达分辨率变化。

<a href="examples/figures/01-loftup.png"><img src="examples/figures/01-loftup.png" width="100%" alt="LoftUp: 坐标形成查询，低分辨率特征提供上下文。用网格与堆叠表达分辨率变化。"></a>

[PNG](examples/figures/01-loftup.png) · [SVG](examples/figures/01-loftup.drawio.svg) · [draw.io 源文件](examples/figures/01-loftup.drawio) · [原论文 · ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/html/Huang_LoftUp_Learning_a_Coordinate-Based_Feature_Upsampler_for_Vision_Foundation_Models_ICCV_2025_paper.html)

---

### 05 / LLaDA · 掩码语言模型

训练时随机遮蔽，采样时并行预测。用少量状态色块讲清两种过程。

<a href="examples/figures/04-llada.png"><img src="examples/figures/04-llada.png" width="100%" alt="LLaDA: 训练时随机遮蔽，采样时并行预测。用少量状态色块讲清两种过程。"></a>

[PNG](examples/figures/04-llada.png) · [SVG](examples/figures/04-llada.drawio.svg) · [draw.io 源文件](examples/figures/04-llada.drawio) · [原论文 · NeurIPS 2025](https://proceedings.neurips.cc/paper_files/paper/2025/hash/48b383b24230e0e6e649d9c98dae4d8c-Abstract-Conference.html)

---

### 06 / Transfusion · 图文统一模型

同一个 Transformer，离散文本与连续图像，两类预测目标。

<a href="examples/figures/06-transfusion.png"><img src="examples/figures/06-transfusion.png" width="100%" alt="Transfusion: 同一个 Transformer，离散文本与连续图像，两类预测目标。"></a>

[PNG](examples/figures/06-transfusion.png) · [SVG](examples/figures/06-transfusion.drawio.svg) · [draw.io 源文件](examples/figures/06-transfusion.drawio) · [原论文 · ICLR 2025](https://proceedings.iclr.cc/paper_files/paper/2025/hash/12678c3948153f4bc391f51e2082bd6e-Abstract-Conference.html)

<sub>这里按模态分组示意，不是逐位置移位后的训练靶标；省略 VAE 和模态适配器。</sub>

---

## 流程的重点

| 先想论文 | 有依据地设计 | 检查真实成图 |
| --- | --- | --- |
| 确认最新成稿与相关工作区，明确读者应该理解什么，不凭美观发明科学结构。 | 短标签、有含义的形状、克制配色、规整组件与留白；真正打开论文参考图学习。 | 逐条追查箭头，在论文尺寸看字体与间距。改源文件、重新导出、再打开复查。 |

主流程只有一个精简的 [SKILL.md](SKILL.md)。不强制图像生成、不规定候选数、不凑固定迭代轮数。专注**架构图、方法流程图与机制示意图**，不接管整篇论文，也不负责实验定量图或定性结果拼图。

## 快速开始

将整个仓库安装为一个 skill 文件夹。以 Codex 为例，目标目录**尚不存在**时执行：

```sh
git clone https://github.com/plbbl/academic-diagram-skill.git ~/.codex/skills/academic-diagram
```

保留 `SKILL.md`、`agents/` 和 `references/` 的相对位置。已有同名目录时先检查，不直接覆盖。重新打开会话后调用：

```text
用 $academic-diagram，根据我提供的论文和最新工作区做一张架构图或机制示意图。
先选合适的美学参考，用可编辑对象画，在隔离目录精修。
打开实际渲染图，检查箭头、字体、组件与留白，并在论文尺寸复查后继续调整。
给我可编辑源文件、SVG/PDF 和 PNG；得到我确认前，不修改正式论文。
```

其他支持本地指令的 agent 也可以直接读取 [SKILL.md](SKILL.md)。画图工具由宿主环境提供，可选 draw.io、PowerPoint、Canva、Illustrator 或直接 SVG。**这是一个 skill，不是自带绘图软件的应用。** 上面的六张案例使用原生 draw.io 对象与 SVG。

**想直接复制一句完整指令？** [领取一键使用提示词 →](GET_STARTED.zh-CN.md) 让 AI 在账号已授权时为仓库点 Star，然后加载 skill、根据你的论文开始画图。Star 自愿，未完成也不影响使用。

## 美学参考图集

独立参考库包含 **30 张论文图、3 张总览**；随附目录涵盖 27 篇标注为 2025–2026 年的论文。它们是**第三方美学参考，不是这个 skill 生成的案例**。先按结构选图，再打开独立原尺寸图片。

[完整出处与选图索引](references/README.md) · [总览 01–10](references/previews/overview-01.jpg) · [总览 11–20](references/previews/overview-02.jpg) · [总览 21–30](references/previews/overview-03.jpg)

## 文件、署名与权利

- [六页展示 PDF](examples/academic-diagram-showcase.pdf)：矢量成图、说明图注、原论文链接。
- [可编辑案例](examples/figures/)：六个 `.drawio`、六张原生文字 SVG、六张 3000 px PNG。
- [案例来源与边界](examples/README.md)：方法归属、简化内容与编辑注意事项。

原创 skill 指令、agent 配置与说明文档采用 [MIT](LICENSE)。这个许可**不自动覆盖展示图与第三方参考图片**；分别见[案例权利说明](examples/README.md#rights)和[第三方声明](THIRD_PARTY_NOTICES.md)。方法属于原作者，收录不代表作者或会议背书。仓库不包含未发表论文、私有工作区或实验数据。

<div align="center">
<br>
<strong>如果它对你有帮助，欢迎点个 Star，让更多研究者看到。</strong><br>
<sub>科学要准确，解释交给图。</sub>
</div>
