# The Dark Side of the Moon

本项目用于测试大模型的 SVG 绘制能力，以《The Dark Side of the Moon》的 AppleMusic 动态专辑封面为参考，保存不同模型及 Harness / Agent 组合生成的 SVG 作品。

## 提示词

```text
使用 SVG 绘制 ../video/The_Dark_Side_of_the_Moon_1080x1080.mp4 视频，将 SVG 文件保存到当前模型目录，命名为：模型名称_思考深度_Harness或Agent名称.svg，严禁读取项目内其他文件。
```

在模型目录中使用该提示词。

## 原版视频与作品对比

[![原版视频预览](./video/The_Dark_Side_of_the_Moon_1080x1080-cover.jpg)](./video/The_Dark_Side_of_the_Moon_1080x1080.mp4)

（点击封面打开视频）

| 模型名称 • 思考等级 | Codex | Devin | DSH | Grok | pi |
| --- | --- | --- | --- | --- | --- |
| claude-fable-5.1 • max | — | [<img src="./claude-fable-5.1/claude-fable-5.1_max_devin-cli.svg" alt="claude-fable-5.1 • max — Devin" width="128">](./claude-fable-5.1/claude-fable-5.1_max_devin-cli.svg) | — | — | — |
| claude-opus-5 • max | — | [<img src="./claude-opus-5/claude-opus-5_max_Devin.svg" alt="claude-opus-5 • max — Devin" width="128">](./claude-opus-5/claude-opus-5_max_Devin.svg) | — | — | — |
| claude-sonnet-5 • max | — | [<img src="./claude-sonnet-5/claude-sonnet-5_max_Devin.svg" alt="claude-sonnet-5 • max — Devin" width="128">](./claude-sonnet-5/claude-sonnet-5_max_Devin.svg) | — | — | — |
| deepseek-v4.1-flash-expires-on-0910 • max | — | — | [<img src="./deepseek-v4.1-flash-expires-on-0910/deepseek-v4.1-flash-expires-on-0910_Max_DSH.svg" alt="deepseek-v4.1-flash-expires-on-0910 • max — DSH" width="128">](./deepseek-v4.1-flash-expires-on-0910/deepseek-v4.1-flash-expires-on-0910_Max_DSH.svg) | — | [<img src="./deepseek-v4.1-flash-expires-on-0910/deepseek-v4.1-flash-expires-on-0910_max_pi.svg" alt="deepseek-v4.1-flash-expires-on-0910 • max — pi" width="128">](./deepseek-v4.1-flash-expires-on-0910/deepseek-v4.1-flash-expires-on-0910_max_pi.svg) |
| gemini-3.8-flash • high | — | [<img src="./gemini-3.8-flash/gemini-3.8-flash_high_devin.svg" alt="gemini-3.8-flash • high — Devin" width="128">](./gemini-3.8-flash/gemini-3.8-flash_high_devin.svg) | — | — | — |
| glm-5.3-flash • max | — | [<img src="./glm-5.3-flash/glm-5.3-flash_max_devin.svg" alt="glm-5.3-flash • max — Devin" width="128">](./glm-5.3-flash/glm-5.3-flash_max_devin.svg) | — | — | — |
| gpt-5.6-luna • max | [<img src="./gpt-5.6-luna/gpt-5.6-luna_max_Codex.svg" alt="gpt-5.6-luna • max — Codex" width="128">](./gpt-5.6-luna/gpt-5.6-luna_max_Codex.svg) | — | — | — | [<img src="./gpt-5.6-luna/gpt-5.6-luna_max_pi.svg" alt="gpt-5.6-luna • max — pi" width="128">](./gpt-5.6-luna/gpt-5.6-luna_max_pi.svg) |
| gpt-5.6-sol • high | [<img src="./gpt-5.6-sol/gpt-5.6-sol_high_Codex.svg" alt="gpt-5.6-sol • high — Codex" width="128">](./gpt-5.6-sol/gpt-5.6-sol_high_Codex.svg) | — | — | — | — |
| gpt-5.6-sol • max | — | — | — | — | [<img src="./gpt-5.6-sol/gpt-5.6-sol_max_pi.svg" alt="gpt-5.6-sol • max — pi" width="128">](./gpt-5.6-sol/gpt-5.6-sol_max_pi.svg) |
| gpt-5.6-sol • ultra | [<img src="./gpt-5.6-sol/gpt-5.6-sol_ultra_Codex.svg" alt="gpt-5.6-sol • ultra — Codex" width="128">](./gpt-5.6-sol/gpt-5.6-sol_ultra_Codex.svg) | — | — | — | — |
| gpt-6-astra • high | [<img src="./gpt-6-astra/gpt-6-astra_high_Codex.svg" alt="gpt-6-astra • high — Codex" width="128">](./gpt-6-astra/gpt-6-astra_high_Codex.svg) | — | — | — | — |
| gpt-6-astra • max | — | — | — | — | [<img src="./gpt-6-astra/gpt-6-astra_max_pi.svg" alt="gpt-6-astra • max — pi" width="128">](./gpt-6-astra/gpt-6-astra_max_pi.svg) |
| gpt-6-astra • ultra | [<img src="./gpt-6-astra/gpt-6-astra_ultra_Codex.svg" alt="gpt-6-astra • ultra — Codex" width="128">](./gpt-6-astra/gpt-6-astra_ultra_Codex.svg) | — | — | — | — |
| grok-4.6 • xhigh | — | — | — | [<img src="./grok-4.6/grok-4.6_xhigh_Grok.svg" alt="grok-4.6 • xhigh — Grok" width="128">](./grok-4.6/grok-4.6_xhigh_Grok.svg) | [<img src="./grok-4.6/grok-4.6_xhigh_pi.svg" alt="grok-4.6 • xhigh — pi" width="128">](./grok-4.6/grok-4.6_xhigh_pi.svg) |
| kimi-k3 • max | — | [<img src="./kimi-k3/kimi-k3_max_Devin.svg" alt="kimi-k3 • max — Devin" width="128">](./kimi-k3/kimi-k3_max_Devin.svg) | — | — | — |

## 目录约定

- 按模型名称创建目录，将该模型生成的 SVG 文件放入对应目录。
- SVG 文件命名格式：`模型名称_思考深度_Harness或Agent名称.svg`。
- `Harness/Agent` 表示使用的 Harness 或 Agent 名称，文件名中不包含斜杠 `/`。
- `video/` 用于存放 1080 × 1080 正方形 AppleMusic 动态专辑封面参考视频。

```text
.
├── README.md
├── video/
│   └── The_Dark_Side_of_the_Moon_1080x1080.mp4
└── 模型名称/
    └── 模型名称_思考深度_Agent名称.svg
```

## 协议

本项目采用 [MIT 协议](./LICENSE)。参考视频及其封面预览不在 MIT 授权范围内，版权归原权利人。
