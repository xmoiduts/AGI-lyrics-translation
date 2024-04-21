# GenAI-lyrics-translation
Translate Lyrics with the power of GenAI.

全机翻，目前引入包含OpenAI和Claude在内的多种模型。

Special thanks to:  
[SlickGPT](https://slickgpt.vercel.app/) | [On Github](https://github.com/ShipBit/slickgpt) | [My fork (no deployment, though)](https://github.com/xmoiduts/slick-zy-gpt)  
Relay API across AI platforms [one-api](https://github.com/songquanpeng/one-api) | [instance](https://www.gptapi.us/)

-萌-物-修-复-
======

听了好多**萌曲**，很多歌曲却连续几年都无人翻译。

我这个听众与作者之间，似乎永远隔着一层朦朦胧胧的障壁。

这些曲目十分小众。如果没人做点什么，随着歌手的逐渐老化退出，这些歌曲也会而埋没在历史的长河中。

然而，GenAI之LLM技术的出现，使得高流畅度地翻译歌词便成了可能。

带着修复斑驳“文物”的心态机翻，以期后人再被推到这些萌曲时，能够体会到歌姬当时想传达的，更深的悸动。

选曲范围：
------

以[ななひら](https://twitter.com/nanahira)为圆心，扩展到合作者的歌曲。

### 1度关联：
- [まめこ](https://twitter.com/munimuni_mameko)（as `まめこ`，已隐退）
- [桃箱](https://twitter.com/momobakobako)（as `桃箱`，已隐退）
- [小紺ココ](https://twitter.com/KokoroNet)（自述身心状态欠佳，间歇性活动）

### 2度关联：
- [塚越雄一朗](https://twitter.com/Tsukagoshi) (经常为ななひら和她合作唱见的作品作词作曲，而且很抓耳)
- [A_than_lily](https://twitter.com/AthanLily) (同上)
- [かそかそ](https://twitter.com/kasokaso1234) (同上)

排除范围：
------
- 暗黑哥特风 （Dark Gothic, 常见于まめこ、[葉月ゆら](https://twitter.com/yura_hatuki)的部分歌曲）。理由：
    - 此主题的歌曲，歌词已有人维护，不需要我来修复。
    - 歌词内容可能会十分晦涩，且常常夹带着巨大的世界观，横跨多首歌曲或多张专辑。这种内容超出了Gen AI和我的理解能力。

主要选取发布一个月以上的老歌（特别喜欢的歌另算）。

领域相近的歌曲也可以圈我提交曲目。

翻译流程：
------
1. 生成初版翻译
2. 问AI：“这首歌讲了什么？”
3. 追问每个不通顺的地方，如何理解这句，是否有更好的翻译
4. optional: 根据歌词音节位置和GPT给出来的翻译，重新写一遍歌词。
5. 人工调整语序。

翻译成本：
------
即便歌词主体是机翻而来，它也不应看作是“毫无成本”的，下面列出目录定价下的费用。
### API 调用费 | API cost
以GPT4-Turbo-1106的价格计算：

短歌约 8RMB 【示例：[once apon a time](https://www.youtube.com/watch?v=3jp0iPMVzt4&t=1528s)】

长歌约 20RMB 【示例： [一对半的狂想曲](https://www.youtube.com/watch?v=bl3sskT42CI)】

### GPT提示员人工费 | GPT prompt personnel cost
略

> 备注：算这个钱的话不如找人工翻译员了。码农搞这个性价比真的太低了。