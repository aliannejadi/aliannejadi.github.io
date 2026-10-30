---
layout: page
permalink: /resources/
title: data & code
description: Datasets, benchmarks, and code released with our papers. Every publication with released code also has a "code" button on the publications page.
nav: true
nav_order: 4
---

### Benchmarks and test collections

- **[Total Recall QA](https://github.com/mahta-r/total-recall-qa)** (SIGIR 2026): a verifiable evaluation suite for deep research agents.
- **[TREC iKAT](https://www.trecikat.com/)** (2023–2025): test collections for personalized conversational search. 2023 collection and tools: [GitHub](https://github.com/irlabamsterdam/iKAT) ([SIGIR 2024](https://arxiv.org/abs/2405.02637)); the 2025 collection appears at SIGIR 2026.
- **[CONE-RAG](https://github.com/irlabamsterdam/CONE-RAG)** (SIGIR 2025): gold nuggets for evaluating personalized conversational RAG ([paper](https://arxiv.org/abs/2503.09902)).
- **[LLMJudge](https://github.com/llm4eval/LLMJudge)**: the LLM4Eval relevance-judgment challenge, and **[Judging the Judges](https://llm4eval.github.io/LLMJudge-benchmark/)**, a collection of LLM-generated relevance judgments ([paper](https://arxiv.org/abs/2502.13908)).
- **[RAVENEA](https://github.com/yfyuan01/RAVENEA)** (ICLR 2026): multimodal retrieval-augmented visual culture understanding ([paper](https://openreview.net/forum?id=4zAbkxQ23i)).
- **[MCPQA](https://github.com/yfyuan01/MCPQA)** (EMNLP 2024): multilingual cross-market product question answering.
- **[PSCon](https://github.com/JieZouIR/PSCon)** (SIGIR 2025): product search through conversations.
- **[XMarket](https://xmrec.github.io/)**: cross-market product recommendation data from Amazon, used in the [XMRec WSDM Cup](https://xmrec.github.io/wsdmcup/) ([CIKM 2021](https://arxiv.org/abs/2109.05929)).
- **[ClariQ](https://github.com/aliannejadi/ClariQ)**: the ConvAI3 challenge on clarifying questions in open-domain dialogue ([report](https://arxiv.org/abs/2009.11352)).
- **[Qulac](https://github.com/aliannejadi/qulac)** (SIGIR 2019): Questions for Lack of Clarity in open-domain information-seeking conversations.
- **[ANTIQUE](https://ciir.cs.umass.edu/downloads/Antique/)** (ECIR 2020): non-factoid question answering from Yahoo! Answers ([paper](https://arxiv.org/pdf/1905.08957.pdf)).
- **[ConvKey](https://github.com/aliannejadi/ConvKey)**: keywords from news articles and mixed-initiative conversations for conversational document ranking ([paper](https://arxiv.org/abs/2109.05979)).
- **[CAsTUR](https://github.com/aliannejadi/castur)** (CHIIR 2020): which earlier TREC CAsT 2019 turns are useful context for an utterance ([paper](https://arxiv.org/pdf/1912.10554.pdf)).
- **[IGLU](https://github.com/iglu-contest/iglu)**: the NeurIPS competition on interactive grounded language understanding, with its [gridworld environment](https://github.com/iglu-contest/gridworld).

### Conversational search and RAG

- **[ChatR1](https://github.com/SimonLupart/ChatR1)** (ACL 2026): reinforcement learning for conversational reasoning and retrieval-augmented QA. Models on [Hugging Face](https://huggingface.co/collections/slupart/chatr1).
- **[DiSCo](https://github.com/SimonLupart/disco-conv-splade)** (SIGIR 2025): LLM distillation for efficient sparse retrieval in conversational search.
- **[Zef-CNP](https://github.com/lulili0963/Zef-CNP)** (ECIR 2025): zero-shot clarification need prediction.
- **[SimQuAC](https://github.com/ZahraAbbasiantaeb/SimQUAC)** (WSDM 2024): simulating human-to-human conversational QA with LLMs.
- **[MQC](https://github.com/yfyuan01/MQC)** (WWW 2024): multimodal clarifying questions.
- **[USi](https://github.com/isekulic/USi)** (WSDM 2022): user simulator for evaluating mixed-initiative conversational search.
- **[PersonalizedCIR](https://github.com/EricLangezaal/PersonalizedCIR)** (SIGIR 2025): LLM variability in personalized conversational retrieval.

### Evaluation and query performance prediction

- **[Re-rankers as judges](https://github.com/ChuanMeng/reranker-as-judge)** (2026): using re-rankers as relevance judges.
- **[LLM-generated rubrics](https://github.com/Clemenciah/llm-generated-rubrics)** (EACL Findings 2026): LLMs designing and applying evaluation rubrics.
- **[QPP-GenRE](https://github.com/ChuanMeng/QPP-GenRE)** (TOIS 2025): query performance prediction with LLM-generated relevance judgments.
- **[LLMs for relevance judgment](https://github.com/ZahraAbbasiantaeb/LLMs-for-relevance-judgment-assessment)** (ECIR 2025): improving the reusability of conversational search test collections.
- **[RLT4Reranking](https://github.com/ChuanMeng/RLT4Reranking)** (SIGIR 2024): ranked list truncation for LLM-based re-ranking.
- **[QPP4CS](https://github.com/ChuanMeng/QPP4CS)** (SIGIR 2023): query performance prediction for conversational search.
- **[LLMCrowdDialogueEval](https://github.com/Clemenciah/LLMCrowdDialogueEval)** (SIGIR 2024) and **[Effects of Dialogue Context](https://github.com/Clemenciah/Effects-of-Dialogue-Context)** (NAACL Findings 2024): crowdsourced and LLM-based evaluation of dialogue systems.
- **[CAUSE](https://github.com/aminvenv/use)** (ACL Findings 2024): counterfactual assessment of user satisfaction estimation.
- **[CQSatisfaction](https://github.com/rahmanidashti/CQSatisfaction)** (EACL Findings 2024): clarifying questions and user satisfaction.
- **[ChatGPT-RetrievalQA](https://github.com/arian-askari/ChatGPT-RetrievalQA)**: synthetic documents for training cross-encoder re-rankers.

### Reproducibility studies

- **[Hypencoder reproduction](https://github.com/arneeichholtz/Hypencoder-reprod)** (SIGIR 2026)
- **[The Power of Noise reproduction](https://github.com/ina0105/The-Power-of-Noise-Reproduction)** (SIGIR 2026)
- **[NevIR reproduction](https://github.com/thijmennijdam/NevIR-reproducibility)** (SIGIR 2025)
- **[Product-side fairness in bundle recommendation](https://github.com/Rec4Fun/Fairness_Bundle_RecSys25)** (RecSys 2025)

### Recommendation, fairness, and bias

- **[Repbias_NBR](https://github.com/lynEcho/Repbias_NBR)** (ECIR 2025) and **[TREX](https://github.com/lynEcho/TREX)** (SIGIR 2024): beyond-accuracy next-basket recommendation.
- **[MSMGenderBias](https://github.com/MaryamMousavian/MSMGenderBias)** (ICTIR 2025): LLMs for gender bias detection and mitigation in ranking.
- **[Outlier visual saliency](https://github.com/arezooSarvi/outlier-visual-saliency)** (TOIS 2026) and **[outlier bias](https://github.com/arezooSarvi/outlierbias)** (SIGIR 2023): outliers in product search.
- **[OMIT](https://github.com/arezooSarvi/OMIT_Fair_ranking)** (WSDM 2022): fair ranking with outliers.
- **[Efficient XMRec](https://github.com/samarthbhargav/efficient-xmrec)** (ECIR 2023) and **[FOREC](https://github.com/hamedrab/FOREC)** (CIKM 2021): cross-market recommendation.
- **[CalibrationFair](https://github.com/rahmanidashti/CalibrationFair)** (CIKM 2022) and **[FairRecSys](https://github.com/rahmanidashti/FairRecSys)** (SIGIR 2022): calibrated and user-oriented fair recommendation.
- **[InsightTab](https://github.com/yfyuan01/InsightTab)** (EMNLP Findings 2025): insight distillation for few-shot tabular classification.
- **[MIMICS-EL benchmark](https://github.com/isekulic/mimics-EL-benchmark)** (ECIR 2021): user engagement prediction for clarification.
- POI recommendation: **[SUCP](https://github.com/Seyedhosseinzadeh/SUCP)** (IP&M 2022), **[ContextsPOI](https://rahmanidashti.github.io/ContextsPOI/)** (TOIS 2022), **[STACP](https://github.com/rahmanidashti/STACP)** (ECIR 2020), **[LGLMF](https://github.com/rahmanidashti/LGLMF)** (AIRS 2019).

### Multimodal assistants

- **[LEGO Co-builder](https://github.com/peterhuang-coding/LEGO-Co-builder)** (ICMI 2026): fine-grained vision-language modeling for multimodal assembly assistants.

### Mobile search and app usage

- **[LSApp](https://github.com/aliannejadi/LSApp)**: ~600K sequential mobile app usage records from ~300 users ([TOIS](https://arxiv.org/pdf/2101.03394)).
- **[ISTAS](https://github.com/aliannejadi/istas)** (CIKM 2018): in situ cross-app mobile search queries collected with **[uSearch](https://github.com/aliannejadi/uSearch)**. [Project page]({{ '/istas.html' | relative_url }})
- **[UniMobile](https://github.com/aliannejadi/unimobile)** (SIGIR 2018): cross-app mobile search queries. [Project page]({{ '/unimobile.html' | relative_url }})
- **[Omicron](https://github.com/aliannejadi/Omicron)**: the app we used to study user behavior in context ([paper](http://arxiv.org/abs/1812.07081)).
- **[TREC-CS](/data.html#data)**: the collection we crawled for the TREC Contextual Suggestion track.

More code is on [GitHub](https://github.com/aliannejadi) and from [IRLab Amsterdam](https://github.com/irlabamsterdam).
