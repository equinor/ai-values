# Values

A one-page app showing how LLMs plot on the Ingelhart–Welzel Cultural Map, which is based on recent responses to 10 questions in the World Values Survey and European Values Study.

You can download and open `index.html` file in your browser, or [try it right now](https://kwinkunks.github.io/ai-values)

<img width="1234" alt="image" src="https://github.com/user-attachments/assets/47b69ae5-9ab0-4fea-bceb-358439386eec" />

## About the project

Human beings have **values** — ideas and practices that they cherish and propagate in their societies. LLMs do not have values per se, but the alignment steps in their training (eg the RLHF step) likely reflect the value systems of the people and corporations that trained them.

So a question we can ask is: Is it possible to get an LLM to reveal the value system it has learned?

The World Values Survey and European Values Survey have run multiple international surveys: 200+ questions, more than 100 countries, more than 1000 respondents per country, most than 40 years of data.

Ten of the WVS/EVS questions contribute to two key indicators: 'survival vs self-expression values' and 'traditional vs secular values'. Together, these are often shown on a Inglehart–Welzel Cultural Map. A recent paper, Tao et al 2024, plots LLMs on this map. This work reproduces and extends that paper.


## Notebooks on Colab

- [Evaluation-of-AI-chat-models.ipynb](https://colab.research.google.com/drive/1DSCi9zRaaelDlYtgTtBF9QhAEPQwp37D)
- [Compute-weights-from-IVS.ipynb](https://colab.research.google.com/drive/1NHcZtt0HaU3fBe1TX2DIp_D0bSl2p0t4)
- [Comparison-with-IVS.ipynb](https://colab.research.google.com/drive/1XdAHu7O8n8r2a2ykh-CXaXppJptpEcK-)


## References 

EVS (2022). EVS Trend File 1981-2017 (ZA7503; Version 3.0.0) [Data set]. GESIS, Cologne. https://doi.org/10.4232/1.14021

Haerpfer, C., Inglehart, R., Moreno, A., Welzel, C., Kizilova, K., Diez-Medrano J., M. Lagos, P. Norris, E. Ponarin & B. Puranen et al. (eds.). 2022. World Values Survey Trend File (1981-2022) Cross-National Data-Set. Madrid, Spain & Vienna, Austria: JD Systems Institute & WVSA Secretariat. Data File Version 4.0.0, doi:10.14281/18241.27.

Tao, Y, O Viberg, RS Baker, RF Kizilcec (2024). Cultural bias and cultural alignment of large language models. PNAS Nexus 3 (9), September 2024, https://doi.org/10.1093/pnasnexus/pgae346.


## Related work

There are papers criticising the approach taken here:

- [Beyond prompt brittleness: Evaluating the reliability and consistency of political worldviews in LLMs](https://arxiv.org/pdf/2402.17649v1), Ceron, Falk, et al. (2024), Stuttgart.
- [Break the Checkbox: Challenging Closed-Style Evaluations of Cultural Alignment in LLMs](https://arxiv.org/abs/2502.08045v2), Kabir et al (2025), Manchester.
  
Similar studies to Tao et al:

- [Which humans?](https://coevolution.fas.harvard.edu/publications/which-humans) Atari, Xue, Park, et al, Harvard.
- [A Question Bank to Assess AI Inclusivity: Mapping out the Journey from Diversity Errors to Inclusion Excellence](https://arxiv.org/pdf/2506.18538v1), Shams et al, CSIRO (I don't tihnk CSIRO's benchmarks are open).
- [Exploring Cultural Variations in Moral Judgments with Large Language Models](https://arxiv.org/pdf/2506.12433), Mohammadi et al, Utrecht.
- [From Surveys to Narratives](https://arxiv.org/pdf/2505.16408v1), Adilazuarda et al., Abu Dhabi.
- [Cultural fidelity in LLMs](https://arxiv.org/pdf/2410.10489v1), Kazemi et al., Columbia.

Some attempts at benchmarks:

- [eval-polical-worldviews](https://github.com/tceron/eval_political_worldviews)
- [WorldValuesBench](https://aclanthology.org/2024.lrec-main.1539.pdf)


## Other AI-related repositories

We maintain a few other repos containing learning material related to machine learning and artificial intelligence.

- [`promptly`](https://github.com/equinor/promptly) for more on prompting and pitfalls in generative AI.
- [`llm-engineering-101`](https://github.com/equinor/llm-engineering-101) for a short workshop aimed at getting developers up to speed.
- [`ml-pitfalls`](https://github.com/equinor/ml-pitfalls) for more on pitfalls in discriminative machine learning, another series of events.
- [`ai-upskill`](https://github.com/equinor/ai-upskill) for a repo describing Equinor's company upskill events and materials.
- [`label-ai`](https://github.com/equinor/label-ai) for a small web app exploring obvious and non-obvious ways of labeling generated content.

---

&copy; 2025 Matt Hall, Equinor | Licensed CC BY, please share this work.
