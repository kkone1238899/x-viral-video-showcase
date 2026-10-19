# X 病毒视频合集

> 缺灵感不知道拍什么？这个库收集 X 上病毒式传播视频的 prompt 合集，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of viral video prompt collections from X prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-18. Continuously updated.

## 条目

### Veo3/即梦/可灵/海螺/豆包视频提示词精选（songguoxs）

**核心提炼**
- 解决什么问题：想找直接能抄的 Veo3 / 即梦 / 可灵 / 海螺 / 豆包 prompt 案例，而不是听理论。
- 核心用法（3 步）：1) 按案例目录挑（50 个案例，覆盖开箱 / ASMR / 产品广告 / 乐高 / 动漫战斗 / 变装等热门玩法）；2) 每个案例带完整提示词，直接复制替换主体；3) 同一个创意按需改模型跑，看哪个模型成片效果最好。
- 什么时候用 / 常见坑：缺灵感、想快速复刻当下流行玩法时来翻；案例跨多个模型，跑前先确认目标模型的写法差异（Veo3 与可灵同一 prompt 成片质感不同）。

**适用场景**：缺灵感、想快速出片的创作者；做案例拆解的内容博主。

**怎么用它搞钱**：提示词教学 / 商单（快速复刻爆款玩法）。

**来源**：[songguoxs/awesome-video-prompts](https://github.com/songguoxs/awesome-video-prompts) · ⭐589 · 更新于 2026-10-15（经 GitHub API 核验）

### MiniMax H3 14 种电影级运镜（loopforge0）

**核心提炼**
- 解决什么问题：MiniMax H3 只有 12 个官方运镜原语，没有"Dolly Zoom"这类现成的复合镜头名，大部分拼法写出来运镜根本不生效。
- 核心用法（3 步）：1) 看在线画廊 loopforge.cc/projects/h3-camera-shots/，每个镜头旁边就是生成它的确切 prompt（运镜和镜头短语高亮标注），clip / prompt / 角色参考板 / ComfyUI 工作流都可下载；2) 装成 agent skill（`.claude/skills/` 目录，复制到用户 skills 目录全局可用），直接让 agent 按镜头名写 prompt；3) 不用 agent 时跑 `python scripts/build_prompt.py <镜头名> --scene my-scene.json` 拼 prompt，人物 / 动物 / 物体按 subject 分槽适配。
- 什么时候用 / 常见坑：想让 AI 短片运镜有电影感时直接套这 14 个验证过的配方；H3 渲染至少 20 步、124 帧起步（4 步 turbo 渲染会压死运镜）；子弹时间被证实做不出来（仓库里有失败报告），别再烧钱试。

**适用场景**：用 MiniMax H3 做短片 / 广告 / TVC 的创作者、agent 工作流玩家。

**怎么用它搞钱**：运镜教学 / AI 短片商单（电影级运镜是差异化卖点）。

**来源**：[loopforge0/minimaxh3-shots-skills](https://github.com/loopforge0/minimaxh3-shots-skills) · ⭐11 · 更新于 2026-10-15 · X 推荐帖 [@egguy7](https://x.com/egguy7/status/2111677222579040486)

### Higgsfield 两部 AI 电影全套提示词资产库

**核心提炼**
- 解决什么问题：长片级 AI 电影的完整提示词和资产库极少公开，这个是真金白银烧出来的实战教材。
- 核心用法（3 步）：1) 《HELL GRIND》：95 分钟、50 万美元成本、Seedance 2.0 制作、曾在戛纳展映；2) 《Cully Hill Boys》：110 分钟、200 万美元成本、Seedance 2.5 制作、人物为真实博主肖像；3) 按片拆解长片连续性管理、人物一致性、成本结构，当实操教材逐镜看。
- 什么时候用 / 常见坑：想做 AI 长片 / 系列短剧、研究"AI 电影到底烧多少钱、怎么管连续性"时看；资产含真实博主肖像，商用注意肖像权。

**适用场景**：AI 短剧 / 长片创作者、想研究 AI 电影工业化流程的人。

**怎么用它搞钱**：AI 短剧实战教学 / 拉片拆解内容 / 长片项目投融资参考。

**来源**：Higgsfield 官方资产库（higgsfield.ai）· X 首发 [@xingjia520](https://x.com/xingjia520/status/2111448610525327544)

### Awesome MiniMax H3 Prompts

**核心提炼**
- 解决什么问题：MiniMax H3 新模型缺少 prompt 教程，想蹭新模型红利但缺案例参考。
- 核心用法（3 步）：1) 按用例分类浏览（剧情片 / 动作奇幻 / 广告产品 / 音乐表演 / vlog 社交）；2) 每个条目带可播放的 WebM 示例 + 完整 prompt + X 原帖来源，看完效果再复制；3) 复制 prompt 替换主体，用 MiniMax H3 生成。
- 什么时候用 / 常见坑：想做新模型差异化内容、避开 Seedance 内卷时用；冷门新模型参数变化快，照搬前先看官方最新文档。

**适用场景**：追新模型的创作者、想做差异化内容的人。

**怎么用它搞钱**：新模型 prompt 教学 / 商单（差异化卖点）。

**来源**：[BeatAPI/awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts) · ⭐196 · 更新于 2026-10-16

### BFL Skills（FLUX 官方）

**核心提炼**
- 解决什么问题：FLUX 3 视频模型的官方 prompt 写法没人整理，自己摸索烧钱。
- 核心用法（3 步）：1) `npx skills add black-forest-labs/skills` 装全套；2) 按需装分科：flux-3-video（视频路由）、flux-image-best-practices（生图）、bfl-api（API 对接）；3) 把需求告诉 coding agent，它按官方 skill 写 prompt 并走 BFL API 生成。
- 什么时候用 / 常见坑：用 FLUX 做视频 / 生图商单时装；官方出品，跟版本最紧；走 BFL API 按量付费。

**适用场景**：FLUX 用户、agent 工作流玩家。

**怎么用它搞钱**：FLUX 视频商单 / agent 工作流教学。

**来源**：[black-forest-labs/skills](https://github.com/black-forest-labs/skills) · ⭐130 · 更新于 2026-10-16

### Awesome Seedance 2.0（ZeroLu）

**核心提炼**
- 解决什么问题：想找"验证过真能用"的 Seedance 2.0 prompt，而不是营销号瞎编的。
- 核心用法（3 步）：1) 按分类浏览（电影感 / 广告 / 社媒 meme / UGC / 动漫 / 短剧 / 特效）；2) 每个条目带完整 prompt + 生成视频 + X 原帖来源，看到效果再拿；3) 复制 prompt 替换主体 / 场景，直接生成；4) 进 API / 工作流资源区学高级玩法。
- 什么时候用 / 常见坑：缺灵感、想复刻某种风格时来翻；条目多是 2.0 写法，2.5 新特性另看对应库。

**适用场景**：Seedance 创作者、做案例拆解的内容博主。

**怎么用它搞钱**：提示词教学 / 商单。

**来源**：[ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) · ⭐2731 · 更新于 2026-10-18

### Awesome Seedance 2.0 Video Prompts（YouMind）

**核心提炼**
- 解决什么问题：Seedance prompt 样本太少，想按题材 / 风格批量找灵感。
- 核心用法（3 步）：1) 去 youmind.com 在线画廊搜（支持模糊搜索和 AI 推荐，比 README 好翻）；2) 按分类挑 prompt（电影 / 动漫 / UGC / 广告 / meme，2000+ 条）；3) 复制微调后生成；4) 看角色一致性技巧和 API 指南进阶。
- 什么时候用 / 常见坑：批量生产时从这里批量取灵感；在在线画廊找体验更好，GitHub README 只当备份。

**适用场景**：矩阵号 / 批量出片的团队、广告商单创作者。

**怎么用它搞钱**：提示词教学 / 商单。

**来源**：[YouMind-OpenLab/awesome-seedance-2-prompts](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts) · ⭐2149 · 更新于 2026-10-18

### Awesome Seedance（LearnPrompt）

**核心提炼**
- 解决什么问题：网上 prompt 案例真假难辨——这个库每个案例都溯源到原帖，还做跨模型复测给"验货报告"。
- 核心用法（5 步）：1) 新手走 Start Here：挑模板 → 复制 → 替换括号 → 丢给 AI chat → 粘贴到 Seedance；2) 直接套 27 个分类模板（UGC / 产品广告 / 时尚 / 美食……）；3) 想验证时看跨模型复测区；4) 装 80 个 AI 视频 skills，让 agent 按案例结构写 prompt。
- 什么时候用 / 常见坑：零基础第一站；模板是英文，替换括号内容时用中文描述也行（AI chat 会转成英文）。

**适用场景**：纯新手、想学"为什么这样写"的学习者。

**怎么用它搞钱**：提示词教学 / 商单。

**来源**：[LearnPrompt/awesome-seedance](https://github.com/LearnPrompt/awesome-seedance) · ⭐2122 · 更新于 2026-10-18

### Motion Prompt 动效/运镜/UI 提示词查询库（showheyohtaki）

**核心提炼**
- 解决什么问题：想让 AI 做某个动效、运镜或 UI 组件，却不知道它叫什么、怎么写 prompt——这个库把名称、动态示例和提问句式整理成 120 条可查条目。
- 核心用法（3 步）：1) 按 5 组翻查（运动图形 motion / 运镜 camera / UI 组件 ui / 落地页效果 lp / 照片质感与布光 photo，每组 24 条）；2) 每条带动态示例和提问句式，先看动效长什么样、再照着句式向 AI 提问；3) 复制条目描述贴进视频生成工具，精准指定动效与运镜。
- 什么时候用 / 常见坑：做 AI 动画 / 短视频需要精准动效描述时查；运镜类条目可直接写进文生视频 prompt 的 camera 段。

**适用场景**：AI 动画 / 短视频创作者、动效设计师；提示词教学者可当词典。

**怎么用它搞钱**：动效提示词教学 / AI 动画商单（精准动效是成片质感的差异化）。

**来源**：[showheyohtaki/motion-prompt](https://github.com/showheyohtaki/motion-prompt) · ⭐411 · 更新于 2026-10-19（经 GitHub API 核验）· X 推荐帖 [@QingQ77](https://x.com/QingQ77/status/2111970331606847623)

### Claude Opus 5.5 代码生成视频四库导航（@czzzzzzJ_ 推荐）

**核心提炼**
- 解决什么问题：Claude Opus 5.5 能纯靠写代码（HTML / Canvas / SVG / Three.js）生成视频、不用任何视频模型，但网上案例散、写法散——这条导航一次给齐从"跟做"到"拆工程"的四个开源仓。
- 核心用法（4 库分工）：1) joeseesun/opus-video-prompts（约 54 个可复制案例，中文友好）——新手先从这里啃，复制提示词直接跑；2) lemomo-ai/lemo-opuscar（51 种影片风格提示词 + 纯代码样片 + 导演与技术指南）——填自己的故事，让 AI 按风格导短片；3) yihui-dev/awesome-opus5-5-videos（病毒视频成片合集，附创作者原始 Prompt，原片与复刻对照看）——学写法；4) JohnHeibel/PDoomVideo（完整 MV 工程：源码 / 分镜 / 渲染）——想研究复杂动画时拆它的工程。
- 什么时候用 / 常见坑：想零视频模型成本做动画 / 短片时走这条线；PDoomVideo 与 opus-video-prompts 暂无 LICENSE 声明，商用前先确认授权。

**适用场景**：想学"代码生成视频"新范式的创作者、Claude Code / agent 工作流玩家。

**怎么用它搞钱**：代码生成视频教学 / AI 动画商单（零模型成本是报价优势）。

**来源**：X 推荐帖 [@czzzzzzJ_](https://x.com/czzzzzzJ_/status/2112085934267346976)（麦当mdldm，蓝V，2026-10-19 发布）· 仓库 [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) ⭐3544（MIT，2026-10-19 更新） / [yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) ⭐6464（MIT） / [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) ⭐2223 / [joeseesun/opus-video-prompts](https://github.com/joeseesun/opus-video-prompts) ⭐426（star 均 2026-10-19 经 GitHub API 核验）

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- 每条格式：核心提炼（解决什么问题 / 核心用法 / 什么时候用）+ 适用场景 + 一条「怎么用它搞钱」
- Star 数为各条目入库当日经 GitHub API 核验（见各条来源行）；持续收录中
- 去重：同一项目只收录一次，不堆 raw 链接

## 相关分类

- 总索引：[x-viral-video-skills](https://github.com/kkone1238899/x-viral-video-skills) —— 13 个分类导航
- [x-viral-video-scripts](https://github.com/kkone1238899/x-viral-video-scripts) —— 编剧 / 脚本
- [x-viral-video-hooks](https://github.com/kkone1238899/x-viral-video-hooks) —— 标题 / 5 秒钩子
- [x-viral-video-creative-direction](https://github.com/kkone1238899/x-viral-video-creative-direction) —— 创意总监
- [x-viral-video-directing](https://github.com/kkone1238899/x-viral-video-directing) —— 导演
- [x-viral-video-replication](https://github.com/kkone1238899/x-viral-video-replication) —— 复制爆款
- [x-viral-video-breakdown](https://github.com/kkone1238899/x-viral-video-breakdown) —— 拉片
- [x-viral-video-pipeline](https://github.com/kkone1238899/x-viral-video-pipeline) —— 流水线 / 生产管线
- [x-viral-video-de-ai](https://github.com/kkone1238899/x-viral-video-de-ai) —— 去 AI 味
- [x-viral-video-characters](https://github.com/kkone1238899/x-viral-video-characters) —— 人物构建
- [x-viral-video-editing](https://github.com/kkone1238899/x-viral-video-editing) —— 视听剪辑技巧
- [x-viral-video-prompt-opt](https://github.com/kkone1238899/x-viral-video-prompt-opt) —— 提示词优化
- [x-viral-video-copywriting](https://github.com/kkone1238899/x-viral-video-copywriting) —— 文案

## 投稿

发现好的X 病毒视频合集 prompt / skill，欢迎提 Issue 或 PR（格式见 CONTRIBUTING.md）。

## 更新日志

- 2026-10-19：晚档搜集新增 1 条（Claude Opus 5.5 代码生成视频四库导航，经 @czzzzzzJ_ 帖推荐，4 仓库 star 均当日 API 核验），共 10 个项目
- 2026-10-19：早档搜集新增 1 条（Motion Prompt 动效/运镜/UI 提示词查询库 showheyohtaki/motion-prompt，120 条目，经 @QingQ77 帖推荐，⭐411 今日更新），GitHub 关键词无新命中，共 9 个项目
- 2026-10-18：早档搜集新增 1 条（Veo3/即梦/可灵/海螺/豆包视频提示词精选 songguoxs/awesome-video-prompts，50 案例），X 侧 0 新增，共 8 个项目
- 2026-10-18：午档搜集新增 2 条（MiniMax H3 14 种电影级运镜 prompt 合集 loopforge0/minimaxh3-shots-skills、Higgsfield 两部 AI 电影《HELL GRIND》/《Cully Hill Boys》全套提示词资产库），老 5 条 star 全量复核更新，共 7 个项目
- 2026-10-12：条目升级为小节格式（核心提炼 / 适用场景 / 搞钱 / 来源），新增 MiniMax H3、FLUX 官方 skills 两个新品类项目，共 5 个项目
- 2026-10-11：首版，3 个项目，持续收录中
