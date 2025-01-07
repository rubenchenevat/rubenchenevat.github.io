---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student (in 3rd and final year) in Applied Mathematics at [UMR MISTEA](https://eng-mistea.montpellier.hub.inrae.fr/) - [INRAE](https://www.inrae.fr/en), Université de Montpellier (France), under the supervision of [Alain Rapaport](https://sites.google.com/site/alainrapaport/) (MISTEA), [Sébastien Roux](https://www.researchgate.net/profile/Sebastien-Roux-2) (MISTEA) and [Bruno Cheviron](https://www.researchgate.net/profile/Bruno-Cheviron) ([UMR G-EAU](https://www.g-eau.fr/index.php/en/)).


Research interests
======
I am interested in how mathematics can contribute to other fields of scientific research, especially natural sciences (physics, biology) and their applications such as environment, health, energy... In other words, I aspire to tackle questions from these applied topics, that may be transposed into mathematical formalism, and for which one can seek to develop mathematical theory leading to scientific advances.

Current works
======
My thesis focuses on <strong>crop irrigation decision support tools</strong> based on the optimization of analytical and numerical models, in a context of climate change and preservation of water resources. The motivation is to provide a real-time decision, integrating seasonal management constraints and weather uncertainties. I consider a <strong>double modeling</strong> approach that relies on investigating a mathematical model on which I develop results from <strong>optimal control theory</strong>, and interacting with the numerical model <strong>[Optirrig](https://www.g-eau.fr/index.php/en/productions/software/item/1036-optirrig-generation-analyse-et-optimisation-de-scenarios-d-irrigation-pour-les-cultures)</strong> for operational purposes.

I am currently working on the elaboration of irrigation strategies suitable for the case of medium term unknown rainfall sequences, and the analysis of their efficiency. This project recquires considering <strong>stochastic control</strong> and <strong>adaptive/predictive methods</strong> to handle the non-deterministic behaviour.

In parallel, I am also working on two projects. The first one is about studying the irrigation problem considering both fresh water and reuse water, therefore leading to the analysis and control of a <strong>switched dynamical system</strong>.

The second one aims at generalizing a technique used for solving my irrigation problem under <strong>state constraints</strong>, consisting in a reformulation into an equivalent optimal control problem without state constraint, thus suited to the standard Pontryagin maximum principle. I am then looking for a class of problems where this technique holds.


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
