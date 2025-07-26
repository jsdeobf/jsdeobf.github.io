# JsDeObsBench: Measuring and Benchmarking LLMs for JavaScript Deobfuscation

<div align="center">
<p> 
  <a href="https://arxiv.org/abs/2506.20170"><img
      src="https://img.shields.io/badge/Paper-CCS'25-a55fed.svg?style=for-the-badge" alt="paper"
      class="img-fluid" /></a>
  <a href="https://github.com/Ch3nYe/JsDeObsBench"><img
      src="https://img.shields.io/badge/github-Benchmark-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"
      alt="github" class="img-fluid" /></a>
  <a href="https://jsdeobf.github.io"><img
      src="https://img.shields.io/badge/Leaderboard-jsdeobf.github.io-F7DF1E.svg?style=for-the-badge" alt="leaderboard"
      class="img-fluid" /></a>
</p> 
</div>

## Introduction

Deobfuscating JavaScript (JS) code poses a significant challenge in web security, particularly as obfuscation techniques are frequently used to conceal malicious activities within scripts. While Large Language Models (LLMs) have recently shown promise in automating the deobfuscation process, transforming detection and mitigation strategies against these obfuscated threats, a systematic benchmark to quantify their effectiveness and limitations has been notably absent. To address this gap, we present JsDeObsBench, a dedicated benchmark designed to rigorously evaluate the effectiveness of LLMs in the context of JS deobfuscation. We detail our benchmarking methodology, which includes a wide range of obfuscation techniques ranging from basic variable renaming to sophisticated structure transformations, providing a robust framework for assessing LLM performance in real-world scenarios. Our extensive experimental analysis investigates the proficiency of cutting-edge LLMs, e.g., GPT-4o, Mixtral, Llama, and DeepSeek-Coder, revealing superior performance in code simplification despite challenges in
maintaining syntax accuracy and execution reliability compared to baseline methods. We further evaluate the deobfuscation of JS malware to exhibit the potential of LLMs in security scenarios. The findings highlight the utility of LLMs in deobfuscation applications and pinpoint crucial areas for further improvement.

## Merge New Evaluation Results

Use our [benchmark](https://github.com/Ch3nYe/JsDeObsBench) to conduct new evaluation with your model or tool, and pull a new request on this repo with your evalation results. More details can be found in the README of the benchmark.
