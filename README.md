

# Topics in Advanced Bayesian Methodology (Fall 2023) STAT 451
Instructor: Aaron Schein <br>
Term: Fall 2023 <br>
The University of Chicago

---

## Logistics:
- Time: Tuesday and Thursday, 3:30am-4:50pm
- Place: Eckhart room 133
- Office hours: 
    - Wei: Monday 2-3 pm (Jones 304)
    - Sounak: Friday 3-4 pm (Jones 308)

## Assignments
- [Assignment 1: Bayesian decision theory](https://github.com/aschein/stat_348/blob/main/assignments/hw1/hw1.ipynb). Due **Monday April 3 at 11:59pm** on GradeScope. 
- [Assignment 2: Logistic regression and beta-binomial updating](https://github.com/aschein/stat_348/blob/main/assignments/hw2/hw2.ipynb). Due **Monday April 10 at 11:59pm** on GradeScope. 
- [Assignment 3: Exponential families, conjugacy, and entropy](https://github.com/aschein/stat_348/blob/main/assignments/hw3/hw3.pdf). Due **Monday April 17 at 11:59pm** on GradeScope. 
- [Assignment 4: HMMs, belief propagation, variable elimination](https://github.com/aschein/stat_348/blob/main/assignments/hw4/hw4.ipynb). Due **Tuesday May 2 at 11:59pm** on GradeScope. 
- [Assignment 5: Bayesian mixture models, Gibbs sampling, EM](https://github.com/aschein/stat_348/blob/main/assignments/hw5/hw5.ipynb). Due **Sunday May 21 at 6:00pm** on GradeScope. 

## Schedule

### Lecture 1 (March 23): Introduction & the hunt for the USS Scorpion
- Suggested readings:
  - Freedman (1994): ["Some issues in the foundations of statistics"](https://github.com/aschein/stat_348/blob/main/materials/Freedman1994.pdf)
  - Freedman ["Notes on the Dutch Book argument"](https://www.stat.berkeley.edu/~freedman/dutchdef.pdf)
  - Chap 15 "The Navy Searches" of [_The Theory That Would Not Die_](https://yalebooks.yale.edu/book/9780300188226/the-theory-that-would-not-die/) (see Canvas for e-copy)
- Materials:
  - [Slides](https://github.com/aschein/stat_348/blob/main/materials/1_intro_and_motivations.pdf)

### Lecture 2 (March 25): Bayesian and frequentist decision theory
- Suggested readings:
   - Chap 1 of Berger (1985) [_Statistical Decision Theory and Bayesian Analysis_](https://link.springer.com/book/10.1007/978-1-4757-4286-2) (see Canvas for e-copy)

### Lecture 3 (March 28): Supervised learning, posterior updating, empirical Bayes
- Suggested readings:
    - Chap 2 of Hastie et al. (2009) [_Elements of Statistical Learning_](https://hastie.su.domains/ElemStatLearn/)
- Materials:
    - [Slides](https://github.com/aschein/stat_348/blob/main/materials/3_logreg_and_beta_binomial.pdf)

### Lecture 4 (March 30): Conjugacy and the exponential families
- Suggested readings:
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2015F/notes/exponential-family.pdf) on exponential families
   
### Lecture 5 (April 4): Prior & predictive distributions, exponential families, information theory
- Suggested readings:
    - Fong & Holmes (2020) [On the marginal likelihood and cross-validation](https://github.com/aschein/stat_348/blob/main/materials/FongHolmes2020.pdf)
    - Chap 9.1-9.2 of Murphy (2012) [_Machine Learning: A Probabilistic Perspective_](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
    - Chap 14 of John Duchi's [lecture notes](https://anilkeshwani.github.io/files/John-Duchi-Statistics-311-Electrical-Engineering-377.pdf) on info theory

### Lecture 6 (April 6): Conditional entropy, mutual information, symbol codes
- Suggested readings:
    - Chap 1-2, 4.1-4.3, 5.1-5.3, 8 of MacKay (2005) [_Information Theory, Inference, and Learning Algorithms_](http://www.inference.org.uk/itprnn/book.pdf) 
    - Wikipedia article on [Z-channels](https://en.wikipedia.org/wiki/Z-channel_(information_theory))

### Lecture 7 (April 11): Probabilistic graphical models (PGMs)
- Suggested readings:
    - Chap 2 of Jordan (2003) [_An Introduction to Probabilistic Graphical Models_](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter2.pdf)
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/graphical-models.pdf) on PGMs

### Lecture 8 (April 13): Inference in PGMS: variable elimination, belief propagation
- Suggested readings:
    - [Chap 3](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter3.pdf) and [chap 4](https://people.cs.pitt.edu/~milos/courses/cs3750-Spring2020/Readings/Graphical_models/chapter4.pdf) of Jordan (2003) _An Introduction to Probabilistic Graphical Models_
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/inference.pdf) on inference in PGMs
   
### Lecture 9 (April 18): HMMs and the forwards-backwards algorithm
- Suggested readings:
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/inference.pdf) on inference in PGMs
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture13_hmms.pdf) on HMMs
    - Ramesh Sridharan's [lecture notes](https://people.csail.mit.edu/rameshvs/content/hmms.pdf) on HMMs
    - Chap 13 (specifically 13.2.2-13.2.4) of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

### Midterm (April 20)

### Lecture 10 (April 25): Baum-Welch, EM, mixture models
- Suggested readings:
    - Chap 9 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture08-em.pdf) on EM
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture13_hmms.pdf) on HMMs

### Lecture 11 (April 27): Bayesian mixture models, conditional conjugacy, EM
- Suggested readings:
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture07-mixtures.pdf) on Bayesian mixtures
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/gibbs.pdf) on Bayesian mixtures
    - Last lecture's readings
    

### Lecture 12 (May 2): Gibbs sampling and MCMC
- Suggested readings:
    - Chap 11.1.6-11.3 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/gibbs.pdf) on Bayesian mixtures and Gibbs sampling
    - Matthew Stephen's [lecture notes](https://stephens999.github.io/fiveMinuteStats/gibbs1.html) on Gibbs sampling
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture04_mcmc.pdf) on MCMC
    - Gregory Gunderson's blogpost on [ergodic Markov chains](https://gregorygundersen.com/blog/2019/10/28/ergodic-markov-chains/)

### Lecture 13 (May 4): Gibbs sampling (cont.): missing data, collapsed Gibbs, Geweke testing
- Suggested readings:
    - Chap 24.2 of Murphy (2012) [_Machine Learning: A Probabilistic Perspective_](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
    - David Blei's [lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/gibbs.pdf) on Bayesian mixtures and Gibbs sampling
    - Stephens (2000): ["Dealing with label switching in mixture models"](https://stephenslab.uchicago.edu/assets/papers/Stephens2000b.pdf)
    - Geweke (2004): ["Getting it Right: Joint Distribution Tests of Posterior Simulators"](http://qed.econ.queensu.ca/pub/faculty/ferrall/quant/papers/04_04_29_geweke.pdf)
    - Roger Grosse's [blogpost](https://lips.cs.princeton.edu/testing-mcmc-code-part-2-integration-tests/) on Geweke testing

### Lecture 14 (May 9): Variational inference
- Suggested readings:
    - Blei, Kucukelbir & McAuliffe (2017) ["Variational inference: A review for statisticians"](http://www.cs.columbia.edu/~blei/fogm/2018F/materials/BleiKucukelbirMcAuliffe2017.pdf)
    - Chap 10.1-10.2, 10.4 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture09-cavi.pdf) on VI

### Lecture 15 (May 11): Admixture models and LDA
- Suggested readings:
    - Chap 27.3 of Murphy (2012) [_Machine Learning: A Probabilistic Perspective_](http://noiselab.ucsd.edu/ECE228/Murphy_Machine_Learning.pdf)
    - Scott Linderman's [slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture09-lda_cavi.pdf) on CAVI for LDA
    - Jeffrey Miller's [slides](https://jwmi.github.io/BMB/12-Variational-inference-and-LDA.pdf) on CAVI for LDA
    - Matt Gormley's [slides](https://www.cs.cmu.edu/~mgormley/courses/10701-f16/slides/lecture20-topic-models.pdf) on LDA
    - Blei, Ng, Jordan (2003) ["Latent Dirichlet Allocation"](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)
    - Pritchard, Stephens, Donnelly (2000) ["Inference of Population Structure Using Multilocus Genotype Data"](https://academic.oup.com/genetics/article/155/2/945/6048111)

### Lecture 16 (May 16): Non-negative matrix factorization (NMF) and Poisson factorization
- Suggested readings:
    - Lee and Seung (1999) ["Learning the parts of objects by non-negative matrix factorization"](https://www.nature.com/articles/44565)
    - Gillis (2014) ["The How and Why of Nonnegative Matrix Factorization"](https://arxiv.org/pdf/1401.5226.pdf)
    - Gopalan et al. (2014) ["Scalable Recommendation with Poisson Factorization"](https://arxiv.org/pdf/1311.1704.pdf)

### Lecture 17 (May 18): Wrap-up, review, future topics
- Materials:
    - [Slides](https://github.com/aschein/stat_348/blob/main/materials/17_wrapup.pdf)

