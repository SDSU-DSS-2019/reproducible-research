---
title       : Reproducible Research
subtitle    : What is it and How can we do it?
author      : Adam J Sullivan 
job         : Assistant Professor of Biostatistics
work        : Brown University
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js # {highlight.js, prettify, highlight}
hitheme     :  github     # 
widgets     : [mathjax, quiz, bootstrap, interactive] # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3, libraries/leaflet, libraries/dygraphs]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : publichealthlogo.png
biglogo     : publichealthlogo.png
assets      : {assets: ../../assets}
--- .segue bg:grey





# About Me

--- &twocol

*** =left

## Current Position

- Adam J Sullivan
- Assistant Professor of Biostatistics (2015-Present)
- Director of Masters Programs in Biostatistics
- Faculty Statistician for the Hassenfeld Child Health Innovation Institute

*** =right


<center>
<img src="./assets/img/brown-logo.png" style="height:400px">
</center>

--- &twocol

## Education



*** =left

- BA in Mathematics and Adolscent Education
- 2003
- Houghton College

*** =right


<center>
<img src="./assets/img/houghton-logo.jpg" style="height:400px">
</center>


--- &twocol

## Education



*** =left

- MS in Mathematics with Specialization in Statistics
- 2010
- South Dakota State University

*** =right


<center>
<img src="./assets/img/sdsu-logo.jpg" style="height:400px">
</center>


--- &twocol

## Education



*** =left

- Ph.D in Biostatistics
- 2015
- Harvard University

*** =right


<center>
<img src="./assets/img/hsph-logo.png" style="height:400px">
</center>

--- .segue bg:grey

# Questions

--- .class #id

## Questions

- For Questions during the talk
- Please go to: [www.slido.com](www.slido.com)
- Enter code: #D162
- Ask Questions and upvote ones already asked. 


--- .segue bg:grey

# Reproducible Research: What is it?

--- .class #id

## Reproducible Research: What is it?

- [Jon Claerbout](http://sepwww.stanford.edu/doku.php?id=sep:research:reproducible:seg92) says

> An article about computational results is advertising, not scholarship. The actual scholarship is the full software environment, code and data, that produced the result.

--- .class #id

## Reproducible Research: What is it?

- [Victoria Stodden](https://www.edge.org/response-detail/25340) separated this out to:
    - Computational reproducibility: ability to reproduce code, computing environment and implementation
    - Empirical reproducibility: Ability to reproduce a non-computational scientific study, need to know process and how data was collected. 
    - Statistical reproducibility: Detailed information on analysis and choice of tests.
  



--- .class #id

## Does this really matter?

- Many articles have been written on this subject and continue to be written. 
- This suggests importance but do we care?

--- .class #id

## Personal Example

- Summer of 2011, first real data analysis performed by me. 
- The analysis was performed in R and was then written into 3 different publications over the course of the next 2 years. 
- When publications came back for revisions it was at least 1 year from time of analysis. 

--- &twocol

## Reproducing my own Work


*** =left

- All data was saved in original files. 
- All code was separated out for papers.
- Absolutely zero comments were made in this code. 
- 1 year later my R had dramatically changed. 

*** =right

<center>
<img src="./assets/img/facepalm.jpg" style="height:200px">
</center>


--- .class #id

## What happened?

- I could not replicate my original tables. 
- I could not follow the code I had written (Think of reading beginners writing)
- I had to redo all of the analysis and remember:
    - What was my inclusion criteria?
    - What was my exclusion criteria?
    - Why did I ever leave comments out????
    


--- .class #id

## What issues can come about?

- How was the data cleaned?
- What definitions were used? 
     - Age has many calculations which can be used. 
     - Was there any rounding or truncating before work was used?


--- .class #id

## Definitions Further Explored

- Example: Medical Data with kids
    - Many times considering ages 1 to 18. 
- Were events included for kids who entered the study at 17 but later vists were at 18? 
- Was there rounding that included 6-11 month olds? 
- How can you replicate even a simple sample size without knowing these things?


--- .segue bg:grey

# Is there any hope?

--- .class #id

## Is there any hope?

- Modern tools are making at least 2 areas of reproducibility very easy:
    - Computational
    - Statistical
- Many of these tools are free and already widely shared. 

--- .class #id

## What are these tools?

- We will explore some of these tools:
    - RStudio Tools
    - RCloud Social
    - Github
  

--- .segue bg:grey

# RStudio Tools

--- .class #id

## RMarkdown

- Takes Markdown and combines it with the ability to run R code as well as:
  - Python
  - C++
  - Julia
  - SQL
  - etc.
- Can turn these into html, pdf and word documents.
- Simple to learn and very powerful. 

--- .class #id

## Further RMarkdown

- You can now generate:
  - Dashboards
  - Textbooks
  - Presentations (like this one)
  - Widgets
  - etc.

--- .class #id

## R Projects

- SAS and R Files used to start out similar :
    - `LIBNAME libref ACCESS PATH='C:\PCFData\Demo.accdb'; `
    - `setwd('C:\PCFData\Demo.accdb')`
- Why does this matter?

--- .class #id

## Setting Directories

- Anytime you move folders your code won't work. 
- No other computer other than yours can run this. 
- Every person using your work must change these statements. 
- In R this further is problem when using this syntax throughout the code to use new data. 

--- &twocol

## R Projects

*** =left
- RStudio's Projects fix this for R
- Once a project is opened the working directory is set to the project base folder. 
- Anyone can open this project and have the file system in place. 
- If you move the folder the working directory changes automatically. 

*** =right


<center>
<img src="./assets/img/rproject.jpg" style="height:200px">
</center>

--- .class #id

## RStudio Server Strengths


<center>
<img src="./assets/img/rstudio-server.PNG" style="height:500px">
</center>




--- .class #id

## RStudio Server

- RStudio platform on a server.
- Both Free and Pro versions.
- Interface looks the same as desktop version. 

--- .class #id

## RStudio Server Strengths

- Single Management of Software can minimize bugs
- Do not need a powerful individual computer. 
- Can actually use Chromebooks. 
- Easily interface through web browswer. 


--- .class #id

## RStudio Server Strengths

- With Pro Version
    - SSL Encryption
    - Custom user load limits
    - Work on shared projects in real time (like google docs)

--- .class #id

## RStudio Server Strengths


<center>
<img src="./assets/img/rstudio-dash.PNG" style="height:500px">
</center>



--- .class #id

## RStudio Server Weaknesses

- Need to be connected to internet or network. 
- Need to have individuals that can host a server and manage it. 
- R and Linux can be a pain for many packages.
- Cost - $10k for pro per year (Still Cheaper than SAS)

--- .class #id

## RCloud Social


<center>
<img src="./assets/img/rcloud-social.PNG" style="height:500px">
</center>


--- .class #id




## RStudio Cloud

- RStudio server hosted by RStudio 
- Still very new 
- Can be slow
- Good to share work or onboard students. 

--- .class #id

## RCloud Social

- Social Environment used for code and data visualizations
- Open Source - all on github
- Can use R or Python
- Dashboards, markdown documents, html widgets, ...
- Written and used extensively by ATT (Bell Labs)


--- .class #id

## RCloud Social

- Can be run on desktop or server
- Easily works with Spark 
- Public and Private Instances allowed.
- Directly connected to github

--- .class ##id

## RCloud Strengths

- Completely Free
- ATT is constanly updating along with others
- Active User Community
- Versioning/Forking
- Reporting Dashboard

--- .class #id

## RCloud Weaknesses

- Only open source support
- Need to be more proficient in R:
    - Not as easy to load date.
    - Not as easy to install packages. 
    - Not as easy to 


--- .class #id

## Github


<center>
<img src="./assets/img/github.PNG" style="height:500px">
</center>

--- .class #id

## Github

- Uses `git` language to version control
- Save you from bad workflow:
      - `my-thesis.doc`
      - `my-thesis-v1.doc`
      - `my-thesis-v1-comments-sullivan.doc`
      - `my-thesis-v1-this-is-so-bad.doc`


--- .class #id

## Github: Pros

- Easy to use tools for all systems
- Directly connects to RStudio and RCloud Social
- Used by many computer programmers, statisticians, data scientists, analysts, ...
- Excellent community and professional support


--- .class #id

## Github Cons

- Difficult Onboarding
- Github Classroom needs a lot of work. 
- `git` can be a pain. 
- Have to pay for private files


--- .class #id


## Questions





<center>
<img src="./assets/img/sadie.jpg" style="height:500px">
</center>







