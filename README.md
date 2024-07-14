## Introduction

Reference solution for [LLM Prompt Recovery](https://www.kaggle.com/competitions/llm-prompt-recovery) in  Kaggle competition.

Code and comments are available in ``baseline.ipynb``.



## Ideas

### Ours

By writing the prompts and examples by ourselves, In-context Learning is used to enhance performance in few-shot scenarios.



### Inspried by Others

- [1st](https://www.kaggle.com/competitions/llm-prompt-recovery/discussion/494343): So interesting! Enhance the prompt for ``sentence-t5`` by incorporating the ``lucrare`` token in a manner that is similar to the ``</s>`` token, thereby improving its effectiveness.