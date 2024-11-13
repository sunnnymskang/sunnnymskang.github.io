---
title: "High quality dataset curation for biomedical NLP and training open-source multi-lingual Large Language Model BLOOM"
excerpt: "I was a contributor to BigScience, an open-source science initiative which collaboration resulted in training a very large multilingual neural network language model and gathering a very large multilingual text dataset on the 28 petaflops Jean Zay (IDRIS) supercomputer located near Paris, France. (source: https://bigscience.huggingface.co/)
I was involved in both of the projects: BigBio for curating biomedical datasets and BLOOM for training a multi-lingual open-source LLM.

BigBio
NLP models have great potential for automating complex healthcare tasks such as clinical decision support, information extraction, research summarization, and so on.
To unlock their potential, however, high-quality, domain-specific training datasets are essential. As a core contributor to BIGBIO, I helped build a community library of over 126 biomedical NLP datasets spanning 13 task categories.
This work addresses the underrepresentation of specialized biomedical data and enables reproducible meta-dataset curation.

BLOOM
Our contributions to BIGBIO were instrumental in the training of BLOOM, the largest open-source multilingual language model at the time of release.
BLOOM performs competitively across diverse benchmarks and represents a significant leap forward in the field by publicly releasing its codebase,
setting a new precedent in the development of Large Language Models."
collection: portfolio
---
[Big-Bio repository on GitHub](https://github.com/bigscience-workshop/biomedical)
[Big-Bio follow-up publication in ACL](https://edoc.mdc-berlin.de/id/eprint/22134/1/22134oa.pdf)
[Big-Bio follow-up publication in Neurips proceedings](https://proceedings.neurips.cc/paper_files/paper/2022/file/a583d2197eafc4afdd41f5b8765555c5-Paper-Datasets_and_Benchmarks.pdf)
[BLOOM publication at archive](https://inria.hal.science/hal-03850124/)

BIGBIO: A Framework for Data-Centric Biomedical Natural Language Processing
Large-scale language modeling and natural language prompting have demonstrated exciting
capabilities for few and zero shot learning in
NLP. However, translating these successes to
specialized domains such as biomedicine remains challenging, due in part to biomedical
NLP’s significant dataset debt – the technical
costs associated with data that are not consistently documented or easily incorporated into
popular machine learning frameworks at scale.
To assess this debt, we crowdsourced curation of datasheets for 167 biomedical datasets.
We find that only 13% of datasets are available via programmatic access and 30% lack
any documentation on licensing and permitted reuse. 

BLOOM: A 176B-Parameter Open-Access Multilingual Language Model
Large language models (LLMs) have been shown to be able to perform new tasks based on a few demonstrations or natural language instructions. 
While these capabilities have led to widespread adoption, most LLMs are developed by resource-rich organizations and are frequently kept 
from the public. As a step towards democratizing this powerful technology, we present BLOOM, a 176B-parameter open-access language model
designed and built thanks to a collaboration of hundreds of researchers. BLOOM is a decoder-only Transformer language model that was 
trained on the ROOTS corpus, a dataset comprising hundreds of sources in 46 natural and 13 programming languages (59 in total).
We find that BLOOM achieves competitive performance on a wide variety of benchmarks, with stronger results after undergoing multitask 
prompted finetuning. To facilitate future research and applications using LLMs, we publicly release our models and code under
the Responsible AI License.