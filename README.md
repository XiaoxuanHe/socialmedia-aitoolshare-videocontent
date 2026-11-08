# socialmedia-aitoolshare-videocontent

为小红书 AI 工具分享、AI Building Case 和 learn in public 系列制作 **3～5 分钟视频内容框架**的 Codex skill。

A Codex skill for planning 3–5 minute AI tool-sharing videos on social media, covering audience pain points, solutions, practical walkthroughs, benefits and limitations, and learn-in-public follow-ups.

当前版本为 **v0.1**。默认使用中文，面向 AI 兴趣人群、创作者和使用 AI 辅助工作的人。

## 内容结构

| 默认时间轴 | 内容 |
| --- | --- |
| 00:00–00:20 | 用具体场景引出共鸣痛点 |
| 00:20–00:45 | 解决方案、好处、适合谁及必要条件 |
| 00:45–02:55 | 展示关键操作，展开最有意思或最容易卡住的一步 |
| 02:55–03:35 | 检查结果，复盘好处与不足 |
| 03:35–04:00 | 下期改进实验、持续学习计划和一个评论问题 |

默认时长为四分钟，可按素材调整到三至五分钟。时间轴为策划估算，最终成片时长以试读或实际音轨为准。

## 每次输出

- 本集定位、受众、观众能学会什么和目标时长。
- 包含口播要点、演示画面和证据状态的时间轴。
- 共鸣开场、方案承接和结尾互动三处关键口播。
- 拍摄前需要补齐的素材和验证项。

明确要求逐字稿时，可继续展开完整口播。视频制作、剪辑和平台发布需要额外执行。

## 使用方法

下载本仓库，在 Codex 中指定本地 SKILL.md 的实际路径，并提供案例。

```text
请读取并使用 socialmedia-aitoolshare-videocontent 文件夹中的 SKILL.md。

帮我制作一份 4 分钟小红书视频内容框架。
案例是……
目标观众是……
最想展示的一步是……
已完成的成果和实测数据是……
已发现的不足是……
下期想测试的方向是……

缺少的事实请标为待验证，并安排相应的录屏或展示画面。
```

文件夹位于其他位置时，请填写 SKILL.md 的完整路径。尚未确定的信息可以写“待验证”。

## 与选题 skill 配合

可以将 [socialmedia-aitoolshare-videobuilder](https://github.com/XiaoxuanHe/socialmedia-aitoolshare-videobuilder) 生成的主题、选题、推荐标题和证据清单直接交给本 skill，展开为拍摄框架。本 skill 也可独立接收案例。

## 示例输入

```text
我想用 AI 做一条短剧，重点分享如何寻找和筛选灵感。
目前没有实测耗时、成片或收益数据。
请安排一份 4 分钟框架，展示从灵感到成片的关键路径。
优缺点先安排检查项，下期根据实际发现的问题提出改进实验。
```

该案例会围绕“想做短剧但不知道拍什么”展开。展示灵感筛选、故事梗概、生成素材和成片检查，工具与操作路径以实际素材为准。

## 内容原则

用真实探索过程表达 learn in public。缺少证据时使用尝试和待验证的措辞。具体耗时、零代码、爆款或收入主张需要实际材料支持。下期预告围绕本次尚未解决的问题提出实验，评论问题用于收集观众感兴趣的工具或工作场景。

## 反馈

欢迎通过 Issues 提供匿名化案例、期望输出和实际输出。说明建议适用于单集还是长期风格，便于持续完善规则。
