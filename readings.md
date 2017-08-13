---
layout: page
title: Readings
permalink: /readings/
---

Course readings are provided below. We do not expect you to read entries marked as "inspiration". They are provided in case you have spare time and want to dig deeper into the topics. Note that access to some readings require you to be on the UoC domain.

Our main text is [Big Data and Social Science: A Practical Guide to Methods and Tools](http://www.bigdatasocialscience.com/home) (henceforth, BDSS) edited by Ian Foster, Rayid Ghani, Ron S. Jarmin, Frauke Kreuter, and Julia Lane.

Some students may have noticed that in the previous installments we used R for data science, however, we have now opted for Python. Two of the main reasons are that Python has more simple syntax with more flexibility applications, making it easier to learn and better to structure data. In addition Python has a more extensive support for machine learning models as well as Big Data applications. See a thorough discussion of advantages between the two programs here:

- [Python vs. R](https://www.quora.com/Which-is-better-for-data-analysis-R-or-Python)

If you are already familiar with R and prefer to work with R in the exercises you may look Kosuke Imai's book on Quantitative Social Science and looking up last year's references [here](http://sebastianbarfort.github.io/sds_summer/). Note that we do not offer any support in terms of coding and supervising in R.

### August 7
*Keywords:* Introduction to Social Data Science, Introduction to Python.

**Required - Introduction to Big Data and Social Data Science**
- Grimmer, Justin. ["We are all social scientists now: how big data, machine learning, and causal inference work together."](https://web.stanford.edu/~jgrimmer/bd_2.pdf) *PS: Political Science & Politics* 48.1 (2015): 80-83.

- Lazer, David and Jason Radford. 2017. ["Data ex Machina. Introduction to Big Data."]( http://www.annualreviews.org/doi/abs/10.1146/annurev-soc-060116-053457) *Annual Review of Sociology* vol 43, August.

- Einav and Levin: Economics in the Age of Big Data. *Science*. 2013. [Link](http://www.sciencemag.org/content/346/6210/1243089.full.pdf?keytype=ref&siteid=sci&ijkey=Jj7wCy7hhth4M).

- Athey, Susan. 2017. ["Beyond prediction: Using big data for policy problems"](http://science.sciencemag.org/content/355/6324/4832017). *Science*

**Required - Python programming**

- [Preparing for Social Data Science](https://abjer.github.io/sds/posts/2017/07/07/preparing-for-sds.html)

- [The Scientist: Get With the Program](http://www.the-scientist.com/?articles.view/articleNo/43632/title/Get-With-the-Program/)

- Michael Dawson, 2010. *Python Programming for the Absolute Beginner, 3rd Edition*. Read pages 7-44, 53-63 (copies will be provided).

**Inspiration**

If you’re interested, and want to delve deeper into coding and programming (you certainly don’t have to, they are not required for this course), we highly recommend the following posts

- [Why learn Python](https://www.continuum.io/why-python)
- [What is Code?](http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/?cmpid=twtr1)
- Forter et al. Kosuke. 2016. *A First Course in Quantitative Social Science*. Read introduction in chapter 1.

**Background**
- Anderson, Chris. 2008. "[The end of theory: The data deluge makes the scientific method obsolete](http://www.uvm.edu/~cmplxsys/wordpress/wp-content/uploads/reading-group/pdfs/2008/anderson2008.pdf)." *Wired*, 16-07.


### August 8 & 9
*Keywords:* Visualization, Data Manipulation, Data Import, Functions.

**Visualizations**

We are using two modules for plotting - [pandas](http://pandas.pydata.org/pandas-docs/stable/) and [seaborn](https://seaborn.pydata.org/index.html). Both these modules are built on the fundamental and flexible plotting module [matplotlib](https://matplotlib.org). Matplotlib will not be covered in this course but if you are interested in how to customize your pandas or seaborn plots read this read [this excellent blog post](http://pbpython.com/effective-matplotlib.html).

Required material
- BDSS Sections 9.1, 9.2, 9.3.2 for a high level introduction.
- Simple plots with [pandas visualizations](https://pandas.pydata.org/pandas-docs/stable/visualization.html) - only read sections on ['Basic Plotting'](https://pandas.pydata.org/pandas-docs/stable/visualization.html#basic-plotting-plot) and ['Other Plots'](https://pandas.pydata.org/pandas-docs/stable/visualization.html#other-plots).
- For stylish [seaborn plots](https://seaborn.pydata.org/index.html) read tutorial on [plotting distrutions](https://seaborn.pydata.org/tutorial/distributions.html#distribution-tutorial) and [categorical data](https://seaborn.pydata.org/tutorial/categorical.html#categorical-tutorial).


If you want to review some of the material on visualizations in class you can check out these videos on visualizations in  [Pandas](https://www.coursera.org/learn/python-plotting/lecture/e7o5K/plotting-with-pandas) and [Seaborn](https://www.coursera.org/learn/python-plotting/lecture/FnAul/seaborn).

Browse the following

- Schwabish, Jonathan A. 2014. "[An Economist's Guide to Visualizing Data](https://www.aeaweb.org/articles.php?doi=10.1257/jep.28.1.209)". *Journal of Economic Perspectives*, 28(1): 209-34.

- Healy, Kieran and James Moody. 2014. "[Data Visualization in Sociology](http://kieranhealy.org/files/papers/data-visualization.pdf)". *Annual Review of Sociology*, 40:105–128.


**Data structuring**

Required material
- Rada, Greg. 2013. "[Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)"- read all three sections.

**Inspiration**

Below are links to some interesting videos describing how companies such as the New York Times or FiveThirtyEight think about visualizing data as well as some posts and videos on the underlying theory behind the "tidyverse" and an introduction to working with spatial data in R.

- [Fivethirtyeight: How We Charted Trump’s Fall From Grace In Hip-Hop](https://fivethirtyeight.com/features/how-we-charted-trumps-fall-from-grace-in-hip-hop/)

- Wickham, Hadley. 2010. "[A Layered Grammar of Graphics](http://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf)". *Journal of Computational and Graphical Statistics*, Volume 19, Number 1, Pages 3–28.

- Wickham, Hadley. 2011. “[The Split-Apply-Combine Strategy for Data Analysis](http://www.jstatsoft.org/article/view/v040i01)”. Journal of Statistical Software 40(1).

- For spatial data we recommend [GeoPandas](https://github.com/geopandas/geopandas) which provides an overlay of Pandas for spatial visualizations and analysis - see tutorials for [making visualizations](https://geohackweek.github.io/vector/04-geopandas-intro/) or [computing features](https://automating-gis-processes.github.io/2016/Lesson2-geopandas-basics.html).

- For network data we recommend using [NetworkX](https://networkx.github.io/) - see BDSS Chapter 8 for an introduction to networks and a tutorial for NetworkX [here](https://networkx.github.io/documentation/networkx-1.10/tutorial/index.html).


### August 10
*Keywords:* Web Scraping, API.
This module is very much about hands-on experience with scraping, storing and cleaning unstructured data.

**Required**

- BDSS, 2016. chapter 2: Working with Web Data and APIs.

- Introduction to pattern matching using regex: "[An introduction to regex in python](https://scotch.io/tutorials/an-introduction-to-regex-in-python). Blog.

- Shiab, Nael. 2015. "[On the Ethics of Web Scraping and Data Journalism](http://gijn.org/2015/08/12/on-the-ethics-of-web-scraping-and-data-journalism/)". Global Investigative Journalism Network.

**Inspiration**

Below are some interesting academic papers using data scraped from online sources that might provide inspiration for your exam project.

- Stephens-Davidowitz, Seth. 2014. "[The cost of racial animus on a black candidate: Evidence using Google search data](http://www.sciencedirect.com/science/article/pii/S0047272714000929)." *Journal of Public Economics*, 118: 26-40.

- Stephens-Davidowitz, Seth, Hal Varian, and Michael D. Smith. 2016. "[Super Returns to Super Bowl Ads?](http://people.ischool.berkeley.edu/~hal/Papers/2015/super.pdf)". R & R, *Journal of Political Economy*.

- Stephens-Davidowitz, Seth, and Hal Varian. 2015 "[A Hands-on Guide to Google Data](https://www.aeaweb.org/aea/2016conference/program/retrieve.php?pdfid=772)." Google working paper.

- Barberá, Pablo. 2015. "[Birds of the same feather tweet together: Bayesian ideal point estimation using Twitter data](http://pan.oxfordjournals.org/content/23/1/76.short)." *Political Analysis*, 23.1: 76-91.

- Cavallo, Alberto. "[Scraped data and sticky prices](http://www.aeaweb.org/aea/2011conference/program/retrieve.php?pdfid=403)". No. w21490. National Bureau of Economic Research, 2015.

- Bond, Robert M., et al. 2012. "[A 61-million-person experiment in social influence and political mobilization](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3834737/)." *Nature*, 489.7415: 295-298.

### August 11

*Keywords:* What is Big Data, reproducible research.

*Description:* We will introduce the Jupyter notebook for publication of code and visualizing data insights. We will show how the notebook can be used to make interactive visualizations.

**Reproducible research - required**

*On markdown*
- Nolan, John. 2015. "[How to Write Faster, Better & Longer: The Ultimate Guide to Markdown](https://blog.ghost.org/markdown/)."

*On git*
- Jones, Zachery. 2015. "[Git & Github tutorial](http://zmjones.com/git-github-tutorial/)".
 - Note that an optional followup can be found in Rainey, Carlisle. 2015. "[Git for Political Science](https://github.com/carlislerainey/git-for-political-science)".

**Big data - required**

- John Gerring. 2012. Measurements. Chapter 7 in Social Science Methodology, 2. Ed., Cambridge University Press. ((*bad*) copies will be provided)

- Christine L. Borgman. Provocations, What Are Data and Data Scholarship in the Social Science. Chapters 1,2 and 6 in *Big Data, Little Data, No Data*. MIT Press 2015. (copies will be provided).

- Edelman, Benjamin. 2012. "[Using internet data for economic research](http://www.jstor.org/stable/41495310)." *The Journal of Economic Perspectives*, 26.2: 189-206.

- Jesse Singal. 2015. "[The Case of the Amazing Gay-Marriage Data: How a Graduate Student Reluctantly Uncovered a Huge Scientific Fraud](http://nymag.com/scienceofus/2015/05/how-a-grad-student-uncovered-a-huge-fraud.html)." New York Magazine.




**Background**

- Lazer, David, et al. 2014. "[The parable of Google Flu: traps in big data analysis](http://gking.harvard.edu/files/gking/files/0314policyforumff.pdf)." *Science*, 343.14.

### August 14

*Keywords*: Observational data, Causation.

- Imai, Kosuke. 2016. *A First Course in Quantitative Social Science*. Read chapter 2 and section 4.3.

- Samii, Cyrus. 2016. ["Causal Empiricism in Quantitative Research"](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2776850). *Journal of Politics* 78(3):941–955.

- Deaton, Angus, and Nancy Cartwright. 2016. [Understanding and Misunderstanding Randomized Controlled Trials](https://www.nber.org/papers/w22595.ack). No. w22595. National Bureau of Economic Research.

*Keywords*: Prediction, Statistical Learning

- BDSS, 2016. chapter 6.1-6.4 and subsection 6.5.2.

- Friedman, Jerome, Trevor Hastie, and Robert Tibshirani. 2001. "[Introduction to statistical learning](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Fourth%20Printing.pdf)". Vol. 1. Springer, Berlin: Springer series in statistics. (pages: 15-42, 175-184, 214-227)

- Kleinberg, Jon, et al. "[Prediction policy problems](http://www.cs.cornell.edu/home/kleinber/aer15-prediction.pdf)." *American Economic Review*, 105.5 (2015): 491-495.

- Varian. Hal. 2014. ["Big Data: New Tricks for Econometrics"](http://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.28.2.3). *Journal of Economic Perspectives*, 28.2: 3-27.

**Inspiration**

- Choi, Hyunyoung, and Hal Varian. "[Predicting initial claims for unemployment benefits](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.549.7927&rep=rep1&type=pdf)." Google working paper.

- Jonas, Zachery and Fridolin Linder. 2016. "[Exploratory Data Analysis using Random Forests](http://zmjones.com/static/papers/rfss_manuscript.pdf)".

- Anderson, Chris. 2008. "[The end of theory: The data deluge makes the scientific method obsolete](http://www.uvm.edu/~cmplxsys/wordpress/wp-content/uploads/reading-group/pdfs/2008/anderson2008.pdf)." *Wired*, 16-07.

- Ginsberg, Jeremy, et al. 2009. "[Detecting influenza epidemics using search engine query data](http://www.nature.com/nature/journal/v457/n7232/full/nature07634.html)." *Nature*, 457.7232: 1012-1014.

- Broniatowski, David Andre, Michael J. Paul, and Mark Dredze. 2014. "[Twitter: big data opportunities](http://cs.jhu.edu/~mpaul/files/science_letter_twitter.pdf)." *Inform*, 49: 255.

### August 15

*Keywords*: Text as Data.

**Required**
- Text analysis. BDSS Chapter 7.
- Grimmer, Justin, and Brandon M. Stewart. 2013. "[Text as data: The promise and pitfalls of automatic content analysis methods for political texts](https://pan.oxfordjournals.org/content/early/2013/01/21/pan.mps028.short)." *Political Analysis*, 21.3: 267-297.

**Inspiration**

- King, G., Pan, J., & Roberts, M. E. 2013. [How censorship in China allows government criticism but silences collective expression](http://gking.harvard.edu/files/censored.pdf). *American Political Science Review*, 107(02), 326-343.
-Andrea Ceron, Luigi Curini, Stefano M. Iacus. "[Using Sentiment Analysis to Monitor Electoral Campaigns: Method Matters—Evidence From the United States and Italy](http://journals.sagepub.com/doi/abs/10.1177/0894439314521983)


### August 16

*Keywords*: Classification, unsupervised learning, feature engineering.
**Required**

*Learning from unlabeled data using unsupervised learning.*
- BDSS Chapter 6.5.1 about unsupervised learning.

*Automated machine learning.*
- Randal S. Olson, Nathan Bartley, Ryan J. Urbanowicz, Jason H. Moore (2016). [Evaluation of a Tree-based Pipeline Optimization Tool for Automating Data Science](https://arxiv.org/abs/1603.06212)

**Unsupervised learning in natural language processing**
- Word Embeddings. Baroni et al. (2014). "[Don't count, predict! A systematic comparison of context-counting vs. context-predicting semantic vectors.](http://clic.cimec.unitn.it/marco/publications/acl2014/baroni-etal-countpredict-acl2014.pdf)"

**Background: wordembeddings and transfer learning**
- Word2Vec. Mikolov et al. (2013). "[Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf)"
- Glove: "[Global Vectors for Word Representation.](https://nlp.stanford.edu/pubs/glove.pdf)"
*Transfer Learning*:
- Learning to understand sentiment from unlabeled data. "[Unsupervised Sentiment Neuron](https://blog.openai.com/unsupervised-sentiment-neuron/)"
- "[Using millions of emoji occurrences to learn any-domain representations for detecting sentiment, emotion and sarcasm]"](https://arxiv.org/abs/1708.00524) 


## August 17



*Keywords:* Privacy and ethics.

**Required**

- Alessandro Acquisti et al. 2015. "[Privacy and human behavior in the age of information](http://science.sciencemag.org/content/347/6221/509.full.pdf+html)." Science 347, 509.

- Heffetz, Ori, and Katrina Ligett. 2014. "[Privacy and Data-Based Research](http://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.28.2.75)." *The Journal of Economic Perspectives*, 28.2: 75-98.

- Mittelstadt et al. 2016. ["The ethics of algorithms: Mapping the debate."](http://www.academia.edu/download/51111739/Mittelstadt_et_al_2016_-_The_Ethics_of_Algorithms.pdf) *Big Data & Society* July-December, 1-21.

- Shiab, Nael. 2015. "[Web Scraping: A Journalist’s Guide](http://gijn.org/2015/08/11/web-scraping-a-journalists-guide/)". Global Investigative Journalism Network.

**Background**

- Alessandro Acquisti. 2015. The Economics and Behavioral Economics of Privacy. Chapter 3 in *Privacy, Big Data, and the Public Good: Frameworks for Engagement* (eds. Julia Lane, Victoria Stodden, Stefan Bender, Helen Nissenbaum). Cambridge University Press.

- Fabian Neuhaus & Timothy Webmoor. 2012. "[AGILE ETHICS FOR MASSIFIED RESEARCH AND VISUALIZATION](http://www.tandfonline.com/doi/abs/10.1080/1369118X.2011.616519)." Information, Communication & Society 15:1, 43-65
