---
publish: true
title: Dolly
description: AI Agent
created: 2026-05-09 22:17:07
modified: 2026-07-22T16:07:49.721+08:00
tags:
  - project
cssclasses: ""
---


本来的构想是一个 AI 沟通网络结合区块链的。结果太复杂了（），搞了几个月搞了一些简单的。

搞出了两个中间东西：

- 第一个是 [Lumina](https://github.com/huasushis/Lumina)，是一个基于 Actor 模型的 ASL 架构语言？用来描述一个项目然后让 AI 来完成的。主要是有这个 Idea 的时候我还没有用 Claude Code，现在看 Claude Code 感觉完全不需要这个（），作为个人来用或许还行？bug 挺多，所以我第二个项目还是让 cc 用纯的 node.js 来写的。
- 第二个是 [Dolly](github.com/huasushis/Dolly)，是用来构建 agent 网络的原子 agent，目前可能写好了这个？反正 AI 跟我说写好了，我也没咋用过，我对此有一点怀疑。采用了一种比较新奇的上下文结构。
- 第三个，网络还没实现，我得一周实现出来，苦来兮苦。

---

上面主要是科学社会研讨课的内容。目前 Lumina 放弃状态。看不到使用的场景。而且很不完善。希望有人能接手吧。目前处于 On hold 的一个状态。

目前热火朝天的是 Dolly，一个 Agent 框架。相比暑假前又进行了一次设计理念和软件结构的大的改变与完善。由于项目过大，发现AI可能难以准确处理这么多的要求一次性。也和我语言描述不清楚或者具体细节没想清楚有关。两天把我 Qoder 4000 Credits 蹬完了。目前处于 Wait 状态。发现 GLM-5.2 对于这种超级大项目的能力应该强于 Qwen 3.7-max的。很疑惑 Qoder 的专家团模式里面 Leader 为什么没有 3.8。