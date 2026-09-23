# Digital Life Visual / 数字人生视觉 Skill

把真实照片转译成一套统一的“数字人生”视觉语言：**现实摄影仍然是主体，近景逐渐显露 Rhino / SketchUp / CAD 裸模，中景在模型、线框、X-Ray 与渲染之间过渡，远景回到真实摄影；再叠加少量有意义的信息标注、局部故障接缝与克制的海报排版。**

它不是赛博朋克滤镜，也不是游戏 HUD 模板。

## 核心语法

`RAW MODEL → EDGE / WIREFRAME → RENDER → REALITY`

空间越靠近镜头，越像“仍然可以编辑的模型”；越远离镜头，越回到现实。

## 适用

- 城市 / 街头照片的数字孪生式转译
- 建筑、室内、交通、产品的模型与现实叠化
- AR / mixed reality 概念视觉
- “现实正在变成可计算对象”的海报视觉
- Rhino / SketchUp 素模与真实摄影渐变
- 少量技术标注 + 局部 glitch + 编辑式大字

## 不适用

- 传统霓虹赛博朋克
- 全屏游戏 HUD
- 整张图全部 wireframe
- 大量没有信息价值的数字与英文
- 在道路上默认铺 `SCAN / VIRTUAL / REALITY` 等通用口号

## 默认设计原则

1. **原图优先**：构图、视角、透视、场景与主要物体位置尽量保持。
2. **深度控制**：近景模型化最强，中景混合，远景真实。
3. **Rhino / SU 感优先**：近景不是密集网格，而是浅灰素模 + 较粗模型描边 + 少量结构线。
4. **文字必须有意义**：能用地名、建筑名、线路、尺寸、ID，就不要写“未来”“扫描”“虚拟现实”。
5. **大字最多一处**：优先建筑立面、墙面、广告位等真实载体；没有合适内容就不加。
6. **Glitch 是接缝**：只发生在现实与模型互相穿透的位置，而不是套满全图的滤镜。

## 目录

```text
digital-life-visual/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── annotation-language.md
    ├── prompt-blueprint.md
    ├── quality-and-recovery.md
    └── visual-system.md
```

## 安装

安装目录名建议保持为 `digital-life-visual`，与 `SKILL.md` 的 `name` 一致。

### Cursor

用户级：

```text
~/.cursor/skills/digital-life-visual
```

项目级：

```text
.cursor/skills/digital-life-visual
```

### Codex / 通用 Agents

```text
~/.agents/skills/digital-life-visual
```

### Claude Code

```text
~/.claude/skills/digital-life-visual
```

## 调用示例

```text
使用 digital-life-visual 重绘这张照片。保留原图构图，近景车辆做 Rhino/SU 素模化并向远处逐渐恢复真实，只保留少量有信息价值的标注。
```

或者：

```text
Use $digital-life-visual on this image. Keep the scene photographic, make the nearest object a raw CAD model with bold modeling edges, and taper back into reality with minimal semantic annotation.
```

## 几个强约束

- 默认不在道路上放大字。
- 默认不使用 `SCAN / VIRTUAL / REALITY / FUTURE / AI / METAVERSE` 等无信息量的科技词。
- 默认不新增科幻建筑、飞车、机器人、全息广告等原图不存在的内容。
- 用户只要求局部修正时，以最新认可版本为母版，仅修改指定维度。

## 设计目标

最终视觉首先仍是一张真实世界的照片，其次才发现它正在被“模型化”，最后才读到信息层。

它表达的不是“未来城市”，而是：

> **日常现实正在悄悄变成可编辑、可测量、可索引的计算对象。**
