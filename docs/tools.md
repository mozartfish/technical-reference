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

I owe most of my engineering knowledge to the following people: Tommy Ngyuen, Sundar Rajan, Ron Minnich, James Wexler, [Ryan Stutsman](https://rstutsman.github.io), [Jakob Johnson](https://jakobj.dev), Peter Jensen, [Jeff Phillips](https://users.cs.utah.edu/~jeffp/) and [Varun Shankar](https://users.cs.utah.edu/~shankar/) whose teaching, office hours, and conversations gave me a foundation for not only understanding how to debug and navigate all levels of the technical stack but also core engineering practices - environment/tool setup, experimentation and monitoring setup, command line hacks, numerical programming, and the mental fortitutde you need for finding and fixing bugs. 

 In the age of chatgpt and llms their advice still holds - the only way to become a better engineer is to spend countless hours debugging, experimenting and writing code.  

**Note: This page is getting constantly updated - Last update: October 17, 2025.**

## General Tools
### AI Tools 
- [Lumi](https://lumi.withgoogle.com/#/)
- [NotebookLM](https://notebooklm.google.com/notebook/)
- [Gemini](https://gemini.google.com/) - the Gems Coding Partner tool is super useful for understanding syntax, patterns and languages
- [Claude](https://claude.ai/) 

### Editors + IDES
* [vscode](https://code.visualstudio.com/), opensource version: [vscodium](https://vscodium.com/). GitHub copilot and its autocomplete is such a nuisance that I have turned it off. If I need AI help, Gemini is more useful. 
* [vim](https://openvim.com/)
* [intellij](https://www.jetbrains.com/idea/)

### Terminal
* [tmux](https://hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)

### Testing 
* [pyTest](https://docs.pytest.org/en/stable/)
* [JUnit](https://junit.org/junit5/)

### Linters, Formatters 
* [ruff](https://docs.astral.sh/ruff/)
- [prettier](https://prettier.io)

### Container Environments 
* [docker](https://www.docker.com) 

### Version Control 
* [git](https://git-scm.com)

### Prototyping 
* [p5.js Web Editor](https://editor.p5js.org/)
* [Svelte Playground](https://svelte.dev/playground/)

### Writing + Publishing 
* [Overleaf](https://www.overleaf.com/)
* [Quarto](https://quarto.org/)
* [Typst](https://typst.app/)

### Package Managers 
- [uv](https://docs.astral.sh/uv/)
- [pip](https://pypi.org/project/pip/)
- [cargo](https://doc.rust-lang.org/cargo/)
- [npm](https://www.npmjs.com/)

### Datasets 
* [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/)
* [fivethirtyeight datasets](https://github.com/fivethirtyeight)
* [Martin Wattenberg datasets](https://github.com/wattenberg/data)

### Monitoring 
* [mlflow](https://mlflow.org/) - [installation](https://mlflow.org/docs/latest/getting-started/index.html)
- [weights and biases]()https://wandb.ai/site/

## Programming Languages 
* [Python](https://www.python.org/) - machine learning, scripting, prototyping and almost all of my development these days
* [Bash](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/) - compile and running programs, experiments etc.
* [Java](https://www.oracle.com/java/technologies/downloads/) - information retrieval, data engineering
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - interfaces, creative coding, interactive visualization
### Python Libraries 
* [tqdm](https://tqdm.github.io/)
* [rich](https://rich.readthedocs.io/en/stable/introduction.html)
* [pathlib](https://docs.python.org/3/library/pathlib.html)

## Data
### Core Libraries 
* [numpy](https://numpy.org) - [installation](https://numpy.org/install/)
* [scipy](https://scipy.org) - [installation](https://scipy.org/install/)
* [pandas](https://pandas.pydata.org/) - [installation](https://pandas.pydata.org/docs/getting_started/index.html)
* [matplotlib](https://matplotlib.org/) - [installation](https://matplotlib.org/stable/users/getting_started/)

### Notebooks
* [marimo](https://marimo.io/)
* [google colab](https://colab.research.google.com/)

### Machine Learning 
* [scikit-learn](https://scikit-learn.org/stable/index.html) - [installation](https://scikit-learn.org/stable/install.html)

#### Deep Learning
* [pytorch](https://pytorch.org/) - [installation](https://pytorch.org/get-started/locally/)
* [pytorch lightning](https://lightning.ai/docs/pytorch/stable/) - [installation](https://lightning.ai/docs/pytorch/stable/starter/installation.html)

### Visualization
The python visualization ecosystem is fragmented and choosing the right visualization library depends on the project and audience. Many of the python visualization libraries build off of matplotlib. Matplotlib while tedious is super power powerful and versatile, with the ability to render interactive 3d plots, conic sections and do image processing work. Seaborn is great for statistical charts with an aesthetic similar to ggplot but the syntax can get gnarly. Altair is an easy to learn member of the Vega-Lite ecosystem but requires deep knowledge of the grammar of graphics and gets knarly with interaction and customizability.
* [seaborn](https://seaborn.pydata.org/) - [installation](https://seaborn.pydata.org/installing.html)
* [plotly](https://plotly.com/python/) - [installation](https://plotly.com/python/getting-started/#installation)
* [altair](https://altair-viz.github.io) - [installation](https://altair-viz.github.io/getting_started/installation.html)
* [kepler-mapper](https://kepler-mapper.scikit-tda.org/en/latest/)

### Dimensionality Reduction 
* [DataMapPlot](https://datamapplot.readthedocs.io/en/latest/) - [installation](https://datamapplot.readthedocs.io/en/latest/installation.html)
* [HDBScan](https://hdbscan.readthedocs.io/en/latest/index.html)
* [UMAP](https://umap-learn.readthedocs.io/en/latest/) 

### Language: Computational Linguistics, Information Retrieval
* [nltk](https://www.nltk.org/)
* [spacy](https://spacy.io/)
* [elasticsearch](https://www.elastic.co/elasticsearch)
* [huggingface transformers](https://huggingface.co/docs/transformers/en/index)

### Image Analysis and Computer Vision
* [scikit-image](https://scikit-image.org) - [installation](https://scikit-image.org/docs/stable/user_guide/install.html)
* [torchvision](https://pytorch.org/vision/stable/index.html)

### Audio 
- [librosa](https://librosa.org)

## Interactive Visualization 
### D3
D3 - a library that has caused many ups and down for me but still I am excited about its capabilities. This is highly opinionated but D3 is done. Svelte, JavaScript, charting libraries(chart.js) and frontend engineering have slowly taken and improved D3's magic to the point that you can actually implement many features with the Canvas API, CSS, and frameworks. D3 was built for the 2009-2021 era but now the api design seems stuck in time as it clashes with frameworks that need to utilize its capabilities. To that end, with some engineering tricks and staring at the source code it is possible to integrate d3 into a framework project but it is now treated more as a module library.

At the time of this writing, d3's capabilities are unmatched for interactive visualization thus d3 is still needed for interactive visualization and building interfaces that interface between users and ml models. 
* [d3.js](https://d3js.org/)
#### D3 extensions
* [D3-Annotation](https://d3-annotation.susielu.com/)
* [D3-Legend](https://d3-legend.susielu.com/)

### JavaScript Frameworks 
Not learning a JS framework was the biggest regret I had from my Utah days. For choosing a framework, it really depends on how well you know javascript and your project goals (see the framework documentaries in the talks page). Since I'm interested in interactive visualization for machine learning, svelte seems to be the most widely adopted based on the tools and research published by [Anthropic](https://transformer-circuits.pub/), [Apple AIML](https://machinelearning.apple.com/research) [Google DeepMind PAIR](https://pair.withgoogle.com/explorables/) and OpenAI hiring [Jay Wang](https://zijie.wang/). I wouldn't count out vue and react because [Catherine Yeh](https://catherinesyeh.github.io/) built [AttentionVis](https://catherinesyeh.github.io/attn-docs/) with vue and the [Polo Club for Data Science](https://poloclub.github.io/) publishes a wide range of ml-vis tools using svelte, vue and react.
* [Svelte](https://svelte.dev/)
- [FlowBite](https://flowbite-svelte.com/)

## Systems Programming + Infrastructure
### Software Frameworks
* [flask](https://flask.palletsprojects.com/en/stable/)

### API
* [fastapi](https://fastapi.tiangolo.com)

### AI Infrastructure
- [Modal](https://modal.com/)

### Data Processing
- [pyspark](https://spark.apache.org/docs/latest/api/python/index.html)
- [mllib](https://spark.apache.org/docs/latest/ml-guide.html)
* [polars](https://pola.rs/)

### Databases 
#### rdbms 
- [postgresql](https://neon.com/postgresql/tutorial)
#### nosql 
- [mongodb](https://www.mongodb.com/)
- [duckdb](https://duckdb.org/)

### ML Interfaces, Deployment, etc. 
* [gradio](https://www.gradio.app)
* [huggingface spaces](https://huggingface.co/spaces)

# Things I wish I had time to explore and learn more about
These are things that I wish I had time to explore 

## Creative Coding 
I first heard about this at the EYEO Festival. I started with Dan Shiffman's [Coding Train](https://thecodingtrain.com/) but shifted to Kevin Workman's [Happy Coding](https://happycoding.io/) and then stopped. It was a lot of fun to use p5 and it explained some of the javascript quirks I struggled with. After seeing all the cool stuff put out by Martin Wattenberg, Fernanda Viegas, Golan Levin, Ravi Chugh, and Andrew McNutt I want to pick it up again and try to implement some of the projects from Code as a Creative Medium. 
* [p5.js](https://p5js.org/)
* [nature of code](https://natureofcode.com)
* [openFrameworks](https://openframeworks.cc/)
* [cinder](https://libcinder.org/)
