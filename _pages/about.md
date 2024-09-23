---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a researcher and software engineer in the field of robotics. My primary expertise lies in robotic manipulation and developing data-driven solutions for real-world robotic challanges. I worked on plenty of robotic projects where I utilised AI models for intelligent robot planning and control using visual, tactile, and propioception feedback. 

I started working with robots in my MSc in Mechatronics Engieering at a [surgical robotic research center](https://sinamed.ir/products/sina-flex-telesurgery) developing tele-operation controllers. I continued my journey by doing my PhD at [Intelligent Manipulation Lab](https://intmanlab.com/index.html) by conducting ground-braking research in tactile-based slip controllers in roboitc manipulation tasks. I am currently a postdoctoral research associate at [Lincoln Institute for Agri-Food Technology](https://www.lincoln.ac.uk/liat/) working on autonomous navigation and 3D modelling of different types of crops. You can find demonstrations of my robotic projects bellow.

<style>
  .custom-bullets ul {
    list-style-type: none; /* Remove default bullet points */
    padding-left: 0; /* Remove indentation */
  }

  .custom-bullets ul li {
    margin-bottom: 10px; /* Add some space between list items */
    list-style-image: none; /* Ensure no other bullet images */
    display: flex;
    align-items: center;
  }

  .custom-bullets ul li img {
    width: 24px; /* Set the desired width */
    height: 24px; /* Set the desired height */
    margin-right: 10px; /* Space between the image and text */
  }
</style>

<div style="display: flex; justify-content: space-between; gap: 1px;">
  <div style="flex: 1; margin-right: 0px;">
    <h2>Interests</h2>
    <ul>
      <li>Robotics</li>
      <li>Data-Driven Control</li>
      <li>Tactile Sensing</li>
      <li>Machine Learning</li>
      <li>Artificial Intelligence</li>
    </ul>
  </div>

  <div style="flex: 1; margin-left: 0px;" class="custom-bullets">
    <h2>Education</h2>
    <ul>
      <li><img src="/images/graduation.png" alt="Hat icon"> PhD in Computer Science, 2020-2024 <br> University of Lincoln</li>
      <li><img src="/images/graduation.png" alt="Hat icon"> MSc in Mechatronics Engineering, 2014-2017 <br> Sharif University of Technology</li>
      <li><img src="/images/graduation.png" alt="Hat icon"> BSc in Mechanical Engineering, 2010-2014 <br> Amirkabir University of Technology</li>
    </ul>
  </div>
</div>


Robotic Projects
======
### Project 1: Title of the Project
**Description:**  
A short paragraph describing your project. Include important details such as what the project is about, the technology stack, the challenges you faced, and what was achieved.

**Video:**

<div style="text-align: center;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/_v7zXF9FROo?si=hR4pP20js0BSIlxm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

**Related Paper:**  
[Download the Paper](https://example.com/your-paper-link)

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
