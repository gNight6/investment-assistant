# 投资助手

用于 Codex 的投资分析 skill，调用名为 `$investment-assistant`。

## 功能

- 核查当前市场数据，结合基本面、技术结构和市场事件分析投资标的。
- 根据投资期限、现有持仓与可接受亏损，提出买入、持有、减仓、退出或观望建议。
- 给出仓位依据、进场条件、退出条件及结论失效条件。
- 整理案例与策略证据，区分作者主张、分析推断和未经核验的信息。

## 安装

将本仓库目录放入 `~/.codex/skills/investment-assistant/`，确保该目录下直接包含 `SKILL.md`。Windows 默认目录为 `C:\Users\你的用户名\.codex\skills\investment-assistant\`。

## 使用示例

```text
使用 $investment-assistant 分析ETH是否值得买入。
投资期限3个月，预算2万元，可接受亏损10%，不使用杠杆。
请核查当前数据，提出建议并说明仓位依据与退出条件。
```

## 文件

- `SKILL.md`：入口与工作要求。
- `agents/openai.yaml`：显示名称与示例提示。
- `references/investment-analysis.md`：投资分析与建议流程。
- `references/channel-summary.md`：来源资料总结与覆盖边界。
- `references/video-catalog.md`：本次收集的视频标题和来源链接。

## 资料范围

频道参考资料收集于2026-09-28，主要为39条公开视频标题、频道简介和部分视频说明，未完成全文字幕分析或历史全量覆盖。具体投资分析需另行核查当前数据；历史收益与宣传措辞不代表已验证策略。本skill不执行下单或转账。
