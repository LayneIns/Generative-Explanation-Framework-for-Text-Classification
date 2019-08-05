## Dataset for paper "Towards Explainable NLP: A Generative Explanation Framework for Text Classification"

###Datasets
This repository contains two datasets used in the paper "Towards Explainable NLP: A Generative Explanation Framework for Text Classification". You may download both of the two datasets from [here](https://drive.google.com/open?id=1o_r3D-lngEXPK8mtx8UQCbadR65Ycv5a)

+ PCMag Review Dataset
This dataset is crawled from the website [PCMag](https://www.pcmag.com/). It is a website providing reviews for electronic products, like laptops, smartphones, cameras and so on. 
Each item in the dataset consists of three parts: a long review text, three short comments, and an overall rating score for the product. 
    + Three short comments are summaries of the long review respectively from positive, negative, neutral perspectives.
    + An overall rating score is a number ranging from 0 to 5, and the possible values that the score could be are {1.0, 1.5, 2.0, ..., 5.0}.

+ Skytrax User Reviews Dataset
This dataset we used in our paper is adapted from the [original version](https://github.com/quankiquanki/skytrax-reviews-dataset). 
Each item in this dataset consists of three parts: a review text, five sub-field scores and an overall rating score. 
    + The five sub-field scores respectively stand for the user’s ratings for seat comfortability, cabin stuff, food, in-flight environment, and ticket value, and each score is an integer between 0 and 5. 
    + The overall score is an integer between 1 and 10.

### Reference
```
@inproceedings{liu-etal-2019-towards-explainable,
    title = "Towards Explainable {NLP}: A Generative Explanation Framework for Text Classification",
    author = "Liu, Hui  and
      Yin, Qingyu  and
      Wang, William Yang",
    booktitle = "Proceedings of the 57th Conference of the Association for Computational Linguistics",
    month = jul,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/P19-1560",
    pages = "5570--5581",
}
```


