
### Want to play with these notebooks online without having to install anything?
Use any of the following services.

**WARNING**: Please be aware that these services provide temporary environments: anything you do will be deleted after a while, so make sure you download any data you care about.

* **Recommended**: Open it in [Binder](https://mybinder.org/v2/gh/tatsath/AlgorithmicTrading/main):
<a href="https://mybinder.org/v2/gh/tatsath/AlgorithmicTrading/main"><img src="https://matthiasbussonnier.com/posts/img/binder_logo_128x128.png" width="90" /></a>

  * _Note_: Binder is a hosting service and the directories of the book will open exactly like they open on your local machine with no installation required. The connection between different files within the folder will work seamlessly. Most of the time, Binder starts up quickly and works great, but when the github repository of this book is updated, Binder creates a new environment from scratch, and this can take quite some time. Also, some of the case study, specially that require more cache data might be slow.
  
* Open this repository in [Colaboratory](https://colab.research.google.com/github/tatsath/AlgorithmicTrading/blob/main):
<a href="https://colab.research.google.com/github/tatsath/AlgorithmicTrading/blob/main"><img src="https://colab.research.google.com/img/colab_favicon.ico" width="90" /></a>

  * _Note_: Google colab supports GPU and can be quite fast. However, the linkages to data file located in the folders of the git directory may not work. Upload the data files seperately while running the jupyter notebooks on google colab. For loading the data files on google colab, you can replace the local directory path with the github path. For example, for the data of case study 1 of chapter 7 _dataset = read_csv('Dow_adjcloses.csv')_ in the code can be replace with _dataset = read_csv('https://raw.githubusercontent.com/tatsath/fin-ml/master/Chapter%207%20-%20Unsup.%20Learning%20-%20Dimensionality%20Reduction/CaseStudy1%20-%20Portfolio%20Management%20-%20Eigen%20Portfolio/Dow_adjcloses.csv')_ for it to work on google colab.  

