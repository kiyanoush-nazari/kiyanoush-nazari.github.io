---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a researcher and software engineer in the field of robotics. My primary expertise lies in robotic manipulation and developing data-driven solutions for real-world robotic challanges. I worked on plenty of robotic projects where I utilised AI models for intelligent robot planning and control using visual, tactile, and propioception feedback. 

I started working with robots in my M.Sc. in Mechatronics Engieering at a [surgical robotic research center](https://sinamed.ir/products/sina-flex-telesurgery) developing tele-operation controllers. I continued my journey by doing my PhD at [Intelligent Manipulation Lab](https://intmanlab.com/index.html) by conducting ground-braking research in tactile-based slip controllers in roboitc manipulation tasks. I am currently a postdoctoral research associate at [Lincoln Institute for Agri-Food Technology](https://www.lincoln.ac.uk/liat/) working on autonomous navigation and 3D modelling of different types of crops. You can find demonstrations of my robotic projects bellow.

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
      <li><img src="/images/graduation.png" alt="Hat icon"> MSc in Mechatronics Eng., 2014-2017 <br> Sharif University of Technology</li>
      <li><img src="/images/graduation.png" alt="Hat icon"> BSc in Mechanical Eng., 2010-2014 <br> Amirkabir University of Technology</li>
    </ul>
  </div>
</div>
<br><br>

Robotic Projects
======
### Bio-inspired Trajectory Modulation for Slip Control in Robot Manipulation Tasks
<span style="font-size: 0.8em;">*Nazari et al. Nature Machine Intelligence (2024)*</span>

In robotic pick-and-place tasks, preventing object slippage is critical. While grip force control is the traditional method, our research highlights trajectory modulation as a superior alternative in certain scenarios, especially when combined with predictive models. This approach offers a promising solution for enhancing robotic manipulation and slip control.


<div style="text-align: center; margin-bottom: 30px;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/_v7zXF9FROo?si=hR4pP20js0BSIlxm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>


<div style="display: flex; gap: 10px; align-items:center; margin-left: 5%; margin-bottom: 40px;">
  
  <!-- Paper Button with ArXiv Symbol -->
  <a href="https://example.com/your-paper-link" target="_blank" style="text-decoration: none;">
    <button style="display: inline-flex; align-items: center; background-color: #f5f5f5; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- ArXiv Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="black" viewBox="0 0 100 100" width="20" height="20" style="margin-right: 8px;">
        <circle cx="50" cy="50" r="50" fill="gray"></circle>
        <text x="50%" y="55%" font-size="40" fill="white" text-anchor="middle" alignment-baseline="middle">arX</text>
      </svg>
      Download Paper
    </button>
  </a>
  
  <!-- GitHub Button -->
  <a href="https://github.com/your-github-repo" target="_blank" style="text-decoration: none; margin-left: 20px;">
    <button style="display: inline-flex; align-items: center; background-color: #333; color: white; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- GitHub Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="white" viewBox="0 0 24 24" width="20" height="20" style="margin-right: 8px;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.726-4.042-1.416-4.042-1.416-.546-1.387-1.332-1.758-1.332-1.758-1.09-.744.083-.729.083-.729 1.205.084 1.84 1.237 1.84 1.237 1.07 1.835 2.809 1.305 3.495.998.108-.775.418-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.47-2.38 1.236-3.22-.124-.303-.536-1.523.117-3.176 0 0 1.008-.322 3.301 1.23a11.513 11.513 0 0 1 3.004-.404c1.02.005 2.044.138 3.002.404 2.292-1.553 3.297-1.23 3.297-1.23.655 1.653.243 2.873.12 3.176.77.84 1.234 1.91 1.234 3.22 0 4.61-2.803 5.625-5.475 5.92.43.372.812 1.103.812 2.222 0 1.606-.014 2.896-.014 3.287 0 .322.217.694.825.576C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
      Code on GitHub
    </button>
  </a>

</div>

____________________________________________________________________________
### Deep Functional Predictive Control (deep-FPC): Robot Pushing 3-D Cluster using Tactile Prediction
<span style="font-size: 0.8em;">*Nazari et al. IROS (2023)*</span>

This project proposes a data-driven controller using tactile predictions and Functional Predictive Control (d-FPC) to manage Physical Robot Interaction (PRI) in complex pushing tasks. Tested on a robot pushing a strawberry stem, the d-FPC successfully controls 3D object movement, offering a promising solution for PRI in robotic manipulation.


<div style="text-align: center; margin-bottom: 30px;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/T_El6SxuDgo?si=SoqjT6paUd1xaNnk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>


<div style="display: flex; gap: 10px; align-items:center; margin-left: 5%;margin-bottom: 40px;">
  
  <!-- Paper Button with ArXiv Symbol -->
  <a href="https://example.com/your-paper-link" target="_blank" style="text-decoration: none;">
    <button style="display: inline-flex; align-items: center; background-color: #f5f5f5; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- ArXiv Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="black" viewBox="0 0 100 100" width="20" height="20" style="margin-right: 8px;">
        <circle cx="50" cy="50" r="50" fill="gray"></circle>
        <text x="50%" y="55%" font-size="40" fill="white" text-anchor="middle" alignment-baseline="middle">arX</text>
      </svg>
      Download Paper
    </button>
  </a>
  
  <!-- GitHub Button -->
  <a href="https://github.com/your-github-repo" target="_blank" style="text-decoration: none; margin-left: 20px;">
    <button style="display: inline-flex; align-items: center; background-color: #333; color: white; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- GitHub Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="white" viewBox="0 0 24 24" width="20" height="20" style="margin-right: 8px;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.726-4.042-1.416-4.042-1.416-.546-1.387-1.332-1.758-1.332-1.758-1.09-.744.083-.729.083-.729 1.205.084 1.84 1.237 1.84 1.237 1.07 1.835 2.809 1.305 3.495.998.108-.775.418-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.47-2.38 1.236-3.22-.124-.303-.536-1.523.117-3.176 0 0 1.008-.322 3.301 1.23a11.513 11.513 0 0 1 3.004-.404c1.02.005 2.044.138 3.002.404 2.292-1.553 3.297-1.23 3.297-1.23.655 1.653.243 2.873.12 3.176.77.84 1.234 1.91 1.234 3.22 0 4.61-2.803 5.625-5.475 5.92.43.372.812 1.103.812 2.222 0 1.606-.014 2.896-.014 3.287 0 .322.217.694.825.576C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
      Code on GitHub
    </button>
  </a>

</div>
____________________________________________________________________________

### Proactive slip control by learned slip model and trajectory adaptation
<span style="font-size: 0.8em;">*Nazari et al. CoRL (2022)*</span>

This paper introduces a novel slip control method for robotic manipulation. Traditional approaches rely on increasing grip force, which may not be feasible or could damage delicate objects. Instead, we propose a data-driven predictive controller that uses an action-conditioned slip predictor and a constrained optimizer to avoid slip during movements. Tested in real robot experiments, the method effectively controls slip, even for objects not encountered during training.


<div style="text-align: center; margin-bottom: 30px;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/DI9BkrVWnCI?si=Bnb49cP8Teyi3XSq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>


<div style="display: flex; gap: 10px; align-items:center; margin-left: 5%;margin-bottom: 40px;">
  
  <!-- Paper Button with ArXiv Symbol -->
  <a href="https://example.com/your-paper-link" target="_blank" style="text-decoration: none;">
    <button style="display: inline-flex; align-items: center; background-color: #f5f5f5; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- ArXiv Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="black" viewBox="0 0 100 100" width="20" height="20" style="margin-right: 8px;">
        <circle cx="50" cy="50" r="50" fill="gray"></circle>
        <text x="50%" y="55%" font-size="40" fill="white" text-anchor="middle" alignment-baseline="middle">arX</text>
      </svg>
      Download Paper
    </button>
  </a>
  
  <!-- GitHub Button -->
  <a href="https://github.com/your-github-repo" target="_blank" style="text-decoration: none; margin-left: 20px;">
    <button style="display: inline-flex; align-items: center; background-color: #333; color: white; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- GitHub Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="white" viewBox="0 0 24 24" width="20" height="20" style="margin-right: 8px;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.726-4.042-1.416-4.042-1.416-.546-1.387-1.332-1.758-1.332-1.758-1.09-.744.083-.729.083-.729 1.205.084 1.84 1.237 1.84 1.237 1.07 1.835 2.809 1.305 3.495.998.108-.775.418-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.47-2.38 1.236-3.22-.124-.303-.536-1.523.117-3.176 0 0 1.008-.322 3.301 1.23a11.513 11.513 0 0 1 3.004-.404c1.02.005 2.044.138 3.002.404 2.292-1.553 3.297-1.23 3.297-1.23.655 1.653.243 2.873.12 3.176.77.84 1.234 1.91 1.234 3.22 0 4.61-2.803 5.625-5.475 5.92.43.372.812 1.103.812 2.222 0 1.606-.014 2.896-.014 3.287 0 .322.217.694.825.576C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
      Code on GitHub
    </button>
  </a>

</div>
____________________________________________________________________________

### Autonomous Black Grass Detection and Removal in Wheat Fields using Unmanned Ground Vehicle
<span style="font-size: 0.8em;">*Nazari et al. JFR (2025)*</span>

A fully autonomous unmanned ground vehicle (UGV) equipped with GPS-based navigation is designed for efficient black grass removal in wheat fields. The system utilizes an RGB camera to detect black grass and identify crop rows, enabling precise targeting. A mechanical tool, with an adjustable horizontal degree of freedom, ensures that only weeds are removed while avoiding crop damage. Upon detecting black grass, the tool descends to remove it and retracts after covering a 5-meter distance. A safety feature, based on LiDAR data, halts the mission if a human presence is detected, resuming operations once the area is clear.

<div style="text-align: center; margin-bottom: 30px;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/FZkYsnHp6JM?si=Nj0HzMcypshDSfKi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>


<div style="display: flex; gap: 10px; align-items:center; margin-left: 5%;margin-bottom: 40px;">
  
  <!-- Paper Button with ArXiv Symbol -->
  <a href="https://example.com/your-paper-link" target="_blank" style="text-decoration: none;">
    <button style="display: inline-flex; align-items: center; background-color: #f5f5f5; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- ArXiv Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="black" viewBox="0 0 100 100" width="20" height="20" style="margin-right: 8px;">
        <circle cx="50" cy="50" r="50" fill="gray"></circle>
        <text x="50%" y="55%" font-size="40" fill="white" text-anchor="middle" alignment-baseline="middle">arX</text>
      </svg>
      Download Paper
    </button>
  </a>
  
  <!-- GitHub Button -->
  <a href="https://github.com/your-github-repo" target="_blank" style="text-decoration: none; margin-left: 20px;">
    <button style="display: inline-flex; align-items: center; background-color: #333; color: white; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; font-size: 16px;">
      <!-- GitHub Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="white" viewBox="0 0 24 24" width="20" height="20" style="margin-right: 8px;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.726-4.042-1.416-4.042-1.416-.546-1.387-1.332-1.758-1.332-1.758-1.09-.744.083-.729.083-.729 1.205.084 1.84 1.237 1.84 1.237 1.07 1.835 2.809 1.305 3.495.998.108-.775.418-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.47-2.38 1.236-3.22-.124-.303-.536-1.523.117-3.176 0 0 1.008-.322 3.301 1.23a11.513 11.513 0 0 1 3.004-.404c1.02.005 2.044.138 3.002.404 2.292-1.553 3.297-1.23 3.297-1.23.655 1.653.243 2.873.12 3.176.77.84 1.234 1.91 1.234 3.22 0 4.61-2.803 5.625-5.475 5.92.43.372.812 1.103.812 2.222 0 1.606-.014 2.896-.014 3.287 0 .322.217.694.825.576C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
      Code on GitHub
    </button>
  </a>

</div>
________________________________________________________________________

Talks
=============

  - **2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**  
    A talk on deep functional predictive conrtol for flexible objects manipulation.
    <div style="text-align: center; margin-top: 30px; margin-bottom: 30px;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ghHnzUmhVGs?si=hMbYihAPZs2q6NzS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

  - **6th Annual Conference on Robot Learning (CoRL) 2022**  
    A talk on proactive slip control using robot trajectory adaptation.

  - **2021 Towards Autonomous Robotic Systems Conference (TAROS)**  
    A talk on multi-modal deep predictive models for tactile state estimation.

<!-- A data-driven personal website
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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
