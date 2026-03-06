# LatinCy

Synthetic trained [spaCy](https://spacy.io/) pipelines for Latin NLP. Developed by [Patrick J. Burns](https://diyclassics.github.io/).

LatinCy models are trained on large amounts of Latin data, including all five Latin Universal Dependency treebanks, and deliver strong performance across core NLP tasks:

- **POS tagging**: 97.41% accuracy
- **Lemmatization**: 94.66% accuracy
- **Morphological tagging**: 92.76% accuracy

## Installation

```bash
pip install latincy
```

## Models

### Latin (spaCy)

| Model | Description |
|-------|-------------|
| [`la_core_web_trf`](https://huggingface.co/latincy/la_core_web_trf) | Transformer pipeline (RoBERTa) |
| [`la_core_web_lg`](https://huggingface.co/latincy/la_core_web_lg) | Large pipeline with floret vectors |
| [`la_core_web_md`](https://huggingface.co/latincy/la_core_web_md) | Medium pipeline with floret vectors |
| [`la_core_web_sm`](https://huggingface.co/latincy/la_core_web_sm) | Small pipeline |

### Ancient Greek (spaCy)

| Model | Description |
|-------|-------------|
| [`grc_dep_web_trf`](https://huggingface.co/latincy/grc_dep_web_trf) | Transformer pipeline |
| [`grc_dep_web_lg`](https://huggingface.co/latincy/grc_dep_web_lg) | Large pipeline with floret vectors |
| [`grc_dep_web_md`](https://huggingface.co/latincy/grc_dep_web_md) | Medium pipeline with floret vectors |
| [`grc_dep_web_sm`](https://huggingface.co/latincy/grc_dep_web_sm) | Small pipeline |

### Multi-framework

| Model | Framework |
|-------|-----------|
| [`la_udpipe_latincy`](https://huggingface.co/latincy/la_udpipe_latincy) | UDPipe |
| [`la_stanza_latincy`](https://huggingface.co/latincy/la_stanza_latincy) | Stanza |
| [`la_flair_latincy`](https://huggingface.co/latincy/la_flair_latincy) | Flair |

## Links

- [Paper (arXiv)](https://arxiv.org/abs/2305.04365v1)
- [All models on HuggingFace](https://huggingface.co/latincy)
- [LatinCy Dashboard](https://huggingface.co/spaces/latincy/latincy-dashboard) — interactive demo
- [`latincy-readers`](https://github.com/latincy/latincy-readers) — corpus readers for Latin text collections

## Citation

```bibtex
@misc{burns_latincy_2023,
    title = {{LatinCy}: Synthetic Trained Pipelines for Latin {NLP}},
    author = {Burns, Patrick J.},
    url = {https://arxiv.org/abs/2305.04365v1},
    date = {2023-05-07},
}
```
