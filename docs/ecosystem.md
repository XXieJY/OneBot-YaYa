## SDK／开发框架

对于使用下面这些语言的机器人开发者，如果不想自己处理繁杂的请求和解析操作，可以尝试使用已经封装好的 SDK 或开发框架。

| 语言               | 通信方式                                                     | 地址                                                         | 核心作者               |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| Python             | HTTP, 反向 WS                                                | [nonebot/nonebot](https://github.com/nonebot/nonebot)        | richardchien yanyongyu |
| Python             | HTTP, 反向 WS                                                | [nonebot/aiocqhttp](https://github.com/nonebot/aiocqhttp)    | richardchien           |
| Node.js            | 正向 WS                                                      | [momocow/node-cq-websocket](https://github.com/momocow/node-cq-websocket) | momocow                |
| Node.js            | HTTP, 正向 WS, 反向 WS                                       | [koishijs/koishi](https://github.com/koishijs/koishi)        | Shigma                 |
| Node.js            | 正向 WS                                                      | [CaoMeiYouRen/node-coolq-robot](https://github.com/CaoMeiYouRen/node-coolq-robot) | CaoMeiYouRen           |
| Node.js            | HTTP                                                         | [XHMM/lemon-bot](https://github.com/XHMM/lemon-bot)          | XHMM                   |
| JavaScript         | 正向 WS                                                      | [pandolia/js-bot](https://github.com/pandolia/js-bot)        | pandolia               |
| Deno               | 反向 WS                                                      | [nenojs/deno-cqhttp](https://github.com/nenojs/deno-cqhttp)  | rikakomoe              |
| PHP                | 反向 WS                                                      | [zhamao-robot/zhamao-framework](https://github.com/zhamao-robot/zhamao-framework) | crazywhalecc           |
| PHP                | HTTP                                                         | [LovelyA72/YeziiBot-v2](https://github.com/LovelyA72/YeziiBot-v2) | LovelyA72              |
| Java               | HTTP                                                         | [HyDevelop/PicqBotX](https://github.com/HyDevelop/PicqBotX)  | Hykilpikonna           |
| Java Kotlin Groovy | 反向 WS                                                      | [lz1998/Spring-CQ](https://github.com/lz1998/Spring-CQ)（[教程](https://www.bilibili.com/video/av89649630/)） | lz1998                 |
| Java               | HTTP                                                         | [ForteScarlet/simple-robot-core](https://github.com/ForteScarlet/simple-robot-core) | ForteScarlet           |
| Java               | HTTP                                                         | [thevsk/cqhttp-java-jfinal-sdk](https://github.com/thevsk/cqhttp-java-jfinal-sdk) | thevsk                 |
| Kotlin             | HTTP                                                         | [JuerGenie/juerobot](https://github.com/JuerGenie/juerobot)  | JuerGenie              |
| Go                 | **API:** HTTP, 正向 WS **Event:** HTTP, 长轮询, 正向 WS, 反向 WS | [catsworld/qq-bot-api](https://github.com/catsworld/qq-bot-api) | catsworld rikakomoe    |
| Go                 | 正向 WS                                                      | [wdvxdr1123/ZeroBot](https://github.com/wdvxdr1123/ZeroBot)  | wdvxdr1123             |
| C#                 | HTTP, 正向 WS                                                | [int-and-his-friends/Sisters.WudiLib](https://github.com/int-and-his-friends/Sisters.WudiLib) | bleatingsheep          |
| C#                 | HTTP, 正向 WS, 反向 WS                                       | [frank-bots/cqhttp.Cyan](https://github.com/frank-bots/cqhttp.Cyan) | frankli0324            |
| C#                 | 反向 WS                                                      | [cqbef/cqhttp.WebSocketReverse.NETCore](https://github.com/cqbef/cqhttp.WebSocketReverse.NETCore) | cqbef                  |
| C#                 | 反向 WS                                                      | [Yukrai103/Sora](https://github.com/Yukrai103/Sora)          | Yukrai103              |
| PowerShell         | HTTP                                                         | [cqmoe/cqhttp-powershell-sdk](https://github.com/cqmoe/cqhttp-powershell-sdk) | richardchien           |
| Lua                | HTTP, 正向 WS                                                | [cleoold/cqhttp-lua53-sdk](https://github.com/cleoold/cqhttp-lua53-sdk) | cleoold                |

## 应用案例

| 项目地址                                                     | 简介或功能                                                   | 依赖                                                         | 核心作者                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------------- |
| [Kyomotoi/ATRI](https://github.com/Kyomotoi/ATRI)            | 名为 [ATRI](https://atri-mdm.com/) 的BOT                     | [nonebot2](https://github.com/nonebot/nonebot2)              | [Kyomotoi](https://github.com/Kyomotoi)               |
| [he0119/CoolQBot](https://github.com/he0119/CoolQBot)        | FF14 PCR 点歌 等                                             | [nonebot2](https://github.com/nonebot/nonebot2)              | [he0119](https://github.com/he0119)                   |
| [Lancercmd/rauthman](https://github.com/Lancercmd/nonebot_plugin_rauthman) | 功能授权管理                                                 | [nonebot2](https://github.com/nonebot/nonebot2)              | [Lancercmd](https://github.com/Lancercmd)             |
| [Pzzzzz5142/Pbot](https://github.com/Pzzzzz5142/Pbot)        | 搜图 点歌 戳一戳 早晚安 查梗 等                              | [nonebot2](https://github.com/nonebot/nonebot2)              | [Pzzzzz5142](https://github.com/Pzzzzz5142)           |
| [SK-415/HarukaBot](https://github.com/SK-415/HarukaBot)      | B站动态、直播监控                                            | [nonebot2](https://github.com/nonebot/nonebot2)              | [SK-415](https://github.com/SK-415)                   |
| [jiang-hr/qq-bot-ai](https://github.com/jiang-hr/qq-bot-ai)  | 并不涩的涩图 anti VPN 等                                     | [nonebot2](https://github.com/nonebot/nonebot2)              | [jiang-hr](https://github.com/jiang-hr)               |
|                                                              |                                                              |                                                              |                                                       |
| [Kyomotoi/ATRI(master分支)](https://github.com/Kyomotoi/ATRI/tree/master) | 名为 [ATRI](https://atri-mdm.com/) 的BOT                     | [nonebot](https://github.com/nonebot/nonebot)                | [Kyomotoi](https://github.com/Kyomotoi)               |
| [fz6m/nonebot-plugin](https://github.com/fz6m/nonebot-plugin) | 各种即开即用、良好兼容的插件                                 | [nonebot](https://github.com/nonebot/nonebot)                | [fz6m](https://github.com/fz6m)                       |
| [remiliacn/qqBot](https://github.com/remiliacn/qqBot)        | 油管推特监控 涩图搜图 娱乐 等                                | [nonebot](https://github.com/nonebot/nonebot)                | [remiliacn](https://github.com/remiliacn)             |
| [haowen-li/DicePP](https://github.com/haowen-li/DicePP)      | 骰娘                                                         | [nonebot](https://github.com/nonebot/nonebot)                | [haowen-li](https://github.com/haowen-li)             |
| [Ailitonia/nonebot_miya](https://github.com/Ailitonia/nonebot_miya) | 名为 miya 的BOT                                              | [nonebot](https://github.com/nonebot/nonebot)                | [Ailitonia](https://github.com/Ailitonia)             |
| [rMuchan/kasumi-challenge](https://github.com/rMuchan/kasumi-challenge) | 角色养成文字冒险RPG                                          | [nonebot](https://github.com/nonebot/nonebot)                | [rMuchan](https://github.com/rMuchan)                 |
| [Angel-Hair/XUN_Bot](https://github.com/Angel-Hair/XUN_Bot)  | RSS 识图 识番搜番 天气地震查询 日语词典 翻译 检查状态        | [nonebot](https://github.com/nonebot/nonebot)                | [Angel-Hair](https://github.com/Angel-Hair)           |
| [Li-mz/KirinBot](https://github.com/Li-mz/KirinBot)          | NG词语游戏 扫雷 剧本杀                                       | [nonebot](https://github.com/nonebot/nonebot)                | [Li-mz](https://github.com/Li-mz)                     |
| [APicebar/LuoguBot](https://github.com/APicebar/LuoguBot)    | Luogu CodeForces AtCoder                                     | [nonebot](https://github.com/nonebot/nonebot)                | [APicebar](https://github.com/APicebar)               |
| [mnixry/coolQPythonBot](https://github.com/mnixry/coolQPythonBot) | 识图识番搜图涩图 番剧查询 B站视频解析 RSS 维基百科 广播 欢迎 一言 嘴臭 身份生成 | [nonebot](https://github.com/nonebot/nonebot)                | [mnixry](https://github.com/mnixry)                   |
| [damLeafsnow/QQMakeGrassBot](https://github.com/damLeafsnow/QQMakeGrassBot) | 种菜 COC 生草 签到 翻译 搜图识图 B站综合                     | [nonebot](https://github.com/nonebot/nonebot)                | [damLeafsnow](https://github.com/damLeafsnow)         |
| [cleoold/sendo-erika](https://github.com/cleoold/sendo-erika) | 自定义回复 点歌 签到 运势 谷歌搜索 百度热搜 碧蓝建造         | [nonebot](https://github.com/nonebot/nonebot)                | [cleoold](https://github.com/cleoold)                 |
| [mgsky1/FG](https://github.com/mgsky1/FG)                    | 词云                                                         | [nonebot](https://github.com/nonebot/nonebot)                | [mgsky1](https://github.com/mgsky1)                   |
| [Singularity0909/awesome-bot](https://github.com/Singularity0909/awesome-bot) | 涩图打击 聊天 知乎日报 一言 笑话 土味情话 狗屁不通生成器     | [nonebot](https://github.com/nonebot/nonebot)                | [Singularity0909](https://github.com/Singularity0909) |
| [Li-mz/DicingKirin](https://github.com/Li-mz/DicingKirin)    | COC TRPG                                                     | [nonebot](https://github.com/nonebot/nonebot)                | [Li-mz](https://github.com/Li-mz)                     |
| [Quan666/ELF_RSS](https://github.com/Quan666/ELF_RSS)        | RSS                                                          | [nonebot](https://github.com/nonebot/nonebot)                | [Quan666](https://github.com/Quan666)                 |
| [the-25th-Nova/ArchiSteamFarm](https://github.com/the-25th-Nova/ArchiSteamFarm-Nonebot) | 查询 steam 状态                                              | [nonebot](https://github.com/nonebot/nonebot)                | [the-25th-Nova](https://github.com/the-25th-Nova)     |
| [SDchao/CoolBot](https://github.com/SDchao/CoolBot)          | 猫图检测 祖安对线 等                                         | [nonebot](https://github.com/nonebot/nonebot)                | [SDchao](https://github.com/SDchao)                   |
| [XiaSweet/xxt-QQbot](https://github.com/XiaSweet/xxt-QQbot)  | 皇室战争 玩家BOT                                             | [nonebot](https://github.com/nonebot/nonebot)                | [XiaSweet](https://github.com/XiaSweet)               |
| [JadyXuan/NonebotAVG](https://github.com/JadyXuan/NonebotAVG) | 文字冒险游戏制作器                                           | [nonebot](https://github.com/nonebot/nonebot)                | [JadyXuan](https://github.com/JadyXuan)               |
| [noahzark/yahourcall](https://github.com/noahzark/yahourcall) | 报时                                                         | [nonebot](https://github.com/nonebot/nonebot)                | [noahzark](https://github.com/noahzark)               |
| [Scarlet-Climax/amethyst](https://github.com/Scarlet-Climax/nonebot-amethyst) | 车万 神秘BOT                                                 | [nonebot](https://github.com/nonebot/nonebot)                | [Scarlet-Climax](https://github.com/Scarlet-Climax)   |
| [Watanabe-Asa/eqa](https://github.com/Watanabe-Asa/eqa)      | 自定义问答                                                   | [nonebot](https://github.com/nonebot/nonebot)                | [Watanabe-Asa](https://github.com/Watanabe-Asa)       |
| [treasurew-kb/shinelily](https://github.com/treasurew-kb/shinelily) | 和风天气 教学习 彩虹屁 早晚安                                | [nonebot](https://github.com/nonebot/nonebot)                | [treasurew-kb](https://github.com/treasurew-kb)       |
| [farewell12345/nonebot](https://github.com/farewell12345/nonebot) | 涩图 早晚安 一言 老婆生成器 祖安对线 夸夸器 steam促销 喜加一推送 翻译 天气 | [nonebot](https://github.com/nonebot/nonebot)                | [farewell12345](https://github.com/farewell12345)     |
| [mdamingyang/coolq_setu_bot](https://github.com/mdamingyang/coolq_setu_bot) | 涩图                                                         | [nonebot](https://github.com/nonebot/nonebot)                | [mdamingyang](https://github.com/mdamingyang)         |
| [adoption-loli/CQ_idleGame](https://github.com/adoption-loli/CQ_idleGame) | 放置游戏                                                     | [nonebot](https://github.com/nonebot/nonebot)                | [adoption-loli](https://github.com/adoption-loli)     |
| [zuckerbergang/comlex-bot](https://github.com/zuckerbergang/comlex-bot) | 每日一句英语                                                 | [nonebot](https://github.com/nonebot/nonebot)                | [zuckerbergang](https://github.com/zuckerbergang)     |
| [ZombieFly/AXbot](https://github.com/ZombieFly/AXbot)        | MC wiki BOT                                                  | [nonebot](https://github.com/nonebot/nonebot)                | [ZombieFly](https://github.com/ZombieFly)             |
| [Lmg66/QQrobot](https://github.com/Lmg66/QQrobot)            | 涩图 图灵聊天 谁是卧底 点歌 识番 天气                        | [nonebot](https://github.com/nonebot/nonebot)                | [Lmg66](https://github.com/Lmg66)                     |
| [hsc10705581/FiveCardStud](https://github.com/hsc10705581/FiveCardStud) | 梭哈                                                         | [nonebot](https://github.com/nonebot/nonebot)                | [hsc10705581](https://github.com/hsc10705581)         |
| [farewell12345/Violet](https://github.com/farewell12345/Violet) | 老婆生成器                                                   | [nonebot](https://github.com/nonebot/nonebot)                | [farewell12345](https://github.com/farewell12345)     |
| [allwaysLove/workNotify](https://github.com/allwaysLove/CourseworkNotificationRobot) | 作业通知                                                     | [nonebot](https://github.com/nonebot/nonebot)                | [allwaysLove](https://github.com/allwaysLove)         |
| [Inkotake/inno](https://github.com/Inkotake/inno)            | 猜拳 等                                                      | [nonebot](https://github.com/nonebot/nonebot)                | [Inkotake](https://github.com/Inkotake)               |
| [lv101/QrobotPlus](https://github.com/lv101/QrobotPlus)      | 修仙 等                                                      | [nonebot](https://github.com/nonebot/nonebot)                | [lv101](https://github.com/lv101)                     |
| [Yoshino-s/buubot](https://github.com/Yoshino-s/buubot)      | 舔狗日记 图灵聊天 等                                         | [nonebot](https://github.com/nonebot/nonebot)                | [Yoshino-s](https://github.com/Yoshino-s)             |
| [dwxrycb123/Akina3](https://github.com/dwxrycb123/Akina3)    | 名为 秋菜酱 的BOT                                            | [nonebot](https://github.com/nonebot/nonebot)                | [dwxrycb123](https://github.com/dwxrycb123)           |
| [bluemomo112/kuakua_chatbot](https://github.com/bluemomo112/Nonebot_based_kuakua_chatbot) | 夸夸器 一言                                                  | [nonebot](https://github.com/nonebot/nonebot)                | [bluemomo112](https://github.com/bluemomo112)         |
| [Tobias272727/azusabot](https://github.com/Tobias272727/azusabot) | 涩图                                                         | [nonebot](https://github.com/nonebot/nonebot)                | [Tobias272727](https://github.com/Tobias272727)       |
| [JarvisHH/KurumiBot](https://github.com/JarvisHH/KurumiBot)  | 记事本                                                       | [nonebot](https://github.com/nonebot/nonebot)                | [JarvisHH](https://github.com/JarvisHH)               |
| [loli-fish/destiny_tarrot-CQnonebot](https://github.com/loli-fish/destiny_tarrot-CQnonebot) | 塔罗牌占卜                                                   | [nonebot](https://github.com/nonebot/nonebot)                | [loli-fish](https://github.com/loli-fish)             |
| [jinserrr/strings](https://github.com/jinserrr/strings)      | 名为 Strings 的BOT                                           | [nonebot](https://github.com/nonebot/nonebot)                | [jinserrr](https://github.com/jinserrr)               |
| [ruokbb/Greedy-Island](https://github.com/ruokbb/Greedy-Island) | 贪婪岛 集卡游戏                                              | [nonebot](https://github.com/nonebot/nonebot)                | [ruokbb](https://github.com/ruokbb)                   |
| [stare-star/qqbot](https://github.com/stare-star/qqbot)      | 多功能BOT                                                    | [nonebot](https://github.com/nonebot/nonebot)                | [stare-star](https://github.com/stare-star)           |
| [nonebot/nonebot-anime](https://github.com/nonebot/nonebot-anime) | 番剧查询                                                     | [nonebot](https://github.com/nonebot/nonebot)                | [Richard Chien](https://github.com/richardchien)      |
| [nonebot/nonebot-alarm](https://github.com/nonebot/nonebot-alarm) | 定时闹钟                                                     | [nonebot](https://github.com/nonebot/nonebot)                | [yanyongyu](https://github.com/yanyongyu)             |
| [artisanbox/PTA_Bot](https://github.com/artisanbox/PTA_Bot)  | 定时任务                                                     | [nonebot](https://github.com/nonebot/nonebot)                | [artisanbox](https://github.com/artisanbox)           |
| [AnotherBlank/ChickenBot](https://github.com/AnotherBlank/ChickenBot) | 方舟&碧蓝抽卡 学习禁言                                       | [nonebot](https://github.com/nonebot/nonebot)                | [AnotherBlank](https://github.com/AnotherBlank)       |
|                                                              |                                                              |                                                              |                                                       |
| [Bluefissure/OtterBot](https://github.com/Bluefissure/OtterBot) | FF14 玩家BOT                                                 | 云BOT                                                        | [Bluefissure](https://github.com/Bluefissure)         |
|                                                              |                                                              |                                                              |                                                       |
| [MahoMaster/300Bot](https://github.com/MahoMaster/300Bot)    | 龙王请安 等                                                  | Golang                                                       | [MahoMaster](https://github.com/MahoMaster)           |
| [Billdex/CQGitBot](https://github.com/Billdex/CQGitBot)      | GitHub 监控                                                  | Golang                                                       | [Billdex](https://github.com/Billdex)                 |
| [LCBHSStudent/QQ_BOT_GAME](https://github.com/LCBHSStudent/QQ_BOT_GAME) | 游戏BOT                                                      | [qq-bot-api](https://github.com/catsworld/qq-bot-api)        | [LCBHSStudent](https://github.com/LCBHSStudent)       |
| [guawoo/QQ-Group-Bridge-Bot](https://github.com/guawoo/QQ-Group-Bridge-Bot) | 多群互相转发                                                 | Golang                                                       | [guawoo](https://github.com/guawoo)                   |
| [b11p/OsuQqBotForNewbieGroup](https://github.com/b11p/OsuQqBotForNewbieGroup) | osu! 新人群 BOT                                              | [WudiLib](https://github.com/int-and-his-friends/Sisters.WudiLib) | [b11p](https://github.com/b11p)                       |
| [arttnba3/a3bot](https://github.com/arttnba3/a3bot)          | 自用型BOT                                                    | [springCQ](https://github.com/lz1998/Spring-CQ)              | [arttnba3](https://github.com/arttnba3)               |
| [ColorfulGhost/qqbot](https://github.com/ColorfulGhost/qqbot) | Minecraft RCON 等                                            | Java                                                         | [ColorfulGhost](https://github.com/ColorfulGhost)     |
| [Tsuk1ko/cq-picsearcher-bot](https://github.com/Tsuk1ko/cq-picsearcher-bot) | 搜图搜番搜本子涩图 群发 定时 anti小程序 方舟公开招募         | Node.js                                                      | [Tsuk1ko](https://github.com/Tsuk1ko)                 |
| [satouriko/cqhttp-twitter-bot](https://github.com/satouriko/cqhttp-twitter-bot) | Twitter订阅                                                  | TypeScript                                                   | [satouriko](https://github.com/satouriko)             |
| [XHMM/*bot*-xiaoxin](https://github.com/XHMM/bot-xiaoxin)    | 名为 小心 的BOT                                              | [lemon-bot](https://github.com/XHMM/lemon-bot)               | [XHMM](https://github.com/XHMM)                       |
| [SoraYama/qqbot](https://github.com/SoraYama/qqbot)          | 砍口垒 玩家BOT 喂宠物                                        | TypeScript                                                   | [SoraYama](https://github.com/SoraYama)               |
