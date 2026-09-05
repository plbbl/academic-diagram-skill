# Six editable diagrams / 六张可编辑示意图

[English home](../README.md) · [中文首页](../README.zh-CN.md) · [Showcase PDF](academic-diagram-showcase.pdf)

These diagrams were created with [academic-diagram](../SKILL.md) from published methods, with access to their original figures as references. They are **reference-guided redesigns**, not blind-test results or the original authors' artwork. No private papers or experimental data were used. The recorded workflow version and source details are in [provenance.json](provenance.json).

这六张是基于公开论文与原图参考的重新设计，不是无记忆盲测、作者原图或实验复现。波形、token 数量、特征颜色与采样状态均为概念示意。

## Methods and scope

| Paper | Read alongside the figure | Deliberate simplifications |
| --- | --- | --- |
| [MaskGCT · ICLR 2025](https://proceedings.iclr.cc/paper_files/paper/2025/hash/74a31a3b862eb7f01defbbed8e5f0c69-Abstract-Conference.html) | §3.2; Figures 1–2 | Both reference conditions are retained. Duration prediction, iterative refinement and the RVQ layer schedule are omitted. |
| [Janus · CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/html/Wu_Janus_Decoupling_Visual_Encoding_for_Unified_Multimodal_Understanding_and_Generation_CVPR_2025_paper.html) | §3.1; Figure 2 | The visual routes are task alternatives, not simultaneous inputs. The generation encoder provides training codes; text-to-image inference starts from text. Adapters are collapsed. |
| [CUT3R · CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Continuous_3D_Perception_Model_with_Persistent_State_CVPR_2025_paper.html) | §3.1; Equations 1–5; Figure 3 | One time step; condensed decoder interactions. Pose token, individual heads and virtual-view queries are omitted. |
| [LoftUp · ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/html/Huang_LoftUp_Learning_a_Coordinate-Based_Feature_Upsampler_for_Vision_Foundation_Models_ICCV_2025_paper.html) | §3; Figure 3 | Coordinate/RGB queries and feature keys/values are retained. Two-stage training is omitted. Colored grids are not measured activations. |
| [LLaDA · NeurIPS 2025](https://proceedings.neurips.cc/paper_files/paper/2025/hash/48b383b24230e0e6e649d9c98dae4d8c-Abstract-Conference.html) | §2.1, 2.2, 2.4; Figure 2 | Gray cells with a dash are masks. Intermediate states do not prescribe a three-step sampler or show an empirical trace. SFT is omitted. |
| [Transfusion · ICLR 2025](https://proceedings.iclr.cc/paper_files/paper/2025/hash/12678c3948153f4bc391f51e2082bd6e-Abstract-Conference.html) | §3; Figures 1, 3, 4 | Text and image prediction objectives are retained. Modalities are grouped schematically, not as exact shifted targets. VAE and adapters are omitted. |

## Files and editing

All six examples have a native `.drawio` file, a `.drawio.svg` and a 3000 px PNG in [figures/](figures/). The [six-page PDF](academic-diagram-showcase.pdf) places each diagram at 184 mm width, with embedded fonts and vector graphics. File prefixes reflect production order, not PDF page order.

- **draw.io:** editable native shapes, text, groups and connectors; waveforms and some geometry use custom vector stencils.
- **SVG:** native paths and text, no embedded bitmap or `foreignObject`. The draw.io model is retained inside the SVG.
- **PNG:** convenient previews, not the editable source.

Connectors have carefully positioned endpoints; moving a component requires checking its arrows again. SVG edits in another editor do not synchronize with the embedded draw.io model. Choose one authoring source. SVG uses Arial, so local font substitution can change layout; use the PDF for stable presentation.

文字、模块、token 与连线都不是一张扁平截图。移动组件后请重新检查箭头；外部编辑 SVG 不会同步其内嵌 draw.io 模型。跨机器展示优先用 PDF。

## Review performed

Rendered figures were inspected against individual source figures, then checked at paper width. Revisions addressed label wrapping, arrow clearance, crowded headings and excess whitespace. All final PDF pages were reopened after export. The final SVGs contain 73 native text labels in total and no raster images; the PDF contains no raster figures. These checks document the delivered files, not a guarantee that every future run will achieve the same quality.

## Rights

The methods and paper identities belong to the cited authors. These are newly drawn explanatory representations, not a claim of authorship of the underlying research, author approval, or conference endorsement. Third-party paper screenshots are not duplicated in this examples directory.

The repository's MIT license is scoped to original instructions, configuration and documentation; it does not automatically license these visual assets. No additional blanket artwork license is asserted here. Check applicable rights before republishing or commercially reusing the examples. The separate reference atlas has its own [third-party notices](../THIRD_PARTY_NOTICES.md).

MIT 的现有范围不自动覆盖这些展示图；这里不另行宣称统一图片授权。方法归原作者，公开展示不代表原作者或会议背书，转载或商用前请核查相应权利。
