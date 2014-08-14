# Data Science Curriculum

-Note: This is still under construction. - 

### Preliminaries: 

I’ve included freely available online sources where possible. If I’ve included a book that must be purchased, rest assured that it’s worth it. 

Additionally, I found the two following sources very helpful when I was creating my own Data Science Curriculum.

Claudia Gold's http://www.mysliderule.com/learning-paths/data-analysis/learn/ and Clare Corthell's Open Source Data Science Masters at https://github.com/datasciencemasters

### The Curriculum

#### I. Computer Science and Programming

a. General programming knowledge
- 6.01: Introduction to Electrical Engineering and Computer Science (MIT) 

b. Databases
- Stanford’s Introduction to Databases

c. Python
- If you've never programmed with Python before, start out with Code Academy's Python tutorial. http://www.codecademy.com/en/tracks/python
- Learn Python the Hard Way - http://bit.ly/ebook-learnpyhardway
- Google's Python class - http://bit.ly/T4j40A
- At this point, you should have a strong enough Python background to start working through Harvard's Stat 110. The lectures will take you through the the material in the next few bullet points, but you may want to start the class in parallel and watch the first few recitation videos, as they will provide some useful exercises that use Python's data analysis packages. 
- Install Python and its scientific packages (NumPy, SciPy, matplotlib, IPython, pandas). 
- I recommend installing Enthought Canopy or Anaconda, which are comprehensive scientific computing distributions of Python. These packages facilitate library installation and offer a useful programming environment. 
- Python for Data Analysis - http://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1449319793/ref=sr_1_1?ie=UTF8&qid=1403656221&sr=8-1&keywords=python+for+data+analysis - $25

d. R
- Install RStudio.
- You should be able to pick up a basic understanding of R from The Analytics Edge course. 
- ggplot cookbook. 

e. Other topics
- Udacity's Design of Computer Programs: A MOOC geared towards those with an intermediate programming level who want to fine-tune their programming design skills. The course has some great examples of clean and efficient code and an engaging lecturer.


#### II. Statistics and Math
a. A class on statistics, and a class on probability. I recommend a more basic book or MOOC (such as Spiegel's Schaum's Outline of Statistics), and then working your way through Wasserman's 'All of Statistics: A Concise Course in Statistical Inference' -- it covers the essentials of statistics and probability that you need and is tailored towards students that will later apply these concepts to statistics, data mining, and mchine learning. 

Harvard's Stat 110 - available on iTunes U. https://itunes.apple.com/us/course/statistics-110-probability/id502492375

c. Linear Algebra — any class should be fine.

d. Differential Equations. 

e. Single and Multi-variable Calculus. 


Schey’s Div, Grad, Curl, and All That’ offers a nice overview of the major topics in multivariate calculus. I’d recommend this book as a refresher for those who haven’t taken multivariate calculus in some time, or as a supplementary text for those working through a more rigorous primary text. 

I suggest that you use computational tools to work through math problems wherever possible. 'Think Stats: Probability and Statistics for Programmers' is a great companion text that goes through statistics problems while using python's scipy and numpy libraries to facilitate running statistical simulations. This iPython notebook goes over solving Differential Equations using Python: http://nbviewer.ipython.org/github/URXtech/techblog/blob/master/continuousTimeMarkovChain/markovChain.ipynb


#### III. Experimental Design and Data Analysis

A. Experimental Design
- Campbell and Stanley (1963): Experimental and Quasi-Experimental Designs for Research. don’t be turned off by the fact that this book was written over 50 years ago — the points that it makes are definitely still valid. It’s a small book, but quite concise, and accurately summarizes research design. You should be able to pick up a used copy for around $25.

- Though the Campbell and Stanley book covers all of the basic ideas you should be familiar with that are relevant to experimental design, you could benefit from taking a class on quantitative and qualitative research methods. These classes apply the concepts in the Campbell and Stanley book and go over scientific writing. I personally took MIT's Political Science labs (17.869 Political Science Scope and Methods (MIT)— qualitative research methods, writing, and experimental design and 17.871 Political Science Laboratory (MIT) — quantitative research methods), but any social science labs that cover quantitative and qualitative methods, while relying on computational statistical tools, should be fine. At this time, there don't seem to be many MOOC offerings in this subject area, so I don't have a particular recommendation, but if anyone has any suggestions for this section, please let me know.

B. Data Analysis

#### IV. Practical stuff
A. A/B testing:
http://www.wired.com/2012/04/ff_abtesting/

B. Data Visualization
- Check out Tableau -- a useful drag-and-drop style visualization tool. Here is a gallery of some of the things that are possible using Tableau. 
- ggplot 
- If you'd like to work with matplotlib and want to improve on its default settings (which you should, because the default settings are not that great), check out this notebook: http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_03_statistical_graphs.ipynb . It goes over some Python code to re-style the matplotlib's default settings by stripping out charg junk and the like. The notebook was created by  Harvard's CS 109 Data Science instructors. 

C. Writing

D. Nate Silver's book
- Nate Silver, who came to national prominence after his accurate predictions of the 2012 presidential elections, wrote a pop science book to go over the logic behind a number of modern-day predictive systems, as well as how he arrived at his own election predictions. http://www.amazon.com/The-Signal-Noise-Predictions-Chinese/dp/0143124005/ref=tmm_pap_title_0

E. Online reading material
- Stack Overflow, Cross Validated (http://stats.stackexchange.com/), Data Science Stack Exchange (http://datascience.stackexchange.com/). 
- Data Tau


F. Machine Learning
- Work through this Machine Learning tutorial. http://metacademy.org/roadmaps/cjrd/level-up-your-ml It will guide you through the following textbooks:
- Lantz's 'Machine Learning with R'
- Bishop's 'Pattern Recognition and Machine Learning'
- Koller et al.'s 'Probabilistic Graphical Models: Principles and Techniques. 


#### V. Additional Elective Work

A. Algorithms
- Udacity's algorithms course. 40 hours. 

B. Additional Machine Learning work 
- Hastie et al.'s 'The Elements of Statistical Learning' -- this is an excellent desktop reference. It goes over all of the most popular Statistical Learning/Machine Learning techniques, including the math behind major algorithms, and includes references to the most relevant publications for each technique. This book is of great value if you want to gain an in-depth understanding of Statistical Learning techniques, but could be frustrating if you were to use it as your first foray into the field. 
- Stanford's 'StatLearning Statistical Learning' MOOC. Utilizes the Hastie textbook. 

C. Data Visualization
- Developing Data Products - Coursera, Johns Hopkins University. Covers creating data products using Shiny, R packages, and interactive graphics in order to better explain your data. 



