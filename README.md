# Super-agent Explorer

Interactive concept explorer for the **Super-agent** architecture described in
DeepSeek Harness team's article 《Super-agent 设计探索：迈向更自主的 Agent 系统》(2026-10-31).

Styled after a "SYSTEMS EXPLORER" teaching-app look: topic catalog, mechanism
diagrams, step-by-step execution trace playback, scene comparison, and a
mechanism / pseudocode / source detail panel.

**5 topics** · 双层架构与订阅直通 · 上下文组织与链式召回 · 两级事件过滤 · 投机执行 · 存算分离与 BYOM

Each topic carries a **plain-language analogy (小白解读)** and a **real-world
scenario walkthrough (真实场景)** so non-experts can follow along.

Responsive down to phones: columns collapse into a single reading flow, the
architecture diagram and trace table scroll horizontally with an on-screen hint.

Keyboard: `Space` play/pause · `←`/`→` step.

Single self-contained `index.html` — no build step, no dependencies.

Source article: WeChat Official Account "DeepSeek Harness 团队" (https://mp.weixin.qq.com/s/zoS7GlReWPhfCjENGxXCdg). Prototype repo mentioned in the article: dsh-superagent-prototype. This page is an independent educational visualization, not affiliated with DeepSeek.
