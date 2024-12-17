---
layout: default
title: tools-reference
nav_order: 2
---

# Tools
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
# Things I am currently using (as of December 2024)

## Programming Languages 
* Python - main language for ml stuff these days
* Golang - occasionally for fun - want to get back to it at some point
* Java - slowly getting back into this - very important for data engineering (hadoop, spark, scala, big data processing). thought I'd never never have to write java again after CS 1410 and CS 2420 at Utah
* JavaScript - occasionally for fun and vis work. on my list to revist to understand how to actually use events for svelte applications
* SQL - haven't used in a long time 

## Data Libraries + Tools
These are libraries that I make sure to have installed for every project. I use conda for managing environments and package installation. Other alternatives include pip and [pyenv-virtualenv](https://jakobj.dev/posts/pyenv/#installation) 
* [numpy](https://numpy.org) - [installation](https://numpy.org/install/) 
* [scipy]() - [installation](https://scipy.org/install/)
* [sckit-learn](https://scipy.org/) - [installation](https://scikit-learn.org/stable/install.html) 
* [matplotlib](https://matplotlib.org/) - [installation](https://matplotlib.org/stable/install/index.html)
* [jupyter lab](https://jupyter.org/) - [installation](https://jupyter.org/install)

## Bayesian Modeling + Inference Tools
These are a specialized set of tools for probabilistic machine learning and probablistic programming with efficient and accurate implementations of MCMC and other probabilistic methods/algorithms. I have not used any of these but want to try them at some point with Ben Lambert's tutorials
* [pystan](https://pystan.readthedocs.io/en/latest/) - [installation](https://pystan.readthedocs.io/en/latest/installation.html)
* [pymc](https://www.pymc.io/welcome.html) - [installation](https://www.pymc.io/projects/docs/en/latest/installation.html)

## Visualization Libraries + Tools
The python visualization ecosystem is fragmented and choosing the right visualization library depends on the project and audience . Many of the python visualization libraries build off of matplotlib. Matpotlib while tedious is super power powerful and versatile, with the ability to render interactive 3d plots, conic sections and do image processing work. Seaborn is great for statistical charts with an aesthetic similar to ggplot but the syntax can get gnarly. Altair is an easy to learn member of the Vega-Lite ecosystem but requires deep knowledge of the grammar of graphics and gets knarly with interaction and customizability.
* [seaborn](https://seaborn.pydata.org) - [installation](https://seaborn.pydata.org/installing.html)
* [plotly](https://plotly.com/python/) - [installation](https://plotly.com/python/getting-started/#installation)
* [altair](https://altair-viz.github.io) - [installation](https://altair-viz.github.io/getting_started/installation.html)
* [bokeh](https://bokeh.org/) - [installation](https://docs.bokeh.org/en/latest/docs/first_steps/installation.html)

## Publishing + Writing
* [Quarto](https://quarto.org/)
* [Typst](https://typst.app/)

## LLMs 
LLMs are now ubiquitous and I highly recommend experimenting with one. As a student, I don't know if its worth paying for a subscription(they are super expensive on a student budget - equivalent to a streaming subscription!! and there are no discounts with github studentpack) but I find using a combination of ChatGPT, Claude and Gemini to be highly effective since each tool has its own pros and cons - Claude is really good at generating code examples and explaining code, Gemini is great for exploring ideas and has unlimited photo upload, and ChatGPT has a really nice UI for math equations. Other ones I haven't tried are [Perplexity](https://www.perplexity.ai/), [Khanmingo](https://www.khanmigo.ai/learners). 
* [ChatGPT](https://chatgpt.com/)
* [Claude](https://claude.ai/)
* [Gemini](https://gemini.google.com/)

## Engineering 
### Development 
* [TMux](https://hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)
### Prototyping 
* [p5.js Web Editor](https://editor.p5js.org/)
* [Svelte REPL](https://svelte.dev/repl/)
### Testing
* [pyTest](https://docs.pytest.org/en/stable/)

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
## JavaScript Frameworks
Not learning a JS framework was the biggest regret I had from my Utah days and I think part of the reason why I had to give up on visualization engineering. For choosing a framework, it really depends on how well you know javascript and in my personal opinion understanding the difference between imperative and declarative programming (see the framework documentaries in the talks page). Now that I am pursuing machine learning its easy to get distracted about frontend and fullstack engineering but after seeing the work of [Jay Wang](https://zijie.wang/) and [Catherine Yeh](https://catherinesyeh.github.io/) I'm inspired to actually try again.

As for what framework I want to try - I would love to try svelte because I've seen it used frequently in the ml-vis space. Vue is another possibility. 
* [Svelte](https://svelte.dev/)
### Svelte Component Libaries
* [Attractions UI](https://illright.github.io/attractions/)
* [Svelte UI](https://svelteui.dev/)

## Visualization 
D3 - a library that has caused many ups and down for me but still I am excited about its capabilities. This is highly opinionated but D3 is done. Svelte, JavaScript, charting libraries(chart.js) and frontend engineering have slowly taken and improved D3's magic to the point that you can actually implement many features with the Canvas API, CSS, and frameworks. D3 was built for the 2009-2021 era but now the api design seems stuck in time as it clashes with frameworks that need to utilize its capabilities. To that end, with some engineering tricks and staring at the source code it is possible to integrate d3 into a framework project but it is now treated more as a module library. I still want to revist it but maybe after I get a firm understanding of javascript fundamentals with svelte, canvas, p5.js. 
* [d3.js](https://d3js.org/)
### D3 extensions 
* [D3-Annotation](https://d3-annotation.susielu.com/)
* [D3-Legend](https://d3-legend.susielu.com/)

# Random 
* [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/)

# Other tools
Tools and libraries that I've seen used in the AIML + visualization communities that people may find interesting that I don't have time to learn.

## Creative Coding  
* [ml5.js](https://ml5js.org/)
* [openFrameworks](https://openframeworks.cc/)
* [cinder](https://libcinder.org/)

## JavaScript Libraries and Frameworks 
### React 
* [React](https://react.dev/)
* [next.js](https://nextjs.org/)
#### React Components 
* [Mantine](https://mantine.dev/)
### Vue 
* [Vue](https://vuejs.org/)
#### Vue Components 
* [Vuetify](https://vuetifyjs.com/en/)