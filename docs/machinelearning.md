---
layout: default 
title: machine learning
nav_order: 2
---

# How to Learn Machine Learning 
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Background 
This page is a list of everything that I have found to learn machine learning in the llm chatgpt era. I used a lot of these references during my undergrad and I discovered new resources and courses that helped me study for some of the challenging courses during my masters program. [Kylie Ying](https://youtube.com/playlist?list=PLkWv3oO4kHnu095L52vLCVK8YN33yRrd_&feature=shared), [Chip Huyen](https://huyenchip.com), [Josh Starmer](https://statquest.org) were a huge inspiration for this page because of how they organized the content on their websites and youtube channels. I recommend following the materials starting from the **Introduction** to **Machine Learning Fundamentals** in order to understand the material in the **Machine Learning Subfields** section.

Lastly, I recommend that every person who wants to study machine learning read ***The Worlds I See: Curiosity, Exploration, and Discovery at the Dawn of AI*** by [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li). 


## Introduction 
* [Chip Huyen A survivor's guide to Artificial Intelligence](https://huyenchip.com/2018/03/30/guide-to-Artificial-Intelligence-Stanford.html)
* [Chip Huyen ML Ops Guide](https://huyenchip.com/mlops/)
* [What is Machine Learning?](https://youtu.be/bk12t0Xz5FM?feature=shared)
* [How to learn Machine Learning](https://youtu.be/BLXZsBd1cDs?feature=shared)

## Mathematics 
### Calculus 
* [Utah MATH 1210 - Differential Calculus](https://www.math.utah.edu/lectures/math1210.php)
* [Utah MATH 1220 - Integral Calculus](https://www.math.utah.edu/lectures/math1220.php)
* [Utah MATH 2210 - Multivariable Calculus](https://www.math.utah.edu/lectures/math2210.php)
* [Intro to Derivatives Calculus for Machine Learning](https://youtu.be/tOfdzeYRadc?feature=shared)
* [3Blue1Brown Essence of Calculus](https://youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&feature=shared)

### Probability and Statistics 
#### Advice 
* [5 tips for getting better at statistics](https://www.youtube.com/watch?v=StSAJIZuqws) 
#### Deep Dives 
* [Random Variables](https://www.youtube.com/watch?v=Y9nsL69CwbU) 
* [Parameters](https://www.youtube.com/watch?v=BDExlZu2Va8)
* [Estimators](https://www.youtube.com/watch?v=iAcK2Tve1pw)
* [Explaining Probability Distributions](https://youtu.be/k5sbE1_MDwU?feature=shared)
* [Parametric Families](https://www.youtube.com/watch?v=GOJkxzkN3m0) 
* [Probability Must-Knows for Machine Learning-Math for ML Part 1](https://youtu.be/oyyFpAwyt6w?feature=shared)
* [Statistics: Sampling and Describing Data-Math for ML Part 2](https://youtu.be/M2S_9lyRMvo?feature=shared)
* [Random Variables and Normal Distributions-Math for Machine Learning Part 3](https://youtu.be/BsV5k-80MJQ?feature=shared)
* [The better way to do statistics - Introduction to Bayesian Statistics](https://www.youtube.com/watch?v=3jP4H0kjtng)
* [3Blue1Brown Bayes Theorem](https://youtu.be/HZGCoVF3YvM?feature=shared)
* [3Blue1Brown Probability of Probabilities](https://youtube.com/playlist?list=PLZHQObOWTQDOjmo3Y6ADm0ScWAlEXf-fp&feature=shared) 
* [3Blue1Brown Central Limit Theorem and the Gaussian Distribution](https://youtube.com/playlist?list=PLZHQObOWTQDOMxJDswBaLu8xBMKxSTvg8&feature=shared)

#### Probability and Statistics for Machine Learning 
* [Stanford CS 109: Probability and Statistics for Computer Scientists](https://web.stanford.edu/class/cs109/)
* [Stanford CS 109: Probability and Statistics for Computer Scientists - Lectures ](https://www.youtube.com/watch?v=2MuDZIAzBMY&list=PLoROMvodv4rOpr_A7B9SriE_iZmkanvUg&index=2)
* [Steven Brunton - Probability Bootcamp](https://www.youtube.com/watch?v=sQqniayndb4&list=PLMrJAkhIeNNR3sNYvfgiKgcStwuPSts9V)
* [Steven Brunton - Introduction to Statistics and Data Analysis](https://www.youtube.com/watch?v=QIXUTsdj_oA&list=PLMrJAkhIeNNT14qn1c5qdL29A1UaHamjx)
##### Bayesian Statistics 
At KTH, one of the required ML courses is [DD2434-Advanced Machine Learning](https://www.kth.se/student/kurser/kurs/DD2434?l=en) which focuses solely on variational inference, one of the most mind bending concepts in machine at the heart of today's generative modeling. Variational Inference assumes a background in Bayesian Statistics which is usually taught as advanced graduate class. I came across this series by [Ben Lambert](https://ben-lambert.com/about/) after the class which attempts to teach this statistics assuming no statistics background and had I known about it during the class, it would have helped me better understand some of [David Blei's](https://www.cs.columbia.edu/~blei/) papers which we had to read and implement in this class. I highly recommend this series to understand some of the techniques and math behind **variational autoencoders, KL Divergence, and Bayesian Deep Learning**. 
* [A student's guide to Bayesian Statistics](https://youtube.com/playlist?list=PLwJRxp3blEvZ8AKMXOy0fc0cqT61GsKCG&feature=shared)

### Linear Algebra 
* [3Blue1Brown Essence of Linear Algebra](https://youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&feature=shared)
* [MIT 18.06 - Linear Algebra](https://github.com/mitmath/1806)

### Mathematics of Machine Learning, Data Science and Big Data 
* [Utah CS 3190 - Foundations of Data Analysis](https://users.cs.utah.edu/~jeffp/teaching/FoDA.html)
* [StatQuest](https://statquest.org/video-index/)

## Programming 
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [Python for Data Analysis](https://wesmckinney.com/book/)
* [Machine Learning with PyTorch and Scikit-Learn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/) - follow this book if you want to learn PyTorch
* [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) - follow this book if you want to learn TensorFlow which is still used heavily for production machine learning

## Machine Learning Fundamentals 
### Statistical Learning
* [Statistical Learning With Python](https://youtube.com/playlist?list=PLoROMvodv4rPP6braWoRt5UCXYZ71GZIQ&feature=shared)
### Machine Learning 
* [KTH DD1420 - Foundations of Machine Learning](https://dd1420.notion.site/DD1420-Lecture-Notes-b555e017345a4119950ce8fd67133275)
* [University of Utah CS 6350 - Machine Learning](https://users.cs.utah.edu/~zhe/teach/cs6350.html)
### Probabilistic Machine Learning 
Probabilistic Machine Learning is probably the most mind-bending machine learning out there. It's so mind-bending that almost all teaching and reference materials reference [Michael I. Jordan](https://www2.eecs.berkeley.edu/Faculty/Homepages/jordan.html) and [David Blei](https://www.cs.columbia.edu/~blei/) who not only pioneered applying bayesian statistics to this area but the applications in healthcare, economics, topic modeling, machine learning interpretability and more. Since the area is very broad, programs emphasize different methods: Markov Chain Monte Carlo (MCMC), Metropolis Hastings (MH), Gibbs, Variational Inference. The KTH DD2434 focuses exclusively on variational inference because it underpins the variational-autoencoders (VAE) technique. The courses listed here focus on a mixture of all the methods but for most people who want to understand VAE, I would just recommend focusing on variational inference.
* [Probabilistic Machine Learning](https://www.youtube.com/playlist?list=PLISXH-iEM4JlFsAp7trKCWyxeO3M70QyJ)
* [University of Utah CS 6190 - Probabilistic Modeling](https://users.cs.utah.edu/~zhe/teach/archived/2024s/cs6190-lectures.html)
* [Stanford CS 228 - Probabilistic Graphical Models Notes](https://ermongroup.github.io/cs228-notes/)
* [Probabilistic Programming and Bayesian Methods for Hackers](https://dataorigami.net/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
### Natural Language Processing and Information Retrieval 
* [Stanford CS 124 -  From Languages to Information](https://web.stanford.edu/class/cs124/)
* [Stanford CS 124 - From Languages to Information - Lectures](https://www.youtube.com/playlist?list=PLaZQkZp6WhWyvdiP49JG-rjyTPck_hvEu)
* [Stanford CS 124 - From Languages to Information - Course GitHub](https://github.com/cs124)

## Machine Learning Subfields 
### Neural Networks - Fundamentals 
* [Neural Networks Zero to to Hero - Lectures 1-6](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&si=riojyDtCd_RJHEwr)
* [3Blue1Brown Neural Networks Lectures 1-4](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&feature=shared)
### Neural Networks - LLMS
* [Grant Sanderson Visualizing transformers and attention](https://youtu.be/KJtZARuO3JY?si=r11r-0NbrX1H1o7L)
* [Andrej Karpathy 1 Hour Intro to Large Language Models](https://youtu.be/zjkBMFhNj_g?si=WKa2-OhiOUeBXEeJ)
* [Andrej Karpathy Deep Dive Into LLMs Like ChatGPT](https://youtu.be/7xTGNNLPyMI?si=hSpi8NGr-7EWG_RB)
* [Neural Networks Zero to to Hero - Lectures 7, 9-10](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&si=riojyDtCd_RJHEwr)
* [3Blue1Brown Neural Networks - Lectures 5-8](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&feature=shared)

### Interpretability 
* [Utah CS 6966 - Local Explanations for Deep Learning Models](https://www.anamarasovic.com/teaching/) 
* [Neural Networks are Weird! Neel Nanda](https://youtu.be/YpFaPKOeNME?si=1byw9-F_qWdX35sA)
* [Mechanistic Interpretability - Neel Nanda](https://youtu.be/_Ygf0GnlwmY?si=pdB6Lm6xQREH39eB)
* [Neel Nanda Mechanistic Interpretability Materials](https://www.neelnanda.io/mechanistic-interpretability)

### Alignment 
* [ARENA](https://arena-resources.notion.site/ARENA-Virtual-Resources-ba4481a64239456bb5a9b3d37a7765f6)

### Data Centric Machine Learning 
* [MIT Data Centric AI](https://dcai.csail.mit.edu/)

### Scalable Machine Learning + ML Systems 
* [Made With ML](https://madewithml.com/)
* [KTH ID 2221 - Data Intensive Computing Platforms](https://id2221kth.github.io/)
* [KTH ID 2223 - Scalable Machine Learning and Deep Learning](https://id2223kth.github.io/)
* [Serverless Machine Learning & Principles of MLOps](https://www.serverless-ml.org/sml-course)

### Deep Generative Modeling
* [Stanford CS 236 - Deep Generative Models](https://deepgenerativemodels.github.io/)
* [Stanford CS 236 - Deep Generative Models Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rPOWA-omMM6STXaWW4FvJT8)
* [Stanford CS 236 - Deep Generative Model Models Notes](https://deepgenerativemodels.github.io/notes/index.html)

### Search Engines, Information Retrieval, Data Mining
* [CS 224N Natural Language Processing With Deep Learning](https://web.stanford.edu/class/cs224n/)
* [CS 224N Natural Language Processing With Deep Learning - Lectures](https://youtube.com/playlist?list=PLoROMvodv4rMFqRtEuo6SGjY4XbRIVRd4&si=gO-JiDUekbbotgA1)
* [Utah CS 6340 - Natural Language Processing](https://www.anamarasovic.com/teaching/) 
* [Utah CS 6140 - Data Mining Spring 2023](https://utah-data-mining-spring23.github.io/)
* [Utah CS 6140 - Data Mining](https://users.cs.utah.edu/~jeffp/)

### Image Analysis and Computer Vision 
* [Stanford CS 231N](https://cs231n.stanford.edu/)
* [Stanford CS 231N 2017 - Lectures](https://youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv&si=Qf-Ew3kHTTC1hOGi)
* [Hany Farid Computer Vision](https://youtube.com/playlist?list=PLhwIOYE-ldwL6h-peJADfNm8bbO3GlKEy&feature=shared)

### Human-AI Interaction - Visualization, Creative Coding, Audio ML
#### Visualization 
* [MIT 6/11.C85 - Interactive Data Visualization & Society](https://vis-society.github.io/)
* [Svelte + D3](https://www.youtube.com/playlist?list=PLNvnDrMLMSipfbxSp1Z4v9Ydu2ud5i9V8)
#### Creative Coding 
* [Machine Learning for the Web](https://github.com/yining1023/machine-learning-for-the-web)
* [Machine Learning for Physical Computing](https://github.com/yining1023/Machine-Learning-for-Physical-Computing)
* [Harvard CS 73](https://wattenberg.github.io/cs73/)
* [UChicago Creative Coding](https://people.cs.uchicago.edu/~rchugh/classes/creative-coding/)
* [Golan Levin Experimental Capture Class](https://github.com/golanlevin/ExperimentalCapture)
#### Audio ML 
* [Audio Signal Processing for Machine Learning](https://youtube.com/playlist?list=PL-wATfeyAMNqIee7cH3q1bh4QJFAaeNv0&feature=shared)

## Engineering - Machine Learning, Computer Science
* [MIT - The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)
* [Coding Challenges](https://codingchallenges.fyi/challenges/intro)
* [Advent of Code](https://adventofcode.com/)
* [Utah MSD Git](https://youtube.com/playlist?list=PLbdXd8eufjyUwR5ksEiFu529UD_kY1A_a&feature=shared)
* [Chip Huyen AIE Book Reference](https://github.com/chiphuyen/aie-book/blob/main/resources.md#ml-theory-fundamentals)

## answerAI 
[answerAI](https://www.answer.ai/) was founded by Jeremy Howard and Eric Rees in 2023 as a new R&D lab focusing on fundamental research and the development of practical applications based on research breakthroughs. answerAI is the successor to [fastAI](https://www.fast.ai/) which was founded by Jeremy Howard and [Rachel Thomas](https://rachel.fast.ai/). fastAI left a legacy with its machine learning research and highly regarded state of the art machine learning courses that aimed to make deep learning accessible to everyone regardless of their math background which was revolutionary at the time the courses were released. Today fastai's materials are still used as an entry to the fields of deep learning and generative AI and at the University of San Francisco MS Data Science Program. Jeremy and his team still produce educational videos from time to time on [youtube](https://youtube.com/@howardjeremyp?feature=shared) and [continue to teach and innovate](https://www.answer.ai). 
#### Materials 
* [Book]((https://course.fast.ai/Resources/book.html))
* [Kaggle Notebooks](https://www.kaggle.com/jhoward/code)
* [PyTorch Image Models](https://timm.fast.ai/)
* [FastAI Library](https://docs.fast.ai/)
### fastAI 
* [Lesson 0: How to fastAI](https://youtu.be/gGxe2mN3kAg?feature=shared)
* [Part 1: Deep Learning for Coders](https://course.fast.ai/)
* [Part 2: From Deep Learning to Stable Diffusion](https://course.fast.ai/Lessons/part2.html)
* [Computational Linear Algebra](https://www.fast.ai/posts/2017-07-17-num-lin-alg.html)
* [Code-First Intro to NLP](https://www.fast.ai/posts/2019-07-08-fastai-nlp.html)
### answerAI 
* [A Hacker's Guide to Language Models](https://youtu.be/jkrNMKz9pWU?feature=shared)
* [Getting Started with CUDA for Python Progammers](https://youtu.be/nOxKexn3iBo?feature=shared)
* [Going Further with CUDA for Python Progammers](https://youtu.be/eUuGdh3nBGo?feature=shared)
* [GPU Programming in the Browser](https://www.answer.ai/posts/2024-09-12-gpupuzzles.html)
