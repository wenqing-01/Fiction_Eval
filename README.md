# Annotated Literary Fiction Dataset
This is the Repo for the paper: "Towards A “Novel” Benchmark: Evaluating Literary Fiction with Large Language Models"
## Abstract
Current exploration on Large Language Models (LLMs) in creative generation focuses mainly on short stories, poetry, and scripts. With the expansion of Large Language Models (LLMs) context windows, "novel" avenues emerge. This study aims to extend the boundaries of Natural Language Generation (NLG) evaluation by exploring LLMs' capabilities in more challenging long-form fiction. We propose a new multi-level evaluation framework that incorporates ten metrics across the Macro, Meso, and Micro levels. An annotated fiction dataset, sourced from human authors, LLMs, and human-AI collaborations in both English and Chinese is then constructed. Human evaluation reveals notable disparities between LLM-generated and human-authored fictions, particularly the “high-starting, low-ending” pattern in LLM outputs. We further probe ten high-performing LLMs through different prompt templates, achieving moderate correlations by strategically utilizing diverse LLMs tailored to different levels, as an initial step towards better automatic fiction evaluation. Finally, we offer a fine-grained analysis of LLMs capabilities through six issues, providing promising insights for future advancements.

## Overview
<img src="https://github.com/wenqing-01/Fiction_Eval/blob/main/fig_overview.jpg" alt="image" width="700"/>

## Contributions
1. We are the first to explore LLMs in long-form fiction evaluation and propose a multi-level framework for quantitative analysis;
2. We release an annotated fiction dataset with various sources in both English and Chinese, along with our refined guidelines, to benchmark literary fiction evaluation;
3. We evaluate ten top LLMs, initially enhancing automated fiction evaluation through utilizing different LLMs with diverse prompt strategies, and provide valuable insights to enhance their capabilities based on a fine-grained analysis.

## Citation
Please cite our work if you find it useful.

@inproceedings{wang-etal-2025-towards-novel,
    title = "Towards A ``Novel'' Benchmark: Evaluating Literary Fiction with Large Language Models",
    author = "Wang, Wenqing  and
      Gao, Mingqi  and
      Hu, Xinyu  and
      Wan, Xiaojun",
    editor = "Che, Wanxiang  and
      Nabende, Joyce  and
      Shutova, Ekaterina  and
      Pilehvar, Mohammad Taher",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2025",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-acl.1114/",
    doi = "10.18653/v1/2025.findings-acl.1114",
    pages = "21648--21673",
    ISBN = "979-8-89176-256-5"
}
