<img src="./assets/avatar.png" width="150" align="right" alt="Teng Tu">

# Teng Tu (涂腾)

PhD student in Computer Science and Technology at Zhejiang University.

I work on **LLM post-training**, **agent evaluation**, **inference optimization**, and **data pricing/data markets**. My work combines algorithm design, reproducible experimentation, and systems engineering.

## Research Focus

- LLM post-training and reinforcement learning from verifiable rewards
- Agent evaluation and execution-driven systems
- Distributed inference and performance analysis
- Query pricing, data markets, and information leakage

## Public Research

### Information Leakage from Prices in Query-based Data Markets

ICDE 2026. The work studies how query prices can reveal information about data existence and data cardinality, and develops price-based attacks and a perturbed-pricing defense framework.

- [DOI](https://doi.org/10.1109/ICDE65706.2026.00209)
- [DBLP record](https://dblp.uni-trier.de/rec/conf/icde/TuPMCDY26.html)
- [PerPricer repository](https://github.com/TengTu0311/PerPricer)

## Selected Public Projects

- [PerPricer](https://github.com/TengTu0311/PerPricer) — Public implementation and experiments related to query-price information leakage and protection.
- [iDBPricer](https://github.com/ZJU-DataVIP-Lab/iDBPricer) — Research prototype for trading and pricing SPJ queries over incomplete data; includes an optional natural-language-to-SQL integration.
- [A-share quant research](https://github.com/TengTu0311/ashare-quant-research) — A reproducible research pipeline covering point-in-time data, factor research, machine learning, portfolio optimization, and bias diagnosis.

## Open-source Contributions

- **Merged:** [codex-island PR #45](https://github.com/ericjypark/codex-island/pull/45) — replaced a fabricated usage chart with persisted usage history and validation logic.
- **Ongoing contribution:** [vLLM-Ascend PR #21282](https://github.com/vllm-project/vllm-ascend/pull/21282) — DSpark V1/V2 comparison and performance evaluation tooling.
- **Technical investigation:** [verl issue #6894](https://github.com/verl-project/verl/issues/6894) — FSDP2/Ascend environment investigation.
- **Technical investigation:** [vLLM-Ascend issue #11160](https://github.com/vllm-project/vllm-ascend/issues/11160) — device compatibility and package investigation.
- **CANN / GitCode:** Contributed **five merged arch22 complex BLAS3 operators** to `cann/ops-blas`: [Cherk !347](https://gitcode.com/cann/ops-blas/merge_requests/347) · [Csyrk !348](https://gitcode.com/cann/ops-blas/merge_requests/348) · [Cher2k !349](https://gitcode.com/cann/ops-blas/merge_requests/349) · [Csymm !350](https://gitcode.com/cann/ops-blas/merge_requests/350) · [Chemm !559](https://gitcode.com/cann/ops-blas/merge_requests/559)

## 中文简介

浙江大学计算机科学与技术博士生，研究兴趣包括大模型后训练、Agent 评测与推理优化，以及数据定价和数据市场。公开作品主要包括 ICDE 2026 论文、PerPricer、iDBPricer 等研究项目，并参与 vLLM-Ascend、CANN 相关开源协作。

## Links

- [GitCode](https://gitcode.com/Euler_teng)
- [Email](mailto:tuteng@zju.edu.cn)
