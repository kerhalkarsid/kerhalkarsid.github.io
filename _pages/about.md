---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a PhD candidate at [School for Marine Sciences and Technology](https://www.umassd.edu/smast/) at University of Massachusetts Dartmouth (UMassD). I am a [Distinguished Doctoral Fellowship](https://www.umassd.edu/graduate/fellowships--funding/distinguished-doctoral-fellowships/) awardee from the University (2019-20,2021-2024), working under the guidance of Prof. Amit Tandon. I primarily study the upper ocean processes, its evolution and its implications on air-sea interaction at smaller length and time scales, in order to understand how these processes are an important source of feedback on larger scale oceanic and atmospheric processes. For my PhD dissertation, I focus on the Diurnal Warm Layers in the Bay of Bengal, which evolves over a day and has potential implications on small scale ocean mixing, larger scale ocean circulation and atmosphere processes like the Indian Summer Monsoons. For more on my research, please see my [research](https://kerhalkarsid.github.io/research/) page. Prior to my graduate school experience here, I pursued my undergraduate in [Indian Institute of Technology, Bhubaneswar, India](www.iitbbs.ac.in), majoring in mechanical engineering.

Academic motivation
======
I spent my childhood in Visakhapatnam, a city located in the East Coast of India and thus I have always been curious about ocean dynamics, tropical cyclones, Indian summer monsoons and ocean-atmosphere exchanges. My deep love for mathematics and physics inspired me to major in mechanical engineering during my undergraduate at Indian Institute of Technology Bhubaneswar and learn about core concepts like fluid dynamics, thermodynamics, heat transfer etc. During the same time, I stumbled upon the course "Introduction to Ocean Dynamics", followed by "Fundamentals of Weather and Climate" during my time as an undergrad student at IIT Bhubaneswar. My fascination for such phenomenon coupled with a desire to make meaningful contributions to the society ensured that I first pursued a summer fellowship at [Indian National Center for Ocean Information Services, Hyderabad](https://incois.gov.in/), following which I applied for my current position as a PhD candidate in [Tandon labs](https://tandonlab.sites.umassd.edu/). 

If you are interested to know more about this journey, the following [article](https://gss.umassd.edu/2020/11/04/student-spotlight-siddhant-kerhalkar/) will be an interesting read.

# Webpage still under construction

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
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
