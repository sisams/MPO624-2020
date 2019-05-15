# Syllabus of MPO/ATM 642, spring 2020
Applied Data Analysis (ADA) in an ocean/atmosphere context. 
https://github.com/MPO624/2020.

Instructor: Brian Mapes, mapes@miami.edu. MSC366 is my office. 

Class meets: 10:30-11:45 Tues-Thurs

Clinc / office hours: By arrangement

No required text, all software is free. Supplemental readings may be found in the Readings area. 

## Goals and spirit of the course
##### _If you want to build a ship, don't drum up people to collect wood and don't assign them tasks and work, but rather teach them to long for the endless immensity of the sea. --Antoine de Saint-Exupery_

Learning outcomes: 

  (1) an appreciation, deep interest, appropriate level of confidence, and positive feeling for lifelong learning about ADA and evidence based reasoning: the essence of the life of the mind

  (2) a broad vocabulary about the space of data analysis concepts and tools, from probability (frequentist and Bayesian) to standard statistics (correlation and regression; parametric hypothesis testing and 'significance') to emerging methods (information theory and compression, nonparametric methods including machine learning)

  (3) software skills: a can-do feeling about accessing and understanding the exploding universe of computational tools
  
  (4) a personal success at expert depth in some technique and application (your project)

## Activities and grading
We have 28 75-minute classes together, plus double that much of your time dedicated to working on your own (or with me or the TA in office hours/ ‘clinic’ sessions). I will try to respect student time by bounding the assignments according to ability levels. Earnest effort at this time level will suffice for success, even as there is always more to know. Collaboration among students is strongly encouraged, within the [UM graduate honor code](https://www.grad.miami.edu/_assets/pdf/graduate_student_honor_code_2016_2017.pdf). 

#### Student work expectations are: 
  * 25% Attendance and participation in class. 
  
  * 25% Homework assignments (mostly digital)  
  
  * 25% Two exams (early-mid and late-mid term; second one may be take-home)
  
  * 25% End-of term research project presentation (15+ minutes). **Note from 2018: Best results come from framing a well-defined question or goal as early as possible: for instance, testing some null hypothesis that (x,y) are not related.** 
  
## Course structure

### Theory Tuesdays, Computer Thursdays

Tuesdays will cover the essential ideas and vocabulary, aimed toward the exams. 

Thursdays will be done with a projector, often paralleling the homework assignments (follow along; then students extend examples or change to their own data inputs for homework).  

### 3 modules: basic stats, series methods, empirical methods 
Three main modules break up the 14 weeks into ~5 week chunks.

1. Notations, concepts, and their expression in basic statistics. Sets. Probability distributions and measures. Information content, compression, and degrees of freedom. Synthetic data generation. Discrete vs. continuous thinking. Small-N hazards, big-N hazards. Estimation under uncertainty. The triplet of correlation, covariance, and regression. The various dichotomies (frequentist vs. Bayesian; paramatric vs. nonparametric; unbiased vs. maximum-likelihood estimators; a priori vs. a posteriori significance; overfitting vs. underfitting; hypothesis vs. null hypothesis). 

2. Series methods for data ordered along a dimension (like time series), preferably uniformly. Fourier mapping to/from spectral space. The best ways to display and interpret spectra (and why these are variously used). The common null hypotheses (white and colored noises, especially AR1 “red noise”). A glimpse of wavelet methods. 

3. Empirical or data-driven analysis. The agnostic approach is philosophically satisfying, but there are pitfalls (overfitting). Maximum Covariance techniques like EOFxPC `data(x,t) = EOF1(x) PC1(t) + EOF2(x) PC2(t) + … ` A glimpse of machine learning methods. How science's goals and evidentiary standards differ from commerce or law. 




## Provisional schedule: 

week | Tuesdays theory | Thursdays computers | dates
-----|----------|-----------|------
1 | Introductions, orientation     |Computer & github setup      |
2 | Deconstruct your science paper's evidence | Computer skills follow-along | 
3 | **Module 1**: sets and stats | Distributions                | 
4 | " : probability|Joint distributions        |  
5 | " : cov,cor,reg| Regression                | 
6 | " : matrices   | Multiple regression        | 
7 | **Module 2**: series | fft decomposition and reconstruction  | 
8 | " : orthogonality, Parseval's theorem| Spectra, plotting   | 
9 | SPRING | BREAK | 
10| **Module 2**: cross-spectra | Fluxes by scale example  | 
11| " : DOFs and significance; wavelets   | Example notebooks     | 
12| **Module 3**: empirical decompositions | EOF example  | 
13| " : machine learning 1  | scikit-learn examples | 
14| " : machine learning 2: neural nets  | TensorFlow example | 
15| " : machine learning 3 | Survey of examples; discussion  | 
16| Reading, projects | Presentation of projects | 

