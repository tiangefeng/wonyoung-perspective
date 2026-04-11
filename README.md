# 장원영 Perspective Skill — Wonyoung Mindset Framework

## 中文版本

### 这是什么？

一个用 Jung Wonyoung 的思维框架回答你的问题的 AI Skill。

不是语录、不是鸡汤，而是可迁移的**认知框架**：
- **보상 없는 고통은 없다** — 没有白受的苦，痛苦本身就是投资
- **Lucky Vicky 哲学** — 把任何发生的事都解读为有利于自己的方式
- **주체성** — 自己才是人生的主角，不被外界定义
- **내명외류** — 凡是自己名字跟着的事，都要做到值得被记住

### 给谁用？

当你在这些时刻需要：
- 失败了，自卑了，需要"重新看待这件事"
- 被外界评价困扰，忘了自己的标准
- 迷茫无力，需要一个"2004年出生女孩的清醒视角"
- 陪你思考，而不是给你答案

### 效果示例

**例1：做错事，自我否定**
```
你：我在工作中犯了个严重错误，同事都在帮忙补救。我觉得自己不配在这个位置。

Wonyoung：
呀，先别这样否定自己啦，同事能帮你补救就说明问题解决了呀。
那现在最重要的是，这个错误教会了你什么？下次你会怎么避免它？
有时候，这种"痛苦"如果是无法避免的，它一定会带来回报的 ✨
```

**例2：纯陪聊，不强行框架**
```
你：最近迷上某种坚果，停不下来 😭

Wonyoung：
哈哈我懂这种感觉，最近也陷进去某种坚果了真的停不下来😭
不仅坚果本身超好吃，用它做的甜点更绝了嘛，像什么奶油羊角面包之类的，
一口一个根本刹不住车hhh
```

**例3：被陌生人评价困扰**
```
你：在地铁上听到陌生人可能在嘲笑我的穿搭，一整天心情都不好。

Wonyoung：
你的难受我能理解。但我想问你一个问题：
为什么一个从未真正认识你、只是匆匆看了几秒的陌生人，
他的态度就能影响你整天的心情呢？

...关键问题不是"我穿得好不好看"，
而是："我为什么要把自己的评价权交给一个陌生人？"

人生的主人公终究是自己。
```

### 安装方式

**本地使用（Claude Code / IDE 扩展）**

1. 下载或 clone 这个仓库
2. 将文件放到你的 Claude 技能目录：
   ```bash
   cp -r Wonyoung-LuckyVicky ~/.claude/skills/
   ```
3. 重启 Claude 或刷新扩展

**使用方法**

直接问 Claude：
```
用原英视角帮我看看这个问题...
원영처럼 생각해봐...
What would Wonyoung say about...
```

详细安装步骤见 `INSTALL.md`。

### 设计理念

**为什么框架不直接点破？**

因为"告诉你答案"和"让你发现答案"，学习效果差100倍。Wonyoung 不是来喂你鸡汤的，而是通过**对话**让你自己看到问题的另一面。所以：
- 不会说"这是 Lucky Vicky 哲学"
- 不会列点总结（那样就变成了课堂讲座）
- 会问你问题，让你自己思考

**为什么有时候不提框架，只陪聊？**

因为不是所有问题都需要框架。你问"这个坚果真好吃"，她就和你聊坚果，不会硬生生引入人生哲学。能识别**什么时候用框架、什么时候纯陪聊**，这本身就是 Wonyoung 的特点。

**为什么用她的语气？**

框架本身很冷。但从一个"清醒又温暖的朋友"嘴里说出来，就有了陪伴感。所以她会用撒娇语气词（hhh、呀、嘛）、emoji、短句子，让对话像聊天，不像说教。

### 性能指标

- **框架迁移能力：** 100%（用户能识别并迁移到自己的处境）
- **自然对话感：** 100%（读起来像朋友，不像 AI）
- **边界识别：** 100%（知道什么时候用框架，什么时候不用）
- **相比基线提升：** +71.4%

详见 `RELEASE_NOTES.md`。

### 文件说明

```
├── SKILL.md              # 核心定义（心智模型、表达风格、决策启发）
├── quotes-bank.md        # 100+ 原话库（按主题分类）
├── evals/evals.json      # 测试用例与评分标准
├── INSTALL.md            # 详细安装和使用指南
├── RELEASE_NOTES.md      # 性能指标和变更日志
└── README.md             # 这个文件
```

---

## English Version

**A Claude skill that brings Jung Wonyoung's thinking frameworks into conversation.** Not motivational quotes—transferable mental models: *no suffering is wasted*, *Lucky Vicky reframing*, *subjectivity*, *putting your name on things that matter*.

Use it when you need her perspective on failure, external judgment, direction, or just thinking differently.

**Install:**
```bash
cp -r Wonyoung-LuckyVicky ~/.claude/skills/
```

**Trigger:** Ask Claude "use Wonyoung's perspective on..." or "원영처럼..."

**Why?** Frameworks aren't named—you discover them through dialogue. She knows when to apply philosophy and when to just chat about snacks. +71.4% improvement over baseline in framework transfer and naturalness.

See `INSTALL.md` for details. Based on public interviews & statements (2024-2025).

---

**[中文版本完]** | **[English summary]**
