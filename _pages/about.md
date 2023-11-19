---
permalink: /
title: "👋Hello there, I'm Qihan!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am  a recent [Peking University](https://english.pku.edu.cn/) graduate, and currently a research assistant at [Aalto University](https://www.aalto.fi/en), Department of Computer Science. My research interests lie at the intersection of Natural Language Processing, Machine Learning, and Data Mining with mental health, behavioral, and societal applications. 

The ubiquity of the internet has enabled the collection of vast datasets that encapsulate the complexities of human behavior and society. My primary research objective is to develop tools to uncover and understand these intricate dynamics by analyzing large-scale, unstructured data. This interdisciplinary endeavor draws from my academic background in psychology from Peking University, coupled with a strong foundation in computer science acquired through coursework and 4 independent research projects. 



# Research Experience
## Towards Understanding Depression through Music Preferences 🎵
The prevalence of Mental Health disorders has been an escalating concern worldwide. I embarked on my journey in data science for mental health with a particular focus on music. I aimed to quantify and compare music preferences between individuals with and without depression, a task challenging to address through traditional laboratory experiments.

To accomplish this, I developed a methodology that examined music from musical, lyrical, and network perspectives. First, I scraped songs’ musical features such as danceability and acousticness through the Spotify API and conducted statistical analysis for them. Second, leveraging Latent Dirichlet Allocation (LDA) and Linguistic Inquiry and Word Count (LIWC), I compared the topic and language use of lyric differences between music favored by individuals diagnosed with and without depression. To understand this question above individual levels, I also conducted a Network Analysis applying community detection algorithms to examine the network relationships of these two groups. My result reveals a possible echo-chamber effect, where the musical choices of depressed individuals may inadvertently reinforce depressive moods. 

This work under the guidance of [Prof. Huan Liu](https://www.public.asu.edu/~huanliu/) from Arizona State University, has been submitted to WWW’24 with me as the first author. 

## Analyzing Users’ Evaluation about Mental Health Apps at Scale 📱
During the past few years, the COVID-19 pandemic also triggered a dramatic increase in the prevalence of mental illness. Nearly 20% of adults are experiencing a mental illness in 2022. While the needs for treatment and intervention of mental health are high, the available resources for mental health are insufficient and inadequate all over the world: the traditional mental health costs are high and need long wait times. Against this backdrop, digital mental health tools present an accessible and affordable solution to address the current treatment gap. Mental health Apps have increasingly become useful tools for individuals seeking help for various mental health issues, including depression, anxiety, and eating disorders.

However, mental health apps, as a new category in the app market, lack solid user experience research, and usability evaluation. To address this gap, I developed a methodology to analyze user reviews of over 500 mental health apps from Google Play and App Store. Through machine learning techniques, including BERT-based classification, clustering, and topic modeling, I identified user concerns and perspectives, enhancing mental health app usability and effectiveness. This research has the potential to significantly contribute to improving mental health treatment.

This work is adviced by [Prof. Talayeh Aledavood](https://talayeh.xyz/) at Aalto University

## BERT-Based Multi-task Approach for Violence Detection 💣
Hate speech can lead to real-world harm, including violence, discrimination, and social division. Understanding its dynamics helps in creating safer online spaces, preventing offline harm, and enhancing platform accountability. In this context, my work, advised by [Prof. Keith Burghardt](https://www.kburg.co/) and [Prof. Kristina Lerman](https://www.isi.edu/people-lerman/) at USC, focuses on the developing violence detection tools and understanding the radicalization of violence. My work involved fine-tuning deep learning-based NLP models, such as BERT and Roberta, for violence detection. I also developed a novel multi-task architecture to address label disagreements between annotators and a multi-label classification approach for hate-speech-related labels. These innovations resulted in a state-of-the-art violence classifier and a hate-speech-related multi-label classifier, outperforming 20% than previous research using SVM and LSTM. My research has practical implications for creating safer online spaces and enhancing platform accountability, and it is currently being prepared for submission to NAACL'24, with me as the first author.

## Exploring the Relationship between Emotion and Audience Engagement 👍

In a collaborative project supervised by [Prof. Gary Hsieh](https://faculty.washington.edu/garyhs/#research) at University of Washington, I explored the social engagement dynamics related to emotion sharing on social media platforms. We uncovered intriguing patterns through data scraping and statistical analysis, such as positive posts receiving more likes and negative posts generating more replies. A survey complemented these findings, shedding light on the underlying reasons for these trends. This project marked my first foray into extensive literature review and academic writing and has been submitted to CSCW 2024, with me as the first author.






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
