# X 病毒视频合集

> 缺灵感不知道拍什么？这个库收集 X 上病毒式传播视频的 prompt 合集，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of viral video prompt collections from X prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-11-14. Continuously updated.

## 条目

### Veo3/即梦/可灵/海螺/豆包视频提示词精选（songguoxs）

**核心提炼**
- 解决什么问题：想找直接能抄的 Veo3 / 即梦 / 可灵 / 海螺 / 豆包 prompt 案例，而不是听理论。
- 核心用法（3 步）：1) 按案例目录挑（50 个案例，覆盖开箱 / ASMR / 产品广告 / 乐高 / 动漫战斗 / 变装等热门玩法）；2) 每个案例带完整提示词，直接复制替换主体；3) 同一个创意按需改模型跑，看哪个模型成片效果最好。
- 什么时候用 / 常见坑：缺灵感、想快速复刻当下流行玩法时来翻；案例跨多个模型，跑前先确认目标模型的写法差异（Veo3 与可灵同一 prompt 成片质感不同）。

**适用场景**：缺灵感、想快速出片的创作者；做案例拆解的内容博主。

**怎么用它搞钱**：提示词教学 / 商单（快速复刻爆款玩法）。

**来源**：[songguoxs/awesome-video-prompts](https://github.com/songguoxs/awesome-video-prompts) · ⭐600 · 更新于 2026-11-13（经 GitHub API 核验）

### MiniMax H3 14 种电影级运镜（loopforge0）

**核心提炼**
- 解决什么问题：MiniMax H3 只有 12 个官方运镜原语，没有"Dolly Zoom"这类现成的复合镜头名，大部分拼法写出来运镜根本不生效。
- 核心用法（3 步）：1) 看在线画廊 loopforge.cc/projects/h3-camera-shots/，每个镜头旁边就是生成它的确切 prompt（运镜和镜头短语高亮标注），clip / prompt / 角色参考板 / ComfyUI 工作流都可下载；2) 装成 agent skill（`.claude/skills/` 目录，复制到用户 skills 目录全局可用），直接让 agent 按镜头名写 prompt；3) 不用 agent 时跑 `python scripts/build_prompt.py <镜头名> --scene my-scene.json` 拼 prompt，人物 / 动物 / 物体按 subject 分槽适配。
- 什么时候用 / 常见坑：想让 AI 短片运镜有电影感时直接套这 14 个验证过的配方；H3 渲染至少 20 步、124 帧起步（4 步 turbo 渲染会压死运镜）；子弹时间被证实做不出来（仓库里有失败报告），别再烧钱试。

**适用场景**：用 MiniMax H3 做短片 / 广告 / TVC 的创作者、agent 工作流玩家。

**怎么用它搞钱**：运镜教学 / AI 短片商单（电影级运镜是差异化卖点）。

**来源**：[loopforge0/minimaxh3-shots-skills](https://github.com/loopforge0/minimaxh3-shots-skills) · ⭐19 · 更新于 2026-11-13 · X 推荐帖 [@egguy7](https://x.com/egguy7/status/2111677222579040486)

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

**来源**：[BeatAPI/awesome-minimax-h3-prompts](https://github.com/BeatAPI/awesome-minimax-h3-prompts) · ⭐216 · 更新于 2026-11-13

### BFL Skills（FLUX 官方）

**核心提炼**
- 解决什么问题：FLUX 3 视频模型的官方 prompt 写法没人整理，自己摸索烧钱。
- 核心用法（3 步）：1) `npx skills add black-forest-labs/skills` 装全套；2) 按需装分科：flux-3-video（视频路由）、flux-image-best-practices（生图）、bfl-api（API 对接）；3) 把需求告诉 coding agent，它按官方 skill 写 prompt 并走 BFL API 生成。
- 什么时候用 / 常见坑：用 FLUX 做视频 / 生图商单时装；官方出品，跟版本最紧；走 BFL API 按量付费。

**适用场景**：FLUX 用户、agent 工作流玩家。

**怎么用它搞钱**：FLUX 视频商单 / agent 工作流教学。

**来源**：[black-forest-labs/skills](https://github.com/black-forest-labs/skills) · ⭐137 · 更新于 2026-11-05

### Awesome Seedance 2.0（ZeroLu）

**核心提炼**
- 解决什么问题：想找"验证过真能用"的 Seedance 2.0 prompt，而不是营销号瞎编的。
- 核心用法（3 步）：1) 按分类浏览（电影感 / 广告 / 社媒 meme / UGC / 动漫 / 短剧 / 特效）；2) 每个条目带完整 prompt + 生成视频 + X 原帖来源，看到效果再拿；3) 复制 prompt 替换主体 / 场景，直接生成；4) 进 API / 工作流资源区学高级玩法。
- 什么时候用 / 常见坑：缺灵感、想复刻某种风格时来翻；条目多是 2.0 写法，2.5 新特性另看对应库。

**适用场景**：Seedance 创作者、做案例拆解的内容博主。

**怎么用它搞钱**：提示词教学 / 商单。

**来源**：[ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) · ⭐2842 · 更新于 2026-11-13

### Awesome Seedance 2.0 Video Prompts（YouMind）

**核心提炼**
- 解决什么问题：Seedance prompt 样本太少，想按题材 / 风格批量找灵感。
- 核心用法（3 步）：1) 去 youmind.com 在线画廊搜（支持模糊搜索和 AI 推荐，比 README 好翻）；2) 按分类挑 prompt（电影 / 动漫 / UGC / 广告 / meme，2000+ 条）；3) 复制微调后生成；4) 看角色一致性技巧和 API 指南进阶。
- 什么时候用 / 常见坑：批量生产时从这里批量取灵感；在在线画廊找体验更好，GitHub README 只当备份。

**适用场景**：矩阵号 / 批量出片的团队、广告商单创作者。

**怎么用它搞钱**：提示词教学 / 商单。

**来源**：[YouMind-OpenLab/awesome-seedance-2-prompts](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts) · ⭐2219 · 更新于 2026-11-13

### Awesome Seedance（LearnPrompt）

**核心提炼**
- 解决什么问题：网上 prompt 案例真假难辨——这个库每个案例都溯源到原帖，还做跨模型复测给"验货报告"。
- 核心用法（5 步）：1) 新手走 Start Here：挑模板 → 复制 → 替换括号 → 丢给 AI chat → 粘贴到 Seedance；2) 直接套 27 个分类模板（UGC / 产品广告 / 时尚 / 美食……）；3) 想验证时看跨模型复测区；4) 装 80 个 AI 视频 skills，让 agent 按案例结构写 prompt。
- 什么时候用 / 常见坑：零基础第一站；模板是英文，替换括号内容时用中文描述也行（AI chat 会转成英文）。

**适用场景**：纯新手、想学"为什么这样写"的学习者。

**怎么用它搞钱**：提示词教学 / 商单。

**来源**：[LearnPrompt/awesome-seedance](https://github.com/LearnPrompt/awesome-seedance) · ⭐2528 · 更新于 2026-11-13

### Motion Prompt 动效/运镜/UI 提示词查询库（showheyohtaki）

**核心提炼**
- 解决什么问题：想让 AI 做某个动效、运镜或 UI 组件，却不知道它叫什么、怎么写 prompt——这个库把名称、动态示例和提问句式整理成 120 条可查条目。
- 核心用法（3 步）：1) 按 5 组翻查（运动图形 motion / 运镜 camera / UI 组件 ui / 落地页效果 lp / 照片质感与布光 photo，每组 24 条）；2) 每条带动态示例和提问句式，先看动效长什么样、再照着句式向 AI 提问；3) 复制条目描述贴进视频生成工具，精准指定动效与运镜。
- 什么时候用 / 常见坑：做 AI 动画 / 短视频需要精准动效描述时查；运镜类条目可直接写进文生视频 prompt 的 camera 段。

**适用场景**：AI 动画 / 短视频创作者、动效设计师；提示词教学者可当词典。

**怎么用它搞钱**：动效提示词教学 / AI 动画商单（精准动效是成片质感的差异化）。

**来源**：[showheyohtaki/motion-prompt](https://github.com/showheyohtaki/motion-prompt) · ⭐2055 · 更新于 2026-11-14（经 GitHub API 核验）· X 推荐帖 [@QingQ77](https://x.com/QingQ77/status/2111970331606847623)

### Claude Opus 5.5 代码生成视频四库导航（@czzzzzzJ_ 推荐）

**核心提炼**
- 解决什么问题：Claude Opus 5.5 能纯靠写代码（HTML / Canvas / SVG / Three.js）生成视频、不用任何视频模型，但网上案例散、写法散——这条导航一次给齐从"跟做"到"拆工程"的四个开源仓。
- 核心用法（4 库分工）：1) joeseesun/opus-video-prompts（约 54 个可复制案例，中文友好）——新手先从这里啃，复制提示词直接跑；2) lemomo-ai/lemo-opuscar（51 种影片风格提示词 + 纯代码样片 + 导演与技术指南）——填自己的故事，让 AI 按风格导短片；3) yihui-dev/awesome-opus5-5-videos（病毒视频成片合集，附创作者原始 Prompt，原片与复刻对照看）——学写法；4) JohnHeibel/PDoomVideo（完整 MV 工程：源码 / 分镜 / 渲染）——想研究复杂动画时拆它的工程。
- 什么时候用 / 常见坑：想零视频模型成本做动画 / 短片时走这条线；PDoomVideo 与 opus-video-prompts 暂无 LICENSE 声明，商用前先确认授权。

**适用场景**：想学"代码生成视频"新范式的创作者、Claude Code / agent 工作流玩家。

**怎么用它搞钱**：代码生成视频教学 / AI 动画商单（零模型成本是报价优势）。

**来源**：X 推荐帖 [@czzzzzzJ_](https://x.com/czzzzzzJ_/status/2112085934267346976)（麦当mdldm，蓝V，2026-10-19 发布）· 仓库 [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) ⭐15722（MIT，2026-11-14 更新） / [yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) ⭐15149（MIT） / [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) ⭐2926 / [joeseesun/opus-video-prompts](https://github.com/joeseesun/opus-video-prompts) ⭐1093（star 均 2026-11-14 经 GitHub API 核验）

### 电影级视频 Skill 十库导航（@awe0_io 推荐）

**核心提炼**
- 解决什么问题：想直接装上就能出电影级视频的 Skill，但网上视频 Skill 散、质量参差——这条导航按实用度排好了 10 个开源仓，从镜头配方到多模型统一接口一次给齐。
- 核心用法（帖内排序，10 库分工）：1) Vincentwei1021/video-shotcraft（⭐19197，Apache-2.0）——Claude / Codex 一句话出电影级产品片，150+ 镜头配方 + Remotion 模板；2) LearnPrompt/awesome-seedance（⭐2528，MIT）——840+ 实测案例 + 80 个可安装 Skill，按场景直接写 Seedance 提示词（本库已有独立条目，此处不重复计）；3) cclank/lanshu-awesome-ai-video-kit（⭐454，MIT）——企业 AI 视频项目工具包，仓库自述 411 prompt + 7 个 Skill，自带模型选择器和跨模型翻译（帖称 600+，以仓库自述为准）；4) robonuggets/seedance-skill（⭐109，暂无 LICENSE）——丢网站截图就出液态玻璃宣传片；5) calesthio/generative-media-skills（⭐243，MIT）——150+ 技能覆盖图像 / 视频 / 音频 / 3D，整套流水线；6) Alisa0808/vibe-creating-skill（⭐163，LICENSE 未识别）——把粗糙想法改写成模型能懂的视频提示词，中英双语；7) iart-ai/explainer-video-skills（⭐102，MIT）——一句话生成带旁白的解说视频或图表动画；8) woodfantasy/Seedance-ShotDesign-Skills（⭐136，MIT-0）——专为 Seedance 2.5 做的分镜、延长、编辑 Skill；9) adamperlis/video-skills（⭐45，MIT）——11 个可复用视频生产 Skill（演示、品牌片、UI 教程）；10) inference-sh/skills（⭐808，暂无 LICENSE）——一个 Skill 调 40+ 视频模型，统一接口。
- 什么时候用 / 常见坑：不知道从哪个 Skill 装起、想按任务挑现成 Skill 时照单装；seedance-skill 与 inference-sh/skills 暂无 LICENSE 声明、vibe-creating-skill 许可未识别，商用前先确认授权；inference-sh 系 API 厂商 Skill，走其 API 按量付费；lanshu 帖称 600+ prompt 与仓库自述 411 有出入，以仓库为准。

**适用场景**：想用 Claude Code / Codex 出电影级产品片、解说视频、品牌片的创作者、agent 工作流玩家。

**怎么用它搞钱**：产品片 / 品牌片商单（电影级镜头配方是差异化卖点）、Skill 装机教学。

**来源**：X 推荐帖 [@awe0_io](https://x.com/awe0_io/status/2113632280036180366)（2026-10-23 发布，原帖全文经 fxtwitter API 核验）· 10 仓库 star 与许可均 2026-11-14 经 GitHub API 核验

### Awesome Video Prompts（ilkerzg）—— fal.ai 视频生成平台

**核心提炼**
- 解决什么问题：想找一个能直接跑起来的 AI 视频提示词平台，而不是只看静态清单——这个仓是基于 fal.ai 的完整视频生成应用，内置提示词库、159+ 条画廊视频、77 篇技术博客。
- 核心用法（3 步）：1) 按 4 个工作室用：Shorts（脚本→9:16 竖屏成片）、Podcast（双人播客脚本→视频）、Scene Builder（故事→分镜→关键帧→渲染）、Multi-Shot（多镜头序列）；2) 在画廊（159+ 视频、15 个分类）先看效果再抄提示词，用 JSON Prompt Builder 结构化写提示词；3) 本地跑需自备 FAL API key（按量付费），Supabase 可选（点赞/浏览统计，不配也能跑）。
- 什么时候用 / 常见坑：想自建一个"提示词库+生成器"一体站、或按分类批量找灵感时用；暂无 LICENSE 声明，商用前先确认授权；走 fal.ai 生成按量付费，先算好成本。

**适用场景**：想搭自己的视频提示词站 / 批量找灵感的创作者、技术型团队。

**怎么用它搞钱**：部署成自己的提示词工具站（引流/会员）/ 提示词教学 / 商单。

**来源**：[ilkerzg/awesome-video-prompts](https://github.com/ilkerzg/awesome-video-prompts) · ⭐138 · 更新于 2026-11-01（经 GitHub API 核验）· 暂无 LICENSE

### Awesome AI Video Prompting（geekjourneyx）—— 双语提示词指南库

**核心提炼**
- 解决什么问题：Veo / Sora / Runway / Pika / Kling 各家官方写法散，想找一份"官方指南+提示词模板+电影语言+音画同步"合在一起的中英双语手册。
- 核心用法（3 步）：1) 先看 Quick Start 懂提示词为什么重要；2) 按 Prompt Engineering（基础/进阶模板、参数控制、电影/广告/艺术专项）+ Cinematic Language（景别/运镜/构图/术语表）查写法；3) 音画同步（Audio & Visual Sync）+ Best Practices 收尾，中文版 README.zh.md 对照看。
- 什么时候用 / 常见坑：新手系统学提示词、或换模型前查官方写法时用；是指南型合集（docs/ 下分文档），不是案例视频库，找现成可抄案例去 songguoxs / ZeroLu 那几条。

**适用场景**：系统学 AI 视频提示词的新手、提示词教学者。

**怎么用它搞钱**：提示词教学 / 商单（规范写法是报价底气）。

**来源**：[geekjourneyx/awesome-ai-video-prompts](https://github.com/geekjourneyx/awesome-ai-video-prompts) · ⭐90 · MIT · 更新于 2026-11-13（经 GitHub API 核验）

### Seedance 2.0 反转式喜剧完整提示词：《老板不批》（@Soranlan）

**核心提炼**
- 解决什么问题：想抄一条"有梗、能直接跑"的 Seedance 2.0 短喜剧提示词——这条 15 秒、16:9、真人现代冷幽默，借"4000 多元算力成本做 96 集 AI 短剧"当日热点，讽刺低估创作者劳动的成本叙事，结构完整到可直接替换人物和台词。
- 核心用法（3 步）：1) 按"核心→人物→地点→三镜头分镜→声画/连续性→Negative Prompt"六段结构抄：人物用 @图一/@图二 锁定两张独立人脸（象牙白外套制片人 vs 青绿毛衣 AI 短剧作者）；2) 三镜头 0–5 秒全景（"四千拍了九十六集？""四千是算力费"）、5–10 秒中景（"编剧、导演、剪辑呢？""我。""老板呢？""也是我。"）、10–15 秒近景（"那还不下班？""老板不批。"静默收尾不强行笑）；3) 声画连续性写死：普通话原生对口型、三镜头沿同一轴线、鼠标声/风扇低响/室内空气声自然、无旁白字幕煽情；负面词堵死换脸/换衣/背景漂移/道具消失。
- 什么时候用 / 常见坑：蹭当日热点做冷幽默短剧时套这个六段结构；换梗时只换核心冲突和台词，人物锁定与三镜头节奏别动；它引用了作者 7 月 25 日的剑仙反转旧帖（同一结构），那条不在本次收录范围。

**适用场景**：做热点讽刺短剧、反转喜剧的创作者。

**怎么用它搞钱**：热点短剧商单 / 提示词教学（六段结构是可复用的模板）。

**来源**：X 原帖 [@Soranlan](https://x.com/Soranlan/status/2121225396855439362)（2026-11-13 20:55 北京发布，正文经 fxtwitter API 核验）

### 5 篇 AI 短剧教程合集导航（@qloog）

**核心提炼**
- 解决什么问题：想系统学 AI 短剧但不知从哪篇看起——这条按热度排好了 5 篇教程：全流程、剧本、分镜、漫剧全覆盖。
- 核心用法（5 篇分工）：1) 一个人拍短剧：Claude + MiniMax H3 从想法到成片，附全流程提示词和技能包（@TuyetloanP81840）；2) 怎么写剧本：短剧和电影短片两套写法，附作者正在用的剧本技能（@TuyetloanP81840）；3) 怎么拆分镜：60 个镜头是怎么来的，附分镜技能（@TuyetloanP81840）；4) 低成本漫剧：手搓和自动调度两套方案，从剧本、资产、分镜到 H3 成片（@aggs8p）；5) 漫剧 Skills：21 套题材模板，一句话生成企划、剧本、分镜和视频提示词（@fhwofjow51260）。
- 什么时候用 / 常见坑：从零学 AI 短剧时按 1→5 顺序啃；5 条内链的各自发布时间未逐条核验（内链为 t.co 短链，原文未给状态 ID），以合集帖 2026-11-13 21:54 发布为准，点进去先看日期再跟。

**适用场景**：从零学 AI 短剧/漫剧的创作者。

**怎么用它搞钱**：短剧代制接单 / 教程拆解内容。

**来源**：X 原帖 [@qloog](https://x.com/qloog/status/2121240315587948686)（2026-11-13 21:54 北京发布，正文经 fxtwitter API 核验）

### 代码 + AI 日更视频全自动流水线 + 2026 工具全景图（@itsyhy）

**核心提炼**
- 解决什么问题：日更视频靠手动剪辑太慢、又容易模板同质化——这篇把做视频变成"软件工程问题"，画面/配音/混音/质检/调研全部代码化，并附 2026 最全工具全景图。
- 核心用法（4 步）：1) 画面编程：Remotion（React 写视频，字幕条/弹窗卡片/分屏容器一次写好、传 JSON 批量渲染）+ OpenFilm（HTML/JS 伪 3D、动能字幕、HUD）+ Python + Pillow/OpenCV + FFmpeg（逐帧画图破模板）；2) 静帧资产：Codex CLI 本地 Mac 终端读 tasks.csv + 参考图批量生成风格一致静帧（布偶猫 Mochi）；3) 配音质检：Azure AI Speech 商用接口（英文长视频 en-US-MichelleNeural +4%、Shorts 用 en-US-BrianMultilingualNeural +4%、中文 zh-CN-YunfanMultilingualNeural）+ faster-whisper 自动回读查漏词；4) 混音质检：FFmpeg mix.py（silenceremove、ducking、两遍 loudnorm 锁定 -14 LUFS、黑帧/冻帧/静音检测、每秒抽帧联系表）+ auto-editor 收紧气口 + pyJianYingDraft 落剪映；Mixkit 免署名可商用音乐 + YouTube/X API 与 yt-dlp 抓爆款数据反哺钩子库。
- 什么时候用 / 常见坑：做矩阵号/日更、或想从"手动剪"升级到"代码出片"时照这套搭；三条选型路线：零代码 CapCut + 可灵/即梦 + Mixkit、知识口播 Descript + OpusClip + HeyGen、技术矩阵 Remotion/OpenFilm + Codex + Azure + FFmpeg；作者结论：工具是杠杆，天花板是前 3 秒钩子、反套路叙事、选题库迭代。

**适用场景**：日更矩阵号、技术型创作者、想批量出片的团队。

**怎么用它搞钱**：矩阵号代运营 / 自动化出片教学 / 工具选型咨询。

**来源**：X 原帖 [@itsyhy](https://x.com/itsyhy/status/2121282238608539747)（2026-11-14 00:41 北京发布，Article 全文经 fxtwitter API 核验）

### AI 短剧变天：平台按观看时长分账，草根团队靠慢工零投流活下来（@grapeot）

**核心提炼**
- 解决什么问题：99% 的 AI 短剧项目亏本、抽盲盒烧废片+七成流水买量——这篇用两个草根团队的一手账本拆解平台规则转向后怎么活：分账锚定有效观看时长，慢工+零投流反而赚钱。
- 核心用法（3 步）：1) 看懂新账本：抖音/红果分账=有效观看时长×动态单价，微信人均看够 10 分钟制作方最高拿 100% 收入激励；前 3 秒骗点击划走几乎换不来分账；10 月下旬红果关停看剧赚金币、下架 20,426 部换皮剧，抖音把伪漫剧降档低价解说剧；2) 学苏州团队：大三学生肖天乐 7 天 3 部快餐代工利润见底后转原创自发行，单部剧播放 15 亿次、创收 200 多万元，不到一年累计营收破 300 万元；3) 学石家庄《持械入宋》六人组：54 岁前批发商张汉生带网约车司机/全职宝妈/送货员，10 季 1000 集约 25 小时、算力投入超 100 万元，全程零投流累计播放超 40 亿次——铁律是 60 分平淡镜头一律作废、开机前半个月精读原著+豆包逐句磨台词+导演一周多做前 20 分钟样片预演、几十张人设/场景/道具图塞进公共资产库、提示词组内全开源、一人一公司零底薪事后按工时分账。
- 什么时候用 / 常见坑：做 AI 短剧立项前先读这篇定策略（时长为王、慢工、考据、共享资产库）；文中数字均为受访者自述，张汉生已辟谣金融分析师背景与千万级回报、总账还没细算，引用时注明来源。

**适用场景**：AI 短剧创业者、想转原创自发行的代工团队。

**怎么用它搞钱**：短剧自发行分账 / 代制接单（按新规则报价）。

**来源**：X 原帖 [@grapeot](https://x.com/grapeot/status/2121288734125814048)（2026-11-14 01:07 北京发布，正文经 fxtwitter API 核验）· 外链文章 yage.ai

### Vibe Coding 小游戏《种毛衣》30 秒宣传片全流程拆解（@ycnot84）

**核心提炼**
- 解决什么问题：Vibe Coding 小游戏要一条宣传片，但风格一跑就散、配乐/字幕/二维码处处踩坑——这篇 Article 把 30 秒、9 镜、90 BPM 的真实流程和踩坑全拆开，风格前缀可直接抄。
- 核心用法（4 步）：1) 先写分镜再生成：游戏核心循环拍成"生产链"（种棉花→纺毛线→毛线排序→织毛衣），9 个镜头 30.0 秒（钩子、种植、离线生长、纺线、排序、小猫捣乱、编织、快剪、收尾），每镜写清时长/目的/画面/运镜/带到下一镜的"衔接物"，开头 2 秒抛问题"一朵棉花/能种出一件毛衣？"、答案留到羊驼奶奶举起毛衣的最后一镜；2) 风格锁死：羊毛毡定格动画微缩场景（手作、莫兰迪低饱和、圆润、不用纯黑描边，轻微变形也不扎眼），先用 Grok Bot 生成"世界+角色"锚点图（羊驼奶奶在农田边），其余全拿它当参考图；每镜提示词加同一段风格前缀（可直接抄）："Needle-felted wool stop-motion miniature diorama, macro photography, shallow depth of field, soft warm morning window light, low-saturation Morandi palette… no black outlines… Materials stay felt and wool, no morphing, no text, no logo."，关键是 "no text, no logo"——字一律后期用代码加；3) 先做 1 条样片再批量：5 张风格图 + 1 条钩子样片（棉桃绽开）确认后再批量，Grok Imagine 图生视频每段 720p、5 秒、9:16，提示词把"画面里发生什么"和"镜头怎么动"分开写；10 段用了 8 段、2 段弃用，模型自带音轨全部不用；4) 配乐与剪辑全代码化：90 BPM、C 大调纯音乐用 Python + numpy 合成（拨弦模拟尤克里里+八音盒/贝斯/沙锤/手拍/混响），音效也合成，混音实测 -14.0 LUFS，切点全落拍子上（1 拍=0.667 秒，快剪段半拍一刀）；ffmpeg 合成，字幕卡 Noto Sans CJK SC 代码生成、每张最多 2 行；片尾二维码从成片抽 6 帧、用 zxing-cpp 和 OpenCV 两种解码器验证通过。
- 什么时候用 / 常见坑：给自己的小游戏/产品做 AI 宣传片时照这套抄；5 条可复制经验：分镜先写"衔接物"、先锁 1 张锚点图、先做 1 条样片再批量、模型不写字、二维码一定要抽帧解码验证；注意片子画面是 AI 生成的概念片、不是游戏实际画面。

**适用场景**：独立游戏/产品宣传片、Vibe Coding 创作者。

**怎么用它搞钱**：游戏宣传片商单 / Vibe Coding 教学。

**来源**：X 原帖 [@ycnot84](https://x.com/ycnot84/status/2121363918790832453)（2026-11-14 06:05 北京发布，Article 全文经 fxtwitter API 核验）

### NotebookLM 跨平台自媒体"降维打击"工作流（@taketokennn）

**核心提炼**
- 解决什么问题：Gemini Pro 会员的算力闲置、跨平台做号一人顶不了一支团队——这条用 NotebookLM 的 Deep Research + Studio 视频生成搭成全自动内容工厂，给选题就能批量出片。
- 核心用法（3 步）：1) 自动调研：Deep Research 围绕关键词跑 2 轮，1 分钟抓几十份深度报告和数据；2) 锁定脚本：在对话里限字数洗出爆款钩子脚本，存为 Note 并设为唯一来源（精准控制视频时长、防出错的核心秘诀）；3) 一键成片：Studio 面板选 Video Overview，英文大片风选 Cinematic、中文解说选 Explainer + 简体中文，几分钟输出带动态图表的完整视频；作者称 Gemini Pro 会员每天算力池约能稳定跑 10–15 条标准解说/短视频、顶配电影感大片 3–5 条（作者说法，未独立核验）。
- 什么时候用 / 常见坑：有 Gemini Pro 会员、想做跨平台解说/知识号时跑这套；成片一鱼多吃：英文版发 X 和 YouTube 赚美金收益，中文版同步抖音、小红书、B 站、视频号；选题覆盖商业巨头翻车、历史冷知识、金融悬案；示例为英伟达 5 分 39 秒视频（"33 years to build a $4 Trillion empire. 14 days to watch it collapse."），AI 直出未做人工调整。

**适用场景**：跨平台解说/知识号、一人自媒体。

**怎么用它搞钱**：多平台收益（英文版美金收益 + 中文版分发）/ 批量出片代运营。

**来源**：X 原帖 [@taketokennn](https://x.com/taketokennn/status/2121388136450453510)（2026-11-14 07:41 北京发布，正文经 fxtwitter API 核验）

### AI 短剧提示词写光：让光在镜头里动（@FootballAnt247）

**核心提炼**
- 解决什么问题：AI 短剧提示词写光只会写"暖色调"这类静态词，画面死气沉沉——这条给的是能直接套用的"写光"方法。
- 核心用法（3 句实战写法）：1) 接电话的静止镜头：「窗外光斑沿玻璃缓慢滑过」；2) 办公室揉太阳穴：「窗外车流光斑持续移动」；3) 关门收尾：「最后一道晨光随门缝闭合而消失」；心法一句话：人不动的时候，光替你动——写清光从哪来、往哪走、最后停在哪。
- 什么时候用 / 常见坑：写文戏/静止镜头提示词时用；别只写色调词，要写光的运动轨迹。

**适用场景**：AI 短剧/文戏提示词作者。

**怎么用它搞钱**：短剧提示词教学 / 代制接单（光影质感是成片差异化）。

**来源**：X 原帖 [@FootballAnt247](https://x.com/FootballAnt247/status/2121398824509780203)（2026-11-14 08:24 北京发布，正文经 fxtwitter API 核验）

### AI 视频日报｜11.14：Seedance 2.5 Flash 上 Runway、《持械入宋》号称 120 亿（@FootballAnt247）

**核心提炼**
- 解决什么问题：AI 视频圈消息散、更新快——这是每 2–3 天一期的定期日报，一屏看完这两三天的大事。
- 核心用法（本期 10 条）：1) Claude Meetings 内测：拉进视频会议，边聊边出文档；2) Krea Bots 开测：AI 创意小队接整个项目，送 $1000；3) Gemini 4 Hydrogen 发布：比 3.8 Flash 快 2.5 倍；4) Higgsfield 再办百万美元大赛：头奖 20 万美元；5) Seedance 2.5 Flash 上 Runway：更快更便宜，第三方实测比 2.5 便宜约三成五；6) AI 漫剧《持械入宋》号称播放 120 亿，已更 1000 集；7) Runway 支持 3D：文/图生 3D 模型当镜头参考；8) HeyGen 接入 Gemini Omni Flash 1.2：15 秒音画同出；9) Envato 11/19 起 24 小时免费无限用 MiniMax H3；10) Chroma Awards 第二季开赛：奖金超 45 万美元。
- 什么时候用 / 常见坑：追行业动态、做选型决策时翻；《持械入宋》120 亿为作者转述"号称"，引用时注明来源；价格类数据（Flash 便宜约三成五）为第三方实测说法。

**适用场景**：追 AI 视频行业动态的创作者、做模型选型的人。

**怎么用它搞钱**：行业资讯号 / 选型咨询（日报本身就是内容选题库）。

**来源**：X 原帖 [@FootballAnt247](https://x.com/FootballAnt247/status/2121429604518998147)（2026-11-14 10:26 北京发布，正文与配图经 fxtwitter API + 图片直读核验）

### 0 元火柴人动画新案例：27 秒「冰箱小剧场」（@AI_DVD6）

**核心提炼**
- 解决什么问题：火柴人动画的母指令方法有了，缺一个"真跑通了"的最新案例——这条就是 0 花费做出来的 27 秒「冰箱小剧场」成片演示。
- 核心用法（4 步）：1) 一句中文母指令，AI 包办编剧和导演；2) Google Flow 生成角色和动画，角色出图 0 点数；3) 开源 AI 配音，支持商用；4) 一条提示词，AI 自动剪辑、合成成片；全程没画一笔、没手写剧本、没花一分钱，换个故事就能再做一条；全过程拆成 8 步、每步有截图，母指令已整理。
- 什么时候用 / 常见坑：方法本体（母指令 + 8 步全流程）在作者 11 月 12 日长文里，该长文已收进提示词优化库，本条是同一方法的最新案例演示，不重复收方法；长文称 Google Flow 每天 50 点、4 段视频共 40 点，第一条约 30 分钟、熟了 15 分钟一条；文中 27 秒为作者说法。

**适用场景**：零成本做火柴人动画/脑洞短片的人。

**怎么用它搞钱**：副业账号（YouTube Shorts / 抖音 / 视频号日更）/ 动画教学。

**来源**：X 原帖 [@AI_DVD6](https://x.com/AI_DVD6/status/2121456840957391302)（2026-11-14 12:15 北京发布，正文与所引 11-12 长文经 fxtwitter API 核验）· 方法本体见提示词优化库同作者条目

### AI 视频生成器 11 月横评 + 两条动画路线对照（@WDdabiange）

**核心提炼**
- 解决什么问题：做动画不知道选视频生成还是写代码——这条把两条路线摆在一起对照，并附 11 月更新版生成器横评。
- 核心用法（两条路线）：1) 视频生成路线：Veo 3.1 画面带原声音画同步，Kling 4.0、Seedance 2.5 一次能生成 30 秒；2) 代码动画路线：Claude Code 写几百行代码就能出分镜、运镜、粒子，一帧一帧全可控；一个靠想象力，一个靠精确控制——做动画的门槛正在被两边一起往下压；附 seeddance.io《Best AI Video Generators in 2026 (November Update)》横评（Kling 4.0、Seedance 2.5、Runway 等 8 款，免费档与水印按官网复核）。
- 什么时候用 / 常见坑：选模型、选路线时对照看；注意所链横评配图图注写着 June 2026，与 November Update 标题不一致，引用时留意时效。

**适用场景**：选模型/选动画路线的人。

**怎么用它搞钱**：选型咨询 / 动画商单（两条路线对应两种报价）。

**来源**：X 原帖 [@WDdabiange](https://x.com/WDdabiange/status/2121478543989477849)（2026-11-14 13:41 北京发布，正文与卡片标题经 fxtwitter API 核验）· 横评链接 [seeddance.io](https://www.seeddance.io/blog/best-ai-video-generators-2026)

### Kling 4.0 提示词写法：只描述镜头里有什么（@park_danie36173）

**核心提炼**
- 解决什么问题：Kling 4.0 提示词写一堆否定词反而更容易出错——这条按官方指南给了一个极简写法。
- 核心用法（3 步）：1) 描述镜头里有什么（正面描述），否定句改肯定句："No people in the background" → "An empty street behind her"；2) 只排除两样东西：字幕（no subtitles）和背景音乐（no background music），因为模型默认可能加上它们；3) 风格变化时写明风格、排除写实质感，别扩充排除清单。
- 什么时候用 / 常见坑：用 Kling 4.0 出片时照这条写；出处为 Kling 4.0 用户指南 2.2 节、API 手册 8.7、Runware 文档，指南 11 月 4 日更新、作者 11 月 14 日核对；配图 4 张为代码画的示意图，不是 Kling 生成的。

**适用场景**：用 Kling 4.0 出片的创作者。

**怎么用它搞钱**：Kling 商单 / 提示词教学（官方写法是报价底气）。

**来源**：X 原帖 [@park_danie36173](https://x.com/park_danie36173/status/2121493427242299500)（2026-11-14 14:40 北京发布，正文经 fxtwitter API 核验、4 张卡片逐张直读核验）

### Reddit 爆款故事 → Seedance 2.0 火柴人动画 → 双平台引流（@natiakourdadze）

**核心提炼**
- 解决什么问题：不知道拍什么能起量——这条给了一个三步闭环的搞钱流程。
- 核心用法（3 步）：1) 找本领域在 Reddit 上爆过的故事；2) 用 Seedance 2.0 做成 60 秒火柴人动画；3) 发到 YouTube 和 IG 引流。
- 什么时候用 / 常见坑：想低成本批量做英文流量号时跑这套；与库内火柴人系列条目互相索引（@AI_DVD6 母指令方法、@daodao166888 What If 系列）。

**适用场景**：想低成本批量做英文流量号的人。

**怎么用它搞钱**：YouTube / IG 流量收益 / 矩阵号代运营。

**来源**：X 原帖 [@natiakourdadze](https://x.com/natiakourdadze/status/2121497610313777652)（2026-11-14 14:57 北京发布，全文经 fxtwitter API 核验）

### 先跑 3 秒测试再跑全片（@neo_cn）

**核心提炼**
- 解决什么问题：全片一次跑完才发现人设崩了、动作错了——返工全段重来，时间和额度一起烧。
- 核心用法：方法论一句话：AI 视频别一上来就跑全片，先跑一条 3 秒测试——test shot first, check face, motion, lighting（看人设、动作、光线），没问题再跑全片；测试先过，全片才稳。
- 什么时候用 / 常见坑：每次跑全片前先过 3 秒测试；这是成本控制方法，3 秒测试本身也要看人设/动作/光线三项，缺一不可。

**适用场景**：所有 AI 视频创作者（省额度）。

**怎么用它搞钱**：降本就是增利 / 工作流教学。

**来源**：X 原帖 [@neo_cn](https://x.com/neo_cn/status/2121498181393645744)（2026-11-14 14:59 北京发布，全文经 fxtwitter API 核验）

### What If 3D 极限脑洞频道拆解（@daodao166888，补翻 11-11）

**核心提炼**
- 解决什么问题：What If 赛道 2D 版火了，3D 版怎么做——这是同一作者的 3D 对照拆解，公式更简洁。
- 核心用法：1) 数据：不露脸 3D 动画讲 What If 极限脑洞，仅 16 条视频涨粉 22900，总播放突破 629 万，预估收益 17800 美元，其中 2 条分别突破 230 万、210 万；对照样本 @Minute_zero_real；2) 公式：What If + 日常事物/能力 + 无限变化 + 无法停止；3) 照做四步：① YouTube 搜 What If、Couldn't Stop、Speed Up，找近 30 天还在涨、标题一眼能看懂的假设类视频；② 只记普通人早就好奇过的题，写成对照样本笔记（频道名、视频数、粉丝、单条播放量、标题公式）；③ 拆播放最高的 3 条，看前 15 秒怎么制造好奇、数字怎么升级、画面怎么从日常场景推向极限；④ 用 Claude Code 等现成工具先做一条 60–90 秒的最短可测样片，别一上来就做 9 分钟；附全套提示词模板（帖内图片/回复）。
- 什么时候用 / 常见坑：本条为 11-11 晚档已收 2D 版（ConChaser，隐藏信息可视化 + 数值反差 + 人物冲突 + 剧情反转）的 3D 对照篇，公式与样本不同，不重复；数据为作者自述。

**适用场景**：想做 What If 赛道动画号的人。

**怎么用它搞钱**：动画号流量收益 / 拆解教学。

**来源**：X 原帖 [@daodao166888](https://x.com/daodao166888/status/2120527377524760868)（2026-11-11 22:41 北京发布，正文经 fxtwitter API 核验，同时核验所引 2D 版原文）

### 视频提示词四要素：主体、场景、时间、风格（@Formulasearch，补翻 11-11）

**核心提炼**
- 解决什么问题：视频提示词写得又长又散、模型还是跑偏——这条把写法压成四个词。
- 核心用法：公式一句话：主体、场景、时间、风格——制作视频，长篇大论再多，不如记住这四个词；写提示词先对齐四要素再展开。
- 什么时候用 / 常见坑：写视频提示词总跑偏时拿这四个词自查；内容很短，价值在公式本身。

**适用场景**：写视频提示词总跑偏的人。

**怎么用它搞钱**：提示词教学（四要素是可复用的检查清单）。

**来源**：X 原帖 [@Formulasearch](https://x.com/Formulasearch/status/2120546725102518340)（2026-11-11 23:58 北京发布，全文经 fxtwitter API 核验）

### Minecraft 剧情动画频道拆解（@daodao166888，补翻 11-12）

**核心提炼**
- 解决什么问题：游戏剧情动画号怎么从 0 起量——这篇用两组对照样本拆出"牵挂的处境 + 结局后置"的公式。
- 核心用法：1) 数据：不露脸 AI 做 Minecraft 剧情动画，21 条视频涨粉 9.77 万，总播放突破 1599 万；对照样本 YouTube @xoxu-mc（前几天拆过 @CheesyRisy）；2) 结论：先找准一个让观众牵挂的处境，再把结果留到后面；核心是让观众迅速在意一个角色，再给他一个追下去的理由；3) 照做三步：① YouTube 搜 minecraft story shorts，找近期播放还在涨的作品，记观众一眼能理解的冲突；② 记清楚谁被留下、其他人怎么选、主角受了什么委屈、结果什么时候揭晓；③ 用现成工具先做一条 30–45 秒片子，固定角色和画风，先测故事，别一上来买一堆会员；角色建议自己原创、逐步积累角色资产；附全套提示词模板（帖内图片/回复）。
- 什么时候用 / 常见坑：所引 11 月 9 日原帖补充：同赛道另一账号换赛道不到 3 周，20 条 Shorts 订阅从 2.55 万涨到 23.3 万，其中"没人救坏小孩"约 12 天播放 1276 万；转型前 175 条视频 7480 万播放只涨 2.5 万粉，转型后每 1000 次播放带来订阅从 0.35 个变 7.9 个；⚠️ 别用 JJ、Mikey 等别人的角色，版权投诉一来号就没了；数据为作者自述。

**适用场景**：想做 Minecraft / 游戏剧情动画号的人。

**怎么用它搞钱**：剧情动画号流量收益 / 角色资产复用。

**来源**：X 原帖 [@daodao166888](https://x.com/daodao166888/status/2120737396946080192)（2026-11-12 12:36 北京发布，正文与所引 11-10 原帖经 fxtwitter API 核验）

### Skill 对照实验：长篇 Skill 反而拖慢大模型（@Formulasearch，补翻 11-12）

**核心提炼**
- 解决什么问题：写了一堆 Skill，大模型出片反而更慢更贵——这篇用 Opus 5.5 做了分组对照实验，给出反直觉的结论。
- 核心用法：1) 方法：主对话只负责派任务和旁观监督，下面开多个子对话去做，全部用 Opus 5.5，同一道题分几组跑，作者判断成果质量并排序；分组 A 全套 skill（严格按自写 skill 一步步做）、B 只给规则（项目规则 + 偏好记录，不准用 skill）、C 裸模型（只给做题资料）、D 换工具（裸模型，动画不用 Remotion、改用 HTML + GSAP）；三道题：① AI 自己想题，做一条 20 秒动效；② 给定真实品牌需求和资料，做一条 30 秒广告；③ 同第 2 题，只把 Remotion 换成 HTML + GSAP；2) 结果（用时 / 输出 token / 读入上下文 / 排名）：题 1：A 24 分钟 / 23.7 万 / 6970 万 / 最差，B 16 分钟 / 13.7 万 / 2040 万 / 过关，C 20 分钟 / 11.3 万 / 1140 万 / 过关；题 2：A 31 分钟 / 31.4 万 / 7340 万 / 第 2，B 19 分钟 / 19.9 万 / 3370 万 / 第 3，C 14 分钟 / 17.5 万 / 1640 万 / 第 1；题 3：C+GSAP 14 分钟 / 20.3 万 / 1710 万 / 与题 2 第 1 名打平；3) 结论：① 长篇大论的 Skill 是在干扰大模型的注意力，简单提示反而 token 和时间最少；② 但"太自由"也有问题，需要一定经验积累去给出引导和限制，效果会稳定很多；③ Remotion 或许并没有带来好处，两种工具用时和 token 几乎一样，GSAP 做出来更流畅，Remotion 的组件细节或许更准一点，但不具备很大优势，作者称以后应该不会继续用了。
- 什么时候用 / 常见坑：用 Claude Code / Opus 做视频、纠结要不要写长 Skill 时看；局限：每组只跑了一次，@TammyBuilds 在评论区质疑单次取样下模型方差可能影响结论，作者本人也说测试"可能不太完善"；作者后续称已删除大量无意义规则、把长篇 md 砍到只剩几句话，效果反而更快更好，代价是额度飞得更快。

**适用场景**：用 Claude Code / Opus 做视频、纠结要不要写长 Skill 的人。

**怎么用它搞钱**：省 token 省时间就是降本 / 工作流教学。

**来源**：X 原帖 [@Formulasearch](https://x.com/Formulasearch/status/2120690542833029274)（2026-11-12 09:30 北京发布，正文经 fxtwitter API 核验、结果表配图直读核验）

### 让 Seedance 2.5 说四川话：两步方言配音法（@xiayitiaoAI，补翻 11-12）

**核心提炼**
- 解决什么问题：Seedance 2.5 生成的方言对白一股普通话味——这条以大闸蟹街访为例，给了两步实操法。
- 核心用法（2 步）：1) 把普通话台词丢给大语言模型，按四川人日常聊天的说法改成川普台词——普通话「她说让我先洗个热水澡，我泡进去就觉得不对。等一下，这不是浴缸！这是锅！」→ 四川话「她喊我先洗个热水澡嘛，我一泡进去就觉得不对头。等哈……这哪是浴缸哦？这是口锅噻！」；2) 生成视频时把方言和说话方式写进提示词：大闸蟹用地道的四川话男声说下面这段台词，全程保持四川口音，按原词说一遍；开头语速稍快，像急着跟记者告状；说到「等哈」突然停半拍，再压低声音问「这哪是浴缸哦？」；最后一下提高声调，重读「锅」。
- 什么时候用 / 常见坑：做方言短视频/街访/地方特色内容时用；同一方法可迁移到其他方言（先改台词、再把方言和说话方式写进提示词）。

**适用场景**：做方言短视频/街访/地方特色内容的人。

**怎么用它搞钱**：方言内容差异化涨粉 / 商单。

**来源**：X 原帖 [@xiayitiaoAI](https://x.com/xiayitiaoAI/status/2120736952655974437)（2026-11-12 12:34 北京发布，正文经 fxtwitter API 核验）

### 御剑飞行人物一致性：姿势图 + 脸部虚化 + 角色卡（@TanLuAI，补翻 11-12）

**核心提炼**
- 解决什么问题：古风飞行镜头姿势一换脸就崩——这条用"姿势图 + 脸部虚化 + 角色卡"三件套，一遍生成青衣侠女仰躺御剑。
- 核心用法（3 步）：1) 先做一张姿势图（评论区自取）；2) 脸部作下虚化（不生成姿势参考图里的脸部马赛克）；3) 再加角色卡（五官沿用清晰人物参考图，保留额间细小花纹、半束黑色长发与发饰）；姿势保持了，人脸一致性也维持；提示词要点（作者自回帖）：4:3 横向画幅一镜到底，2000–2005 年中国南方小镇，家用 MiniDV 偶然拍到青衣女子仰躺御剑、向镜头比耶后加速撞上前方垃圾桶；纪实、略模糊、手持、不完美构图、有真实现场感；全程仰躺不站立、不蹲坐、不换姿势，身体沿剑身纵向后仰，一手枕在脑后、两腿弯曲、一脚抬高、一脚靠近剑柄、一手从膝盖附近抬起向镜头比耶；只有一把实体金属长剑，剑尖在女子头部一端、剑柄在脚部一端，以脚部/剑柄一端朝前行进；长剑贴近路面低空飞行、与地面平行、高度低于垃圾桶桶盖，前端剑柄轨迹正对垃圾桶身中部；人物、剑与地面投影同步移动，头发和袍摆随实际气流向后飘。
- 什么时候用 / 常见坑：做古风/武侠 AI 视频、卡人物一致性时套这三件套；作者备注：飞行方向看起来不对，明天重新调教——成片方向感仍需人工验收；完整提示词见作者自回帖（浏览器侧读取）。

**适用场景**：做古风/武侠 AI 视频、卡人物一致性的人。

**怎么用它搞钱**：古风短视频商单 / 人物一致性教学。

**来源**：X 原帖 [@TanLuAI](https://x.com/TanLuAI/status/2120901866200658141)（2026-11-12 23:29 北京发布，主帖正文经 fxtwitter API 核验，完整提示词在作者自回帖，浏览器侧读取）

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

- 2026-11-14：午档搜集新增 13 条（X 13 条：主窗口 7 条 @FootballAnt247 写光/视频日报、@AI_DVD6 冰箱小剧场新案例、@WDdabiange 11 月横评、@park_danie36173 Kling 4.0 写法、@natiakourdadze Reddit 火柴人引流、@neo_cn 3 秒测试；补翻 11-11–11-12 6 条 @daodao166888 What If 3D / Minecraft、@Formulasearch 四要素 / Skill 对照实验、@xiayitiaoAI 四川话、@TanLuAI 御剑；13 帖正文与时间戳均经 fxtwitter API 核验，日报配图/实验结果表/Kling 4 张卡片逐张直读核验；去重：@daodao166888 What If 2D 已在复制爆款库、@Zizaiaiai 声音篇/@daodao166888 地图灾难/@xiayitiaoAI 文戏反应镜头已在提示词优化库，均不重复计），共 32 个项目
- 2026-11-14：早档搜集新增 8 条（GitHub 2 个：ilkerzg/awesome-video-prompts 138★、geekjourneyx/awesome-ai-video-prompts 90★ MIT；X 6 条：@Soranlan 反转喜剧完整提示词、@qloog 5 篇短剧教程合集、@itsyhy 代码+AI 全自动流水线、@grapeot AI 短剧分账账本、@ycnot84《种毛衣》宣传片拆解、@taketokennn NotebookLM 工作流；8 条正文与时间戳均经 fxtwitter API 核验，ycnot84 与 itsyhy 两篇 Article 全文已读），老 21 项 star 全量刷新（0 回落：LearnPrompt 2122→2528、showheyohtaki 411→2055、lemo-opuscar 3544→15722、awesome-opus5-5-videos 6464→15149、video-shotcraft 15491→19197），共 19 个项目
- 2026-11-01：早档搜集新增 1 条（电影级视频 Skill 十库导航，经 @awe0_io 帖推荐，10 仓库 star 均当日 API 核验），GitHub 关键词无新命中，共 11 个项目
- 2026-10-19：晚档搜集新增 1 条（Claude Opus 5.5 代码生成视频四库导航，经 @czzzzzzJ_ 帖推荐，4 仓库 star 均当日 API 核验），共 10 个项目
- 2026-10-19：早档搜集新增 1 条（Motion Prompt 动效/运镜/UI 提示词查询库 showheyohtaki/motion-prompt，120 条目，经 @QingQ77 帖推荐，⭐411 今日更新），GitHub 关键词无新命中，共 9 个项目
- 2026-10-18：早档搜集新增 1 条（Veo3/即梦/可灵/海螺/豆包视频提示词精选 songguoxs/awesome-video-prompts，50 案例），X 侧 0 新增，共 8 个项目
- 2026-10-18：午档搜集新增 2 条（MiniMax H3 14 种电影级运镜 prompt 合集 loopforge0/minimaxh3-shots-skills、Higgsfield 两部 AI 电影《HELL GRIND》/《Cully Hill Boys》全套提示词资产库），老 5 条 star 全量复核更新，共 7 个项目
- 2026-10-12：条目升级为小节格式（核心提炼 / 适用场景 / 搞钱 / 来源），新增 MiniMax H3、FLUX 官方 skills 两个新品类项目，共 5 个项目
- 2026-10-11：首版，3 个项目，持续收录中
