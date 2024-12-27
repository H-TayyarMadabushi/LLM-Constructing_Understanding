# [Constructing understanding: on the constructional information encoded in large language models](https://link.springer.com/article/10.1007/s10579-024-09799-9)
[Claire Bonial](https://aclanthology.org/people/c/claire-bonial/), [Harish Tayyar Madabushi](https://aclanthology.org/people/h/harish-tayyar-madabushi/)

This repository contains the relevant data associated with the paper. 

Read the [Paper Here](https://link.springer.com/article/10.1007/s10579-024-09799-9)

## Abstract

We review research related to both Construction Grammar (CxG) and Natural Language Processing showing that recent advances in probing Large Language Models (LLMs) for certain types of linguistic knowledge align with the tenets of CxG. However, our survey leads us to hypothesize that LLM constructional information may be limited to the constructions within the lower levels of postulated taxonomical “constructicons” enumerating a particular language’s constructions. Specifically, probing studies show that the constructions at the lower levels of the taxonomy, which are more substantive constructions with fixed elements corresponding to frequently used words within that construction, are a type of linguistic information accessible to LLMs. In contrast, more general, abstract constructions with schematic slots that can be filled by a variety of different words are not included in the linguistic knowledge of LLMs. We test this hypothesis on a collection of 10 distinct constructions, each of which is exhibited in 50 or more corpus instances. Our experimental results strongly support our hypothesis and lead us to conclude that, in order for LLMs to generalize to the point where purely schematic constructions can be recognized regardless of the frequency of the instantiating words (as psycholinguistic experimentation has shown people can), additional semantic resources are needed to make explicit the semantic role of the schematic slot. To ensure transparency and reproducibility, we publicly release our experimental data, including the prompts used with the model.

## Dataset

* You can access to CoGs Dataset and the corresponding test set [HERE](https://github.com/H-TayyarMadabushi/Construction_Grammar_Schematicity_Corpus-CoGS)
* The false positives that we use are available [HERE](https://github.com/H-TayyarMadabushi/LLM-Constructing_Understanding/tree/main/Data)
* The prompts we use are detailed in [Section 5.2 of the paper](https://link.springer.com/article/10.1007/s10579-024-09799-9#Sec7).

Please get in touch with us at htm43 AT bath DOT ac DOT UK if you have any questions or require any further information.


## Citation

```
@article{bonial2024constructing,
  title={Constructing understanding: on the constructional information encoded in large language models},
  author={Bonial, Claire and Tayyar Madabushi, Harish},
  journal={Language Resources and Evaluation},
  pages={1--40},
  year={2024},
  publisher={Springer}
}
```
