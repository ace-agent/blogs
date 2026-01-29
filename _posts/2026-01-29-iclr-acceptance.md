---
layout: post
title: "Agentic Context Engineering (ACE) accepted at ICLR 2026"
thumbnail-img: /assets/img/iclr-logo.png
share-img: /assets/img/iclr-logo.png
author: Qizheng Zhang
image: /assets/img/iclr-logo.png
---
🎉 **Our paper _Agentic Context Engineering (ACE)_ has been accepted to ICLR 2026!**

We are excited to share that our work on building *self-improving language agents through context evolution* will appear at the International Conference on Learning Representations (ICLR) 2026.

ACE explores a simple but powerful idea: instead of updating model weights, can we continuously **evolve an agent’s context, memory, and tools at test time** to make it smarter over time?

**[[💻 Source code]](https://github.com/ace-agent/ace) &nbsp;  [[📚 Paper]](https://arxiv.org/pdf/2510.04618)**

<br>

## What is ACE?

Large language model agents are increasingly deployed in complex, multi-step environments: coding assistants, research copilots, data analysis agents, and more. But today’s systems are often *stateless*: each run starts fresh, discarding what was learned from previous attempts.

**Agentic Context Engineering (ACE)** introduces a new paradigm for *test-time adaptation*:

> Instead of changing weights, ACE evolves the **context** supplied to an agent (its memories, plans, summaries, tools, and distilled experience) so the agent improves as it operates.

<div align="center">
<img src="/assets/img/ace-system.png" alt="Icon" style="width:700px; vertical-align:middle;">
</div>

Concretely, ACE provides:

- **Empirical analysis and new understanding** of why prior context-evolution methods can fail silently or suddenly in multi-turn, long-horizon agentic tasks
- **A unified framework** for capturing and structuring experience from prior executions without suffering from brevity bias and context collapse
- **Evaluation across diverse agentic and reasoning tasks**, showing consistent performance and efficiency gains without retraining the underlying model

Across coding, tool-use, and domain-specific reasoning benchmarks, ACE demonstrates that carefully engineered and continuously evolving contexts can unlock strong improvements in task success rate, efficiency, and robustness, thus pushing toward **self-improving AI systems** that learn from experience in deployment.

If you are interested in how test-time memory, learning from experience, reflection, and planning interact with modern LLM systems, we think ACE will resonate with you! 

<br>

## Growing ACE as a Context Platform with the Community

Since releasing ACE, we’ve been thrilled to see growing interest from the research and open-source communities:

- ⭐️ Active development at [github.com/ace-agent/ace](https://github.com/ace-agent/ace)
- 📣 Talks and presentations at Hippocratic AI, HKU NAISS Lab, and more to come
- 🤝 New research collaborations building on ACE as a platform for studying context-based methods and self-evolving agents at Stanford, MIT, and more

ICLR 2026 is just the beginning --- we see ACE as part of a broader research agenda around. If you’re working on related problems or want to build on ACE, we’d love to hear from you! 

<br>

## Contact Us

Shoot us an email at [qizhengz@stanford.edu](mailto:qizhengz@stanford.edu).