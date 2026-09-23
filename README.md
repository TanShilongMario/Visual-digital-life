# Digital Life Visual / 数字人生视觉 Skill

把真实照片转译成一套统一但可变强度的“数字人生”视觉语言。

核心仍然是：

RAW MODEL → EDGE / WIREFRAME → RENDER → REALITY

但新版不再把界面限制为克制的工业标注。它现在支持两种强度，并可自动混合：

- Editorial / Instrument：更像建筑、工业设计与信息图。
- First-person / Immersive：更像第一人称 AR 游戏界面，有任务列表、空间导航、小地图、状态模块、扫描框和更明显的虚拟层。

整体目标不是把照片变成传统赛博朋克，而是让现实看起来正在被建模、索引、导航和实时计算。

## 新版重点

1. 不再默认在角落放“数字人生 / DIGITAL LIFE”标题。
2. 角落 UI 优先变成与图像内容相关的任务 / Objective 列表。
3. 可以加入虚拟小地图、局部雷达或空间导航，但只在场景具备空间逻辑时使用。
4. UI 字体整体更大、更可读，避免微型文字糊成噪声。
5. 重要引线更粗，普通辅助线更细，形成明确线宽层级。
6. 大字不再只限于建筑立面，可以贴合桌面、墙面、地面、产品平面、交通工具等真实透视载体。
7. 大字可以做成 AR 投影：轻微离面、投影阴影、发光边缘、RGB 偏移、故障撕裂和短暂运动残影。
8. 支持高端第一人称科幻游戏 UI 的“感觉”，例如任务层级、导航、准星、状态模块和空间覆盖，但不复制任何具体游戏的现成界面、Logo 或专有图标。

## 核心视觉结构

近景：
- Rhino / SketchUp / CAD 裸模
- 浅灰素模
- 粗轮廓 / 特征边
- 少量线框与 X-Ray
- 最强数字化

中景：
- 模型、线框、材质与现实连续过渡
- 少量对象识别与状态标记

远景：
- 基本保持摄影真实
- 只留下少量 UI 锚点或数字痕迹

## First-person 模式

当用户要求更强“虚拟感 / 数字感 / 游戏感 / AR 眼镜感”时，优先使用：

- 2–4 条场景化任务
- 一个高亮 Active Task
- 一个角落小地图
- 1–2 个状态模块
- 少量准星 / Scan Bracket
- 3–6 条较粗主引线
- 一处具有透视与悬浮感的大字
- 局部 glitch / motion ghosting

界面应该像真的在“理解这个场景”，而不是在照片上铺一层装饰。

## 文字原则

不再绝对禁止 SCAN / ANALYZE / IDENTIFY 等词。

它们只有在“具体任务”里才成立，例如：

- SCAN HK MILK TEA
- IDENTIFY STRAW / ICE / GLASS
- ROUTE TO EXIT B
- INSPECT VEHICLE 07

仍然避免没有语义的：

- FUTURE
- METAVERSE
- DIGITAL CITY
- SYSTEM ONLINE
- VIRTUAL FUTURE

## 大字原则

大字是一层“海报 + AR 投影”。

它必须：

- 遵循真实透视
- 有明确承载平面
- 与场景内容有关
- 轻微悬浮
- 有接触阴影或投影
- 有少量 glitch / RGB split
- 可以带短暂运动拖影

这样看起来不是印刷在照片上，而是由 AR 系统实时生成并贴合现实空间。

## 目录

digital-life-visual/
  SKILL.md
  README.md
  agents/
    openai.yaml
  references/
    annotation-language.md
    first-person-ui.md
    prompt-blueprint.md
    quality-and-recovery.md
    visual-system.md

## 安装

Cursor 用户级：

~/.cursor/skills/digital-life-visual

Cursor 项目级：

.cursor/skills/digital-life-visual

Codex / 通用 Agents：

~/.agents/skills/digital-life-visual

Claude Code：

~/.claude/skills/digital-life-visual

## 调用示例

更克制：

使用 digital-life-visual 重绘这张照片。保留原图构图，近景做 Rhino/SU 素模化，向远景逐渐恢复真实，只保留少量有意义的标注。

更沉浸：

使用 digital-life-visual 的 first-person 模式。保留原图，把近景主体变成可编辑 CAD / wireframe 混合体，增加场景化任务列表、角落小地图、少量状态模块和一处贴合透视的大字。UI 要像高端第一人称科幻游戏，但保持原创，避免模板化。

## 设计目标

最终视觉应该同时具备三层阅读：

1. 先看到真实世界。
2. 再发现现实正在变成模型。
3. 最后意识到一个不可见的系统正在理解、导航和编辑这个世界。

数字人生不是“未来世界”。

它是“现实世界开始拥有操作系统”。
