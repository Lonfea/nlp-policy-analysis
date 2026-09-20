# NLP Models for Climate Policy Analysis

> **Portfolio implementation — Climate Change AI Virtual Summer School 2026**  
> Completed by **Berkant Duman**. Original tutorial authorship, citations, and license are preserved below.

## Portfolio snapshot

This two-part project applies **NLP and large language models to climate-policy analysis**, spanning supervised evidence synthesis and LLM-based document classification.

**Skills demonstrated:** NLP · supervised text classification · embeddings · LLM prompting · policy-document analysis · evaluation workflows · API-based AI systems

**Decision context:** Automated text analysis can help researchers and policymakers navigate rapidly growing climate-policy and scientific literatures, but outputs still require validation and careful interpretation.


Explore how Natural Language Processing (NLP) can be used to assist in identifying and mapping climate-relevant literature using a supervised learning approach and leverage a state of the art Large Language Model (LLM) to classify climate policy documents.

Author(s):
* Daniel Spokoyny, Carnegie Mellon University, dspokoyn@cs.cmu.edu
* Max Callaghan, Mercator Research Institute on Global Commons and Climate - Berlin, callaghan@mcc-berlin.net
* Tobias Schimanski, University of Zurich, tobias.schimanski@df.uzh.ch

Originally presented at Climate Change AI Summer School 2022, revised annually for 2023, 2024, and 2026.

Completed by **Berkant Duman** for the **Climate Change AI Virtual Summer School 2026**. Both tutorial parts are included in this single public repository, so this repository URL is the one submission link.

## Access this tutorial

We recommend executing this notebook in a Colab environment to gain access to GPUs and to manage all necessary dependencies.

Part 1: <a target="_blank" href="https://colab.research.google.com/github/Lonfea/nlp-policy-analysis/blob/main/part1_evidence_synthesis.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Part 2: <a target="_blank" href="https://colab.research.google.com/github/Lonfea/nlp-policy-analysis/blob/main/part2_paris_prompts.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Estimated time to execute end-to-end: 2 hours

### Part 2 API setup

Part 2 uses the OpenAI API for text generation and embeddings. In Google Colab, open **Secrets** (the key icon), create a secret named `OPENAI_API_KEY`, and enable notebook access. Never paste an API key into the notebook or commit it to GitHub. API usage may incur charges.

## Contribute to this tutorial

Please refer to these [GitHub instructions](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project#about-forking) to open a pull request via the "fork and pull request" workflow. 

Pull requests will be reviewed by members of the Climate Change AI Tutorials team for relevance, accuracy, and conciseness.

## Climate Change AI Tutorials
Check out the [tutorials page](https://www.climatechange.ai/tutorials?) on our website for a full list of tutorials demonstrating how AI can be used to tackle problems related to climate change.

## License
Usage of this tutorial is subject to the MIT License.

## Cite

### Plain Text
Spokoyny, D., Callaghan, M, & Schimanski, T. (2026). NLP Models for Climate Policy Analysis [Tutorial]. In Climate Change AI Summer School. Climate Change AI. https://doi.org/10.5281/zenodo.21446699

### BibTeX

```
@misc{spokoyny2026nlp,
  title={NLP Models for Climate Policy Analysis},
  author={Spokoyny, Daniel and Callaghan, Max and Schimanski, Tobias},
  year={2026},
  organization={Climate Change AI},
  type={Tutorial},
  doi={https://doi.org/10.5281/zenodo.21446699},
  booktitle={Climate Change AI Summer School},
  howpublished={\url{https://github.com/climatechange-ai-tutorials/nlp-policy-analysis}}
}
```
