# Bangla Sentiment Classification
This is a compiled version of sentiment analysis dataset collected from several sources for benchmarking purpose. We provide data splits and benchmark results to compare with any future works.  


## Dataset

### Directory structure:
In the following directories we have data splits (train/dev/test) for different datasets.

* data/ABSA_Datasets -- This dataset has developed to per­form aspect ­based sentiment analysis task in Bangla.
* data/SAIL_data -- This dataset, consists of tweet posts, has developed in the Shared task on Sentiment Analysis in Indian Languages (SAIL) 2015. [2]
* data/multichannel_bsentiment -- This data was collected from several newspapers, TV news, books, blogs, and social me­dia.
* data/youtube_sentiment -- This dataset was devel­oped by extracting comments from various YouTube videos.
<!-- * data/consolidated -- all combined dataset from the above data splits -->
**Note:** Due to the license limitation we are not able to release CogniSenti Dataset.

### Lexical Analysis
For the lexical analysis, we computed valance score for each dataset. In *lexical_analysis/* directory, we provided such analyses.


## Licensing
This is a compiled version from several datasets. We are releasing it as CC BY-NC-SA 2.0 (https://creativecommons.org/licenses/by-nc-sa/2.0/).
However, for the respective data source please check the licence in the corresponding papers or source location.



## Please cite the following papers if you are using the data:

1. Md. Arid Hasan and Jannatul Tajrin and Shammur Absar Chowdhury and Firoj Alam, Sentiment Classification in Bangla Textual Content: A Comparative Study, 23rd International Conference on Computer and Information Technology (ICCIT), 2020.
2. B. G. Patra, D. Das, A. Das, and R. Prasath, “Shared task on sentiment analysis in indian languages (sail) tweets­an overview,” in Proc. of
MIKE. Springer, 2015, pp. 650–655.
3. M. Rahman, E. Kumar Dey et al., “Datasets for aspect­based sentiment analysis in bangla and its baseline evaluation,” Data, vol. 3, no. 2, p. 15, 2018.
4. N. I. Tripto and M. E. Ali, “Detecting multilabel sentiment and emotions from bangla youtube comments,” in Proc. of ICBSLP. IEEE, 2018, pp. 1–6.
5. M. Rezaul Karim, B. Raja Chakravarthi, M. Arcan, J. P. McCrae, and M. Cochez, “Classification benchmarks for under­resourced Bengali language based on multichannel convolutional­lstm network,” arXiv, pp. arXiv–2004, 2020.

```bib
@inproceedings{iccit2020Arid,
	Author = {Md. Arid Hasan and Jannatul Tajrin and Shammur Absar Chowdhury and Firoj Alam},
	Booktitle = {23rd International Conference on Computer and Information Technology (ICCIT)},
	Month = {December},
	Title = {Sentiment Classification in Bangla Textual Content: A Comparative Study},
	Year = {2020}
}
@inproceedings{patra2015shared,
  title={Shared task on sentiment analysis in indian languages (sail) tweets-an overview},
  author={Patra, Braja Gopal and Das, Dipankar and Das, Amitava and Prasath, Rajendra},
  booktitle={Proc. of MIKE},
  pages={650--655},
  year={2015},
  organization={Springer}
}

@article{rahman2018datasets,
  title={Datasets for aspect-based sentiment analysis in bangla and its baseline evaluation},
  author={Rahman, Md and Kumar Dey, Emon and others},
  journal={Data},
  volume={3},
  number={2},
  pages={15},
  year={2018},
  publisher={Multidisciplinary Digital Publishing Institute}
}

@article{rezaul2020classification,
  title={Classification Benchmarks for Under-resourced {Bengali} Language based on Multichannel Convolutional-LSTM Network},
  author={Rezaul Karim, Md and Raja Chakravarthi, Bharathi and Arcan, Mihael and McCrae, John P and Cochez, Michael},
  journal={arXiv},
  pages={arXiv--2004},
  year={2020}
}
@inproceedings{tripto2018detecting,
  title={Detecting Multilabel Sentiment and Emotions from Bangla YouTube Comments},
  author={Tripto, Nafis Irtiza and Ali, Mohammed Eunus},
  booktitle={Proc. of ICBSLP},
  pages={1--6},
  year={2018},
  organization={IEEE}
}

```
