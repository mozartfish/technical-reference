---
layout: default
title: uses this
nav_order: 3
---

# Tools

{: .no_toc }

## Table of Contents

{: .no_toc .text-delta }

1. TOC
   {:toc}

---

## Background

This page is a place where I keep track of what libraries and tools I have used/currently using. This page is inspired by [uses this](https://usesthis.com/interviews/), [the missing semester of your cs education](https://missing.csail.mit.edu/), [the pragmatic programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/), [strangeloop](https://www.thestrangeloop.com/index.html), [eyeo festival](https://eyeofestival.com/).

I owe most of my engineering knowledge to the following people: Tommy Ngyuen, Sundar Rajan, [Ron Minnich](https://github.com/rminnich), James Wexler, [Ryan Stutsman](https://rstutsman.github.io), [Jakob Johnson](https://jakobj.dev), Peter Jensen, [Jeff Phillips](https://users.cs.utah.edu/~jeffp/) and [Varun Shankar](https://users.cs.utah.edu/~shankar/) whose teaching, office hours, and conversations gave me a foundation for not only understanding how to debug and navigate all levels of the technical stack but also core engineering practices - environment/tool setup, experimentation and monitoring setup, command line hacks, numerical programming, and the mental fortitutde you need for finding and fixing bugs.

In the age of chatgpt and llms their advice still holds - the only way to become a better engineer is to spend countless hours debugging, experimenting and writing code. When it comes to UIs, Webdev and even visualization engineering vibecoding gets the 90% of the job done(at least from what i've seen and tried). The last 10% - that's the human-creative part that AI can't replace.

Software engineering is not dead - the mission critical and important software we use every day in health, driving and more is implemented with C++ and other technologies that have been battled tested.

**Note: This page is getting constantly updated - Last update: february 13, 2026**

## Enginering Tools

### Terminal

- [tmux](https://hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)

### Editors, IDES etc.

- [vscode](https://code.visualstudio.com/), opensource version: [vscodium](https://vscodium.com/). GitHub copilot and its autocomplete is such a nuisance that I have turned it off. If I need AI help, Gemini/Claude is more useful.
- [vim](https://openvim.com/)
- [intellij](https://www.jetbrains.com/idea/)

### Testing

- [pyTest](https://docs.pytest.org/en/stable/)
- [JUnit](https://junit.org/junit5/)

### Linters and Formatters

- [ruff](https://docs.astral.sh/ruff/)
- [prettier](https://prettier.io)

### Package Managers

- [uv](https://docs.astral.sh/uv/)
- [pip](https://pypi.org/project/pip/)
- [cargo](https://doc.rust-lang.org/cargo/)
- [npm](https://www.npmjs.com/)

### Version Control

- [git](https://git-scm.com)

### Containerization

- [docker](https://www.docker.com/)
- [kubernetes](https://kubernetes.io/docs/concepts/overview/)

### Prototyping

- [p5.js Web Editor](https://editor.p5js.org/)
- [Svelte Playground](https://svelte.dev/playground/)
- [Jupyter](https://jupyter.org/)
- [google colab](https://colab.research.google.com/)

#### Interactive Prototyping

- [marimo](https://marimo.io/)

### Python Tools

- [tqdm](https://tqdm.github.io/)
- [rich](https://rich.readthedocs.io/en/stable/introduction.html)
- [pathlib](https://docs.python.org/3/library/pathlib.html)

### Audio Tools

- [Audacity](https://www.audacityteam.org/)
- [MuseScore](https://musescore.org/en)

### File Processing

- [ffmpeg](https://www.ffmpeg.org/)

## AI Tools

- [Lumi](https://lumi.withgoogle.com/#/)
- [NotebookLM](https://notebooklm.google.com/notebook/)
- [Gemini](https://gemini.google.com/) - the Gems Coding Partner tool is super useful for understanding syntax, patterns and languages
- [Claude](https://claude.ai/)
- [Semantic Scholar](https://www.semanticscholar.org)
- [Asta](https://asta.allen.ai/chat)

## Writing + Publishing

- [Overleaf](https://www.overleaf.com/)
- [Quarto](https://quarto.org/)
- [Typst](https://typst.app/)

## Signal Processing

### Audio

- [librosa](https://librosa.org/doc/latest/index.html)
- [torchaudio](https://docs.pytorch.org/audio/stable/index.html)

### Image

- [scikit-image](https://scikit-image.org/)
- [OpenCV](https://opencv.org/)
- [torchvision](https://docs.pytorch.org/vision/stable/index.html)

## Datasets

- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/)
- [fivethirtyeight datasets](https://github.com/fivethirtyeight)
- [Martin Wattenberg datasets](https://github.com/wattenberg/data)
- [Kunstderfugue](https://kunstderfuge.com/) - the largest free online repository of classical music MIDI files

## Scientific Data Computing

- [numpy](https://numpy.org) - [installation](https://numpy.org/install/)
- [scipy](https://scipy.org) - [installation](https://scipy.org/install/)
- [pandas](https://pandas.pydata.org/) - [installation](https://pandas.pydata.org/docs/getting_started/index.html)
- [matplotlib](https://matplotlib.org/) - [installation](https://matplotlib.org/stable/users/getting_started/)

## Dimensionality Reduction

- [DataMapPlot](https://datamapplot.readthedocs.io/en/latest/) - [installation](https://datamapplot.readthedocs.io/en/latest/installation.html)
- [HDBScan](https://hdbscan.readthedocs.io/en/latest/index.html)
- [UMAP](https://umap-learn.readthedocs.io/en/latest/)

## Systems

### Large Scale Data Processing

- [pyspark](https://spark.apache.org/docs/latest/api/python/index.html)
- [polars](https://pola.rs/) -> substitute for pandas when working with parquet and giant data(non-csv)

### Databases

- [postgresql](https://neon.com/postgresql/tutorial)
- [mongodb](https://www.mongodb.com/)

* [duckdb](https://duckdb.org/) -> columnar in-memory database
* [sqllite](https://docs.python.org/3/library/sqlite3.html)

### Feature Stores

- [Hopsworks](https://www.hopsworks.ai/)

### Compute + Infrastructre

- [Modal](https://modal.com/)
- [Ray](https://github.com/ray-project/ray)

### Deployment

- [flask](https://flask.palletsprojects.com/en/stable/)
- [fastapi](https://fastapi.tiangolo.com)

### AIML Deployment, Interfaces and Infrastructure

- [gradio](https://www.gradio.app)
- [huggingface spaces](https://huggingface.co/spaces)

## Information

### Information Retrieval

- [libfmp](https://meinardmueller.github.io/libfmp/build/html/index.html)
- [elasticsearch](https://www.elastic.co/elasticsearch)

### Language

- [nltk](https://www.nltk.org/)
- [spacy](https://spacy.io/)
- [HuggingFace Transformers](https://huggingface.co/docs/transformers/index)
- [HuggingFace SentenceTransformers](https://sbert.net/)

## Machine Learning

### Classical Machine Learning

- [scikit-learn](https://scikit-learn.org/stable/index.html) - [installation](https://scikit-learn.org/stable/install.html)

### Deep Learning

- [pytorch](https://pytorch.org/) - [installation](https://pytorch.org/get-started/locally/)
- [pytorch lightning](https://lightning.ai/docs/pytorch/stable/) - [installation](https://lightning.ai/docs/pytorch/stable/starter/installation.html)
- [keras](https://keras.io/) -[installation](https://keras.io/getting_started/)

### Distributed Machine Learning

- [mllib](https://spark.apache.org/docs/latest/ml-guide.html)

### Machine Learning Tools

- [optuna](https://optuna.org/) - [installation](https://optuna.org/#installation)
- [mlflow](https://mlflow.org/) - [installation](https://mlflow.org/docs/latest/getting-started/index.html)
- [weights and biases](https://wandb.ai/site/)

## Language Models

### Open Source AI Models

- [Gemma Models](https://deepmind.google/models/gemma/)
- [Olmo Models](https://allenai.org/olmo)

### Finetuning Tools

- [Unsloth](https://unsloth.ai/)
- [Axlotl](https://axolotl.ai/)

### Diffusion Tools

- [ComfyUI](https://www.comfy.org/)

### HuggingFace Tools

- [HuggingFace PEFT](https://huggingface.co/docs/peft/main/en/index)
- [HuggingFace Diffusers](https://huggingface.co/docs/diffusers/index)

## Visualization

The python visualization ecosystem is fragmented and choosing the right visualization library depends on the project and audience. Many of the python visualization libraries build off of matplotlib. Matplotlib while tedious is super power powerful and versatile, with the ability to render interactive 3d plots, conic sections and do image processing work. Seaborn is great for statistical charts with an aesthetic similar to ggplot but the syntax can get gnarly. Altair is an easy to learn member of the Vega-Lite ecosystem but requires deep knowledge of the grammar of graphics and gets knarly with interaction and customizability.

- [seaborn](https://seaborn.pydata.org/) - [installation](https://seaborn.pydata.org/installing.html)
- [plotly](https://plotly.com/python/) - [installation](https://plotly.com/python/getting-started/#installation)
- [altair](https://altair-viz.github.io) - [installation](https://altair-viz.github.io/getting_started/installation.html)
- [kepler-mapper](https://kepler-mapper.scikit-tda.org/en/latest/)

### Interactive Visualization

D3 - a library that has caused many ups and down for me but still I am excited about its capabilities. This is highly opinionated but D3 is done. Svelte, JavaScript, charting libraries(chart.js) and frontend engineering have slowly taken and improved D3's magic to the point that you can actually implement many features with the Canvas API, CSS, and frameworks. D3 was built for the 2009-2021 era but now the api design seems stuck in time as it clashes with frameworks that need to utilize its capabilities. To that end, with some engineering tricks and staring at the source code it is possible to integrate d3 into a framework project but it is now treated more as a module library.

At the time of this writing, d3's capabilities are unmatched for interactive visualization thus d3 is still needed for interactive visualization and building interfaces that interface between users and ml models.

- [d3.js](https://d3js.org/)

#### D3 Extensions

- [D3-Annotation](https://d3-annotation.susielu.com/)
- [D3-Legend](https://d3-legend.susielu.com/)

## Programming Languages

- [Python](https://www.python.org/) - machine learning, scripting, prototyping and almost all of my development these days
- [Bash](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/) - compile and running programs, experiments etc.
- [Java](https://www.oracle.com/java/technologies/downloads/) - information retrieval, data engineering

### Web - JavaScript and Frameworks

Not learning a JS framework was the biggest regret I had from my Utah days. For choosing a framework, it really depends on how well you know javascript and your project goals (see the framework documentaries in the talks page). Since I'm interested in interactive visualization for machine learning, svelte seems to be the most widely adopted based on the tools and research published by [Anthropic](https://transformer-circuits.pub/), [Apple AIML](https://machinelearning.apple.com/research) [Google DeepMind PAIR](https://pair.withgoogle.com/explorables/) and OpenAI hiring [Jay Wang](https://zijie.wang/). I wouldn't count out vue and react because [Catherine Yeh](https://catherinesyeh.github.io/) built [AttentionVis](https://catherinesyeh.github.io/attn-docs/) with vue and the [Polo Club for Data Science](https://poloclub.github.io/) publishes a wide range of ml-vis tools using svelte, vue and react.

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - interfaces, creative coding, interactive visualization
- [Svelte](https://svelte.dev/)
- [FlowBite](https://flowbite-svelte.com/)

# Things I wish I had time to explore and learn more about

These are things that I wish I had time to explore

## Creative Coding

I first heard about this at the EYEO Festival. I started with Dan Shiffman's [Coding Train](https://thecodingtrain.com/) but shifted to Kevin Workman's [Happy Coding](https://happycoding.io/) and then stopped. It was a lot of fun to use p5 and it explained some of the javascript quirks I struggled with. After seeing all the cool stuff put out by Martin Wattenberg, Fernanda Viegas, Golan Levin, Ravi Chugh, and Andrew McNutt I want to pick it up again and try to implement some of the projects from Code as a Creative Medium.

- [p5.js](https://p5js.org/)
- [nature of code](https://natureofcode.com)
- [openFrameworks](https://openframeworks.cc/)
- [cinder](https://libcinder.org/)

## C++

I wish I had time to explore C++ more in depth because this is the language for turning research projects and code into production and tools that people actually use especially for my interests in audio, vision, graphics are in C++.
