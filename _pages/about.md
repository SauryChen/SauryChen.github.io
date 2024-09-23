---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an (INTJ) Ph.D candidate at [Department of Earth System Science](https://www.dess.tsinghua.edu.cn), [Tsinghua University](https://www.tsinghua.edu.cn). My major is atmospheric science, and I currently conduct research at the intersection of atmospheric science and artificial intelligence. I started working with Prof. [Haohuan Fu](http://www.thuhpgc.net/mediawiki/index.php/Haohuan_Fu) in Fall 2021, prior to that, I got my Bachelor's degree at [UM-SJTU Joint Institute](https://www.ji.sjtu.edu.cn/cn/), [Shanghai Jiao Tong University](https://www.sjtu.edu.cn), majoring in Mechanical Engineering.

👩🏻‍🎓 Education
======
+ *2021.09 - Now*       Ph.D Candidate in Department of Earth System Science, Tsinghua University, Beijing, China
  + Teaching Assistant in Big Data Analytics for Global Change Studies
+ *2017.09 - 2021.08*   B. Eng in Shanghai Jiao Tong University, Shanghai, China
  + Teaching Assistant in VM320 Fluid Mechanics and VM350 Design & Manufacturing
+ *2019.01 - 2019.02*   Winter Exchange Program in Istituto Tecnologico de Buenos Aires, Buenos Aires, Argentina

👩🏻‍💻 Experience
======
+ *2024.08 - Now*       Research Intern @ National Supercomputing Center (Shenzhen)
  + Weather predictablity and interpretability
+ *2021.03 - 2021.05*   Research Intern @ Pilot National Laboratory for Marine Science and Technology
  + Optimization of NEMO ocean model on the Sunway Supercomputer
+ *2020.02 - 2021.02*   Research Intern @ National Supercomputing Center (Wuxi)
  + Identifying deep convection with machine learning

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
