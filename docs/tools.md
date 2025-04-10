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
This page is a place where I keep track of what libraries and tools I use in my work. This page is inspired by [uses this](https://usesthis.com/interviews/), [the missing semester of your cs education](https://missing.csail.mit.edu/), [the pragmatic programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/), [strangeloop](https://www.thestrangeloop.com/index.html), [eyeo festival](https://eyeofestival.com/).My work can't be clearly described as a single area ie. fullstack, frontend, backend, infrastructure, cloud, systems. I'm an engineer who works at the interface layer between machine learning models and the platform/application layer that people interact with. I describe this as tooling because it is domain specific ie. music, nlp, search, computer vision, interpretability, information retrieval. In the following sections I describe my work and tool setup for the problems I work on. I'd also like to thank Ryan Stutsman whose teaching and office hours pushed me to understand my tools to at least 1/8 of his knowledge which I learned the hard way comes from countless hours of debugging, experimentation and writing software.  

**Note: It is a constant work of progress.**

## General Tools
### Editors + IDES
* [vscode](https://code.visualstudio.com/), opensource version: [vscodium](https://vscodium.com/)
* [vim](https://openvim.com/)
* [intellij](https://www.jetbrains.com/idea/)

### Terminal
* [tmux](https://hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)
* [ohmyzsh](https://ohmyz.sh/)

### LLMs
* [Claude](https://claude.ai/)
* [Gemini](https://gemini.google.com/)

### Testing 
* [pyTest](https://docs.pytest.org/en/stable/)
* [JUnit](https://junit.org/junit5/)
* [GoogleTest](https://google.github.io/googletest/)

### Prototyping 
* [p5.js Web Editor](https://editor.p5js.org/)
* [Svelte Playground](https://svelte.dev/playground/)

### Writing + Publishing 
* [Overleaf](https://www.overleaf.com/)
* [Quarto](https://quarto.org/)
* [Typst](https://typst.app/)

### Datasets 
* [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/)
* [fivethirtyeight datasets](https://github.com/fivethirtyeight)

## Programming Languages 
* [Python](https://www.python.org/) - machine learning, scripting, prototyping and more 
* [Golang](https://go.dev/) - cloud, scripting, systems programming 
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - interfaces, creative coding, interactive visualization 
* [Java](https://www.oracle.com/java/technologies/downloads/) - information retrieval, enterprise systems, data engineering 
* [Bash](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/) - compile and running programs, experiments etc. 

## Data
### Foundational Tools 
These are libraries that I make sure to have installed for every project. I use conda for managing environments and package installation. Other alternatives include pip and [pyenv-virtualenv](https://jakobj.dev/posts/pyenv/#installation)
* [numpy](https://numpy.org) - [installation](https://numpy.org/install/)
* [scipy]() - [installation](https://scipy.org/install/)
* [sckit-learn](https://scipy.org/) - [installation](https://scikit-learn.org/stable/install.html)
* [matplotlib](https://matplotlib.org/) - [installation](https://matplotlib.org/stable/install/index.html)
* [seaborn](https://seaborn.pydata.org) - [installation](https://seaborn.pydata.org/installing.html)

#### Notebooks 
* [jupyter lab](https://jupyter.org/) - [installation](https://jupyter.org/install)
* [marimo](https://marimo.io/)
* [google colab](https://colab.research.google.com/)

#### Visualization Libraries 
The python visualization ecosystem is fragmented and choosing the right visualization library depends on the project and audience . Many of the python visualization libraries build off of matplotlib. Matpotlib while tedious is super power powerful and versatile, with the ability to render interactive 3d plots, conic sections and do image processing work. Seaborn is great for statistical charts with an aesthetic similar to ggplot but the syntax can get gnarly. Altair is an easy to learn member of the Vega-Lite ecosystem but requires deep knowledge of the grammar of graphics and gets knarly with interaction and customizability.
* [plotly](https://plotly.com/python/) - [installation](https://plotly.com/python/getting-started/#installation)
* [bokeh](https://bokeh.org/) - [installation](https://docs.bokeh.org/en/latest/docs/first_steps/installation.html)
* [altair](https://altair-viz.github.io) - [installation](https://altair-viz.github.io/getting_started/installation.html)

### Search + Information Retrieval
* [ElasticSearch](https://www.elastic.co/elasticsearch)

### NLP + Language Engineering
* [NLTK](https://www.nltk.org/)
* [Spacy](https://spacy.io/)

### Probabilistic Machine Learning + Generative Modeling 
These are a specialized set of tools for probabilistic machine learning and probablistic programming with efficient and accurate implementations of MCMC and other probabilistic methods/algorithms. I have not used any of these but want to try them at some point with Ben Lambert's tutorials
* [cmdstanpy](https://mc-stan.org/docs/cmdstan-guide/) - [installation](https://mc-stan.org/docs/cmdstan-guide/installation.html)
* [pymc](https://www.pymc.io/welcome.html) - [installation](https://www.pymc.io/projects/docs/en/latest/installation.html)

### Deep Learning 

### Computer Vision + Image Analysis 

### Music Informatics

### Databases 


## Interactive Visualization 
### D3
D3 - a library that has caused many ups and down for me but still I am excited about its capabilities. This is highly opinionated but D3 is done. Svelte, JavaScript, charting libraries(chart.js) and frontend engineering have slowly taken and improved D3's magic to the point that you can actually implement many features with the Canvas API, CSS, and frameworks. D3 was built for the 2009-2021 era but now the api design seems stuck in time as it clashes with frameworks that need to utilize its capabilities. To that end, with some engineering tricks and staring at the source code it is possible to integrate d3 into a framework project but it is now treated more as a module library.
* [d3.js](https://d3js.org/)
#### D3 extensions
* [D3-Annotation](https://d3-annotation.susielu.com/)
* [D3-Legend](https://d3-legend.susielu.com/)

### JavaScript Frameworks 
Not learning a JS framework was the biggest regret I had from my Utah days. For choosing a framework, it really depends on how well you know javascript and in my personal opinion understanding the difference between imperative and declarative programming (see the framework documentaries in the talks page). Now that I am pursuing machine learning its easy to get distracted about frontend and fullstack engineering but after seeing the work of [Jay Wang](https://zijie.wang/) and [Catherine Yeh](https://catherinesyeh.github.io/) I'm inspired to actually try again.
* [Svelte](https://svelte.dev/)
* [Vue](https://vuejs.org/)
* [React](https://react.dev/)

### Component Libraries 
#### Svelte 
* [Attractions UI](https://illright.github.io/attractions/)
* [Svelte UI](https://svelteui.dev/)
#### Vue 
* [Vuetify](https://vuetifyjs.com/en/)
#### React 
* [Mantine](https://mantine.dev/)

## Systems Programming 

# Things I want to learn more about in 2025
These are things I want to learn more about in 2025 related to python development and machine learning
* [tqdm](https://tqdm.github.io/)
* [rich](https://rich.readthedocs.io/en/stable/introduction.html) 
* [pathlib](https://docs.python.org/3/library/pathlib.html)
* [pydantic](https://docs.pydantic.dev/latest/)
* [ruff](https://docs.astral.sh/ruff/)

# Things I wish I had time to explore and learn more about
These are things that I wish I had time to learn more about. Hopefully I'll get a chance to use them with machine learning at some point. 
## Creative Coding 
I first heard about this at the EYEO Festival. I started with Dan Shiffman's [Coding Train](https://thecodingtrain.com/) but shifted to Kevin Workman's [Happy Coding](https://happycoding.io/) and then stopped. It was a lot of fun to use p5 and it explained some of the javascript quirks I struggled with. After seeing all the cool stuff put out by Martin Wattenberg, Golan Levin, Ravi Chugh, and Andrew McNutt I want to pick it up again and try to implement some of the projects from Code as a Creative Medium. 
* [p5.js](https://p5js.org/)
* [ml5.js](https://ml5js.org/)
* [openFrameworks](https://openframeworks.cc/)
* [cinder](https://libcinder.org/)
