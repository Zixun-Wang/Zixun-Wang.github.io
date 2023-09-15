---
permalink: /
title: "Education"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
* Institute of Physics Chinese Academy of Sciences
  * Undergraduate Student in Jici Yan Honor Program, expected 2024

* Jilin University
  * Undergraduate Student majoring in Physics, expected 2024
  * GPA : 3.9/4.0
  * TOEFL : 108/120
    
Research Experience
======
1. <font size=5>Metadynamics with Machine Learning Potentials</font>   
  * *Summer internship at University of Saskachewan, Saskatoon, Canada*      
  * Supervisor : Prof. Yansun Yao
  * July.2023--Present
  * I have attempted to use machine learning molecular dynamics potentials for Metadynamics simulations to study phase transitions. In comparison to traditional molecular dynamics, this method allows for simulations at a larger scale (around 500,000 atoms). I have already conducted benchmarks on Si and GaN. We hope that it can address the phase transition process of compressing onion carbon into diamond.

2. <font size=5>One-dimensional Ferroelectric</font>   
  * *Research Assistant at Westlake University, Hangzhou, China*      
  * Supervisor : Prof. Shi Liu
  * Dec.2022--Present
  * I employed density functional theory (DFT) to obtain a family of stable 1D nanothreads from cutting III-V two-dimensional triatomic layers anti-ferroelectric materials. This is the first predicted stable one-dimensional anti-ferroelectric and ferroelectric structure. These nanothreads exhibit anti-ferroelectric phases, along with radial polarization. The radial polarization can be reversed under the influence of an electric field. This discovery holds significant promise for memory applications, marking a breakthrough in the field of low-dimensional anti-ferroelectrics. The results will be submitted in the form of a research paper.
![Editing a markdown file for a talk](/images/structure of o2.png "structure of ferroelectirc nanothread") 

3. <font size=5>Ideal Strength Calculation Software</font>   
  * *Research Assistant at Jilin University, Changchun, China*      
  * Supervisor : Prof. Hanyu Liu
  * July.2022--May.2023
  * I have developed software for calculating the ideal strength of materials based on first-principles calculations, building upon the previous work of our research group. This software can compute the ideal strength of materials under arbitrary stress directions and supports simulations with different indenter shapes, such as simulating Vickers hardness. The source code has been uploaded to: [github](https://github.com/Zixun-Wang/MatElastPy)
The results are being submitted as a research paper, and a preprint version is available at: 
 [arxiv](https://arxiv.org/abs/2309.01137)

Skills
======
Programming languages : Python, C/C++, Linux script, $\LaTeX$
Software : VASP, Lammps, Quantum Espresso, Deepmd-kit, etc.

Honors
======
* National Scholarship 2022
* University-level outstanding students 2022
* University-level outstanding student cadres 2022/2023


Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
