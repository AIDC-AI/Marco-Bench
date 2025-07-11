# Marco-Bench-MIF: A Benchmark for Multilingual Instruction-Following Evaluation

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![ACL 2025](https://img.shields.io/badge/ACL-2025-blue)](https://www.2025.aclweb.org/)

## Introduction

Marco-Bench-MIF is the first deeply localized multilingual benchmark designed to evaluate instruction-following capabilities across 30 languages. Unlike existing benchmarks that rely primarily on machine translation, Marco-Bench-MIF implements fine-grained cultural adaptations to provide more accurate assessment. Our research demonstrates that machine-translated data underestimates model performance by 7-22% in multilingual environments.


## Key Features

- **Extensive Language Coverage**: 30 languages spanning 6 major language families, including high-resource (English, Chinese, German) and low-resource languages (Yoruba, Nepali)
- **Deep Cultural Localization**: Three-step process of lexical replacement, theme transformation, and pragmatic reconstruction to ensure cultural and linguistic appropriateness
- **Diverse Constraint Types**: 541 instruction-response pairs covering single/multiple constraints, expressive/content constraints, and various instruction types
- **Comparative Dataset**: Machine-translated and culturally-localized versions available for specific languages (Arabic, Chinese, Spanish, etc.) to enable comparative research

## Dataset Access

The dataset will be available through our GitHub repository and Hugging Face:

```bash
git clone https://github.com/AIDC-AI/Marco-Bench-MIF.git
```

## Key Findings

Our benchmark evaluated 20+ LLM models and revealed:

1. Model scale strongly correlates with performance, with 70B+ models outperforming 8B models by 45-60%
2. A 25-35% performance gap exists between high-resource languages (German, Chinese) and low-resource languages (Yoruba, Nepali)
3. Significant differences between localized and machine-translated evaluations, especially for complex instructions

## Contact

For questions or suggestions, please submit a GitHub issue or contact us:
- Email: lyuchenyang.lcy@alibaba-inc.com
- Project homepage: https://github.com/AIDC-AI/Marco-Bench-MIF

## License

This dataset is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Acknowledgments

Special thanks to all annotators and translators who participated in dataset construction and validation. This project is supported by Alibaba International Digital Commerce Group.