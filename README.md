----------
# Programming Related Resources #
----------

## Programming Central ##


| Language      | Book List      | Installation  | Documentation | Forum                      |
| ------------- |:--------------:|:-------------:|:-------------:|:--------------------------:|
| C++           | [Books][10001] | pip           |               |                            |

[10001]: https://github.com/ingehap/ingehap.github.io/CPP_books.md

### 01. C++ ###

#### 01.1 C++ - Books ####

- *Abrahams, C++ Template Metaprogramming*
- *Alexrandrescu, Modern C++ Design*
- *Koenig, Accelerated C++*
- *Romanik, Applied C++*
- *Schmidt, C++ Network Programming, Volume 1*
- *Schmidt, C++ Network Programming, Volume 2*
- *Siek, Boost Graph Library*
- *Sutter, C++ Coding Standards*
- *Sutter, Exceptional C++*
- *Sutter, Exceptional C++ Style*
- *Sutter, More Exceptional C++*

### 02. Julia ###

- [Jula home page](https://julialang.org/)
- [stochasticlifestyle](http://www.stochasticlifestyle.com/)

### 03. Loglan ###

#### 03.1 Loglan - Template ####

```loglan
/* Initilaize local variables
n = 0
max_frames = 56000

perform CONVERT_LOGS_TO_ARRAYS
perform CHECK_MAX_FRAMES
perform CALCULATIONS
perform CONVERT_ARRAYS_TO_LOGS

end

CONVERT_LOGS_TO_ARRAYS:
dowhile GET_FRAME ()
   n = n + 1
   LOG[n] = LOG_IN
enddo
return

CHECK_MAX_FRAMES:
IF (n > max_frames) THEN
   call DISPLAY_ERROR('Error: Input curves must have at most max_frame samples')
ENDIF
return

CALCULATIONS:
/* One or a combination of the following:
/*     loglan
/*     C++      (begin_c  .... end_c)
/*     matlab 
return

CONVERT_ARRAYS_TO_LOGS:
call REWIND ()
n = 0
dowhile GET_FRAME ()
   n = n + 1
   LOG_OUT = LOG[n]
   call PUT_FRAME ()
enddo
return
```

### 04. Markdown ###

#### 04.1 Markdown - Cheatsheets ####

| Topic         | Forum                   |
| ------------- |:-----------------------:|
| Markdown      | [Adam Pritchard][1]     |

[1]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### 05. Python ###

#### 05.1 Python - Libraries ####

| Library       | Code           | Installation  | Documentation | Forum                      |
| ------------- |:--------------:|:-------------:|:-------------:|:--------------------------:|
| cntk          | [GitHub][1001] | pip           |               |                            |
| keras         | [GitHub][1002] | pip           | [Doc][1003]   | [Google group forum][1004] |
| statsmodels   |                | Anaconda      |               | [Google group forum][1005] |
| tensorflow    | [GitHub][1006] | pip           | [Doc][1007]   |                            |
| theano        | [GitHub][1008] | pip           |               | [Google group forum][1009] |

[1001]: https://github.com/Microsoft/cntk
[1002]: https://github.com/keras-team/keras
[1003]: https://keras.io/
[1004]: https://groups.google.com/forum/#!forum/keras-users
[1005]: https://groups.google.com/forum/#!forum/pystatsmodels
[1006]: https://github.com/tensorflow/tensorflow
[1007]: https://www.tensorflow.org/
[1008]: https://github.com/Theano/Theano
[1009]: https://groups.google.com/forum/#!forum/theano-users

### 2. Competitions ###

- [Kaggle Competitions](https://www.kaggle.com/competitions)

### 3. Courses ###

| Location      | Course name                       |
| ------------- |:---------------------------------:|
| Udacity       | [Data Analyst Nanodegree][52]     |
| Coursera      | [Data Science Specialization][51] |

[51]: https://www.coursera.org/specializations/jhu-data-science
[52]: https://www.udacity.com/course/data-analyst-nanodegree--nd002?v=a4

### 4. Data sets ###

| Data set                 | Forum                     |
| ------------------------ |:-------------------------:|
| ImageNet                 | [Google group forum][101] |
| [Kaggle collection][102] |                           |

[101]: https://groups.google.com/forum/#!forum/imagenet-community
[102]: https://www.kaggle.com/datasets

### 6. Kernels ###

- [Kaggle kernels](https://www.kaggle.com/kernels)

### 9. Major centra ###

- [AI index](https://aiindex.org/)
- [Algorithmia](https://algorithmia.com/)
- [Amazon](https://www.amazon.com)
  + [Manage Your Content and Devices](https://www.amazon.com/mn/dcw/myx.html/ref=nav_youraccount_myk#/home/content/booksAll/dateDsc/)
- [arXiv](https://arxiv.org/)
- [CoCalc](https://cocalc.com/)
- [Codeburst](https://codeburst.io/)
- [Data Carpentry](http://www.datacarpentry.org/)
- [Data Science Central](https://www.datasciencecentral.com)
- [DataCamp](https://www.datacamp.com)
- [Dataquest](https://www.dataquest.io/)
- [Deep Mind](https://deepmind.com/research/publications/)
- [Digital Academy](http://entry.statoil.no/HR/LearnStatoil/DigitalAcademy/pages/digitalacademy-learn.aspx)
- [Distill](https://distill.pub/)
- [EliteDataScience](https://elitedatascience.com)
- [Facebook](https://www.facebook.com/)
- [freeCodeCamp](https://medium.freecodecamp.org/)
- [Google Plus](https://plus.google.com/)
- [Kaggle](https://www.kaggle.com/)
- [KD Nuggets](https://www.kdnuggets.com/)
- [Quora](https://www.quora.com)
  + [Big Data Analysis](https://www.quora.com/topic/Big-Data-Analysis)
  + [Data Analysis](https://www.quora.com/topic/Data-Analysis)
  + [Data Science](https://www.quora.com/topic/Data-Science)
- [Reddit](https://www.reddit.com)
  + [Data Science](https://www.reddit.com/r/datascience/)
  + [Machine Learning](https://www.reddit.com/r/MachineLearning/)
  + [Programming](https://www.reddit.com/r/programming/)
- [Software Carpentry](https://software-carpentry.org/lessons/)
- [Think Big Data](http://thinkbigdata.in/)
- [TowardsDataScience](https://towardsdatascience.com/)
  + [Data science](https://towardsdatascience.com/data-science/home)
  + [Machine-learning](https://towardsdatascience.com/machine-learning/home)
  + [Programming](https://towardsdatascience.com/programming/home)
  + [Data-visualization](https://towardsdatascience.com/data-visualization/home)
- [Twitter](https://twitter.com/)
  + [analyticbridge](https://twitter.com/analyticbridge)
  + [ContainersExpo](https://twitter.com/ContainersExpo)
  + [Docker](https://twitter.com/Docker)
  + [HPDSLab](https://twitter.com/HPDSLab)
  + [KDnuggets](https://twitter.com/kdnuggets)
  + [RStatsStExBot](https://twitter.com/RStatsStExBot)
  + [slashML](https://twitter.com/slashML)
  + [swcarpentry](https://twitter.com/swcarpentry)

### 10. Video playlists ###

- [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/featured)
- [A9](https://www.youtube.com/user/A9Videos/featured)
- [CppCon](https://www.youtube.com/user/CppCon/playlists)
- [Data Science Central](https://www.datasciencecentral.com/video/)
- [Enthought](https://www.youtube.com/user/EnthoughtMedia/playlists)
- [GitHub Training \& Guides](https://www.youtube.com/user/GitHubGuides/playlists)
- [Google](https://www.youtube.com/user/Google/playlists)
- [Google Cloud Platform](https://www.youtube.com/user/googlecloudplatform/playlists)
- [JetBrainsTV](https://www.youtube.com/user/JetBrainsTV/playlists)
- [Microsoft Research](https://www.youtube.com/user/MicrosoftResearch/playlists)
- [Preserve Knowledge](https://www.youtube.com/user/Charleshche/playlists)
- [PyCon 2017](https://www.youtube.com/channel/UCrJhliKNQ8g0qoE_zvL8eVg/videos)
- [PyCon KR](https://www.youtube.com/channel/UC26x6D5xpKx6io4ShfXa_Ow/playlists)
- [UTAPWeLS](https://www.youtube.com/channel/UCHWnztyGyQPEXXbp2Tu0_DA/videos?disable_polymer=1)
