# chatAI4RBI: Chat-based Artificial Intelligence for R and Bioinformatics

## Description

Chat-based Artificial Intelligence (AI) for Bioinformatics, "chatAI4RBI," is an R package designed to integrate the ChatGPT API with bioinformatics. This package aims to enable efficient data analysis and knowledge discovery based on a large language model (LLM)-based AI technique, ChatGPT. The package utilizes the ChatGPT API for natural language processing and provides a set of functions capable of executing various bioinformatics analysis methods.

## About this project

- R language usage for AI API
  - ChatGPT API
  - DeepL API
  - Text embeddings API (text-embedding-ada-002)
- LLM-based AI technique for Bioinformatics
  - ゲノム解析, タンパク質構造予測, 遺伝子発現解析, 変異解析
  - 自動解析: 解析デザイン, 統計, データ可視化, 考察, 質問応答
  - 専門文章の言語モデル: 自然言語での質問応答

## Installation

1. Start R.app

2. Run the following commands in the R console.

```r
#CRAN-version
install.packages("chatAI4RBI")
library(chatAI4RBI)

#Dev-version
devtools::install_github("kumeS/chatAI4RBI")
library(chatAI4RBI)
```

## Basic functions

- chat4R: Interact with gpt-3.5-turbo-16k (default) using OpenAI API
- textEmbedding: Text Embedding from OpenAI API (model: text-embedding-ada-002)
- deepel: DeepL Translation Function

## Secondary Layer Functions

- chat4R_history:
- conversation4R: 

## Task-specific functions



### Functions for RIKEN press release

- get_riken_pressrelease_urls:
- riken_pressrelease_text_jpn: 
- riken_pressrelease_textEmbedding:

## Simple usage




## License

Copyright (c) 2023 Satoshi Kume released under the [Artistic License 2.0](http://www.perlfoundation.org/artistic_license_2_0).

## Cite

Kume S. (2023) chatAI4RBI: Chat-based Artificial Intelligence for R and Bioinformatics.

```
#BibTeX
@misc{Kume2023chatAI4RBI,
  title={chatAI4RBI: Chat-based Artificial Intelligence for R and Bioinformatics},
  author={Kume, Satoshi}, year={2023},
  publisher={GitHub}, note={R Package},
  howpublished={\url{https://github.com/kumeS/chatAI4RBI}},
}
```

## Contributors

- Satoshi Kume

