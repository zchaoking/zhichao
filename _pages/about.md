---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Zhichao Wang was a Research Fellow at [Electrical Engineering and Telecommunications](https://www.unsw.edu.au/engineering/our-schools/electrical-engineering-telecommunications) at [University of New South Wales](https://www.unsw.edu.au), under supervision of [Prof. Victor Solo](https://www2.ee.unsw.edu.au/~victors/). Before that he got the Phd degree from [Tsinghua University](https://www.tsinghua.edu.cn/en/), department of automation, China. 
His papers have been published in the top-tier conferences and journals in the field of machine learning,  data mining and control science, such as CDC, ICASSP, CVPR, AAAI, CIKM, Journal of Process Control, IEEE-TCSVT, IEEE- VLDB, IEEE-TKDE, ACM-TKDD, IEEE-TNNLS etc.

## News
- [4-June-2024] Our research paper titled "HOT-GAN: Hilbert Optimal Transport for Generative Adversarial Network" is online by top journal IEEE Transactions on Neural Networks and Learning Systems  (TNNLS, CORE A*),
- [2 Oct 2023 ]Our research paper titled "Be causal: De-biasing social network confounding in recommendation" is accepted by top journal ACM Transactions on Knowledge Discovery from Data  (TKDD, CORE A*), Congratulations to Xiangmeng and Dianer! 
I was invited as program committee for NeurIPS2023, ICML2023
- [2 March 2022] Our research paper titled "Causal Disentanglement for Semantics-Aware Intent Learning in Recommendation" is accepted by top journal IEEE Transactions on Knowledge and Data Engineering (TKDE, CORE A*), Congratulations to Xiangmeng and Dianer! 
I was invited as program committee for CVPR2022, ICML2022
- [27 September 2021]One research paper titled "Causal Optimal Transport for Treatment Effect Estimation." is accepted by top journal IEEE Transactions on Neural Networks and Learning Systems (TNNLS, CORE A*).
- [5 September 2021]I was invited as a program committee for ICLR2022.
- [17 August 2021] I was invited as a program committee for AAAI2022.
- [9 August 2021] One research paper on causal reasoning is accepted by the top conference - CIKM 2021 (CORE A).
- [20 July 2021] I was invited as a reviewer for Journal of Knowledge based systems. 
- [15 July 2021] One research paper titled "Convergence of a Tangent Space Numerical Scheme for a Stochastic Differential Equation on a Sphere " is accepted by IEEE CDC 2021.
- [9 March 2021] One research paper titled "Hilbert Sinkhorn Divergence for Optimal Transport" is accepted by the top conference - CVPR 2021 (CORE A*).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
