---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

Education
======
- **Georgia Institute of Technology**, Atlanta, GA
  - **Ph.D.** in Computer Science, Fall 2009 - August 2013
    - Thesis Topic: Shared Resource Management for Efficient Heterogeneous Computing
    - Thesis Advisor: [Prof. Hyesoon Kim](http://cc.gatech.edu/~hyesoon)
  - **M.S.** in Computer Science, May 2009
  - [Graduate courses]({% link _pages/course.md %})
- **Sogang University**, Seoul, Korea
  - B.S. in Computer Science, February 2007

Work Experience
======
- Research Engineer, November 2017 - Present<br>
  Arm Research, Austin, TX<br></li>
- Silicon Architecture Engineer, September 2013 - November 2017<br>
  MIC (Xeon-Phi) Architecture, Intel/PDG, Hillsboro, OR</li>
- Graduate Research Assistant, 2008 - 2013<br>
  Georgia Institute of Technologoy, Atlanta, GA</li>
- Graduate Intern Technical, May 2012 - August 2012<br>
  Platform architecture research group, Intel Labs, Intel, Santa Clara, CA<br>
  Manager: Mani Azimi</li>
- Graduate Intern Technical, May 2011 - August 2011<br>
  Visual and Parallel Computing Group (VPG), Intel, Austin, TX<br>
  Manager: Eric Sprangle</li>

Publications
======
1. **Jaekyu Lee**, Dong Hyuk Woo, Hyesoon Kim, and Mani Azimi, "GREEN Cache: Exploiting the Disciplined Memory Model of OpenCL on GPUs", In IEEE Transactions on Computers (TC), Volume: 64, Issue: 11, Nov. 1 2015</li>
1. **Jaekyu Lee**, Si Li, Hyesoon Kim, and Sudhakar Yalamanchili, "Design Space Exploration of On-chip Ring Interconnection for a CPU-GPU Heterogeneous Architecture", In Journal of Parallel and Distributed Computing (JPDC), Vol. 73, Issue 12, pp. 1525-1538, December 2013
1. **Jaekyu Lee**, Si Li, Hyesoon Kim, and Sudhakar Yalamanchili, "Adaptive Virtual Channel Partitioning for Network-on-Chip in Heterogeneous Architectures" In ACM Transactions on Design Automation of Electronic Systems (TODAES), Vol. 18, No. 4, pp.48:1-48:28, October 2013
1. Jaewoong Sim, **Jaekyu Lee**, Moinnuddin Qureshi, and Hyesoon Kim, "FLEXclusion: Balancing Cache Capacity and On-Chip Traffic with Flexible Exclusion" In Proc. of the 39th Int'l Symp. on Computer Architecture (ISCA-39), Portland, OR, June, 2012 (acceptance rate 18% (47/262))
1. **Jaekyu Lee**, Hyesoon Kim, and Richard Vuduc, "When Prefetching Works, When It Doesn't, and Why", In ACM Transactions on Architecture and Code Optimization (TACO), Vol. 9, No. 1, pp.2:1-2:29, March 2012. Also invited to 8th Int'l Conf. on High-Performance and Embedded Architectures and Compilers (HiPEAC), January, 2013
1. **Jaekyu Lee** and Hyesoon Kim, "TAP: A TLP-Aware Cache Management Schemes for a CPU-GPU Heterogeneous Architecture", In Proc. of the 18th Int'l Symp. on High Performance Computer Architecture (HPCA-18), pp.91-102, New Orleans, LA, February, 2012 (acceptance rate 17% (36/210))
1. Nagesh B. Lakshminarayana, **Jaekyu Lee**, Hyesoon Kim, and Jinwoo Shin, "DRAM Scheduling Policy for a GPGPU Architecture Based on a Potential Function", IEEE Computer Architecture Letters (CAL), 2011
1. **Jaekyu Lee**, Nagesh B. Lakshminarayana, Hyesoon Kim, and Richard Vuduc, "Many-Thread Aware Prefetching Mechanisms for GPGPU Applications", In Proc. of the 43rd Int'l Symp. of Microarchitecture (MICRO-43), pp.213-224, Atlanta, GA, December, 2010 (acceptance rate 18% (45/248))
1. Nagesh B. Lakshminarayana, **Jaekyu Lee**, and Hyesoon Kim, "Age Based Scheduling for Asymmetric Multiprocessors", SC, pp.25:1-25:12, November, 2009 (acceptance rate 23% (59/261))


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
