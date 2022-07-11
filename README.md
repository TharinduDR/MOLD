# MOLD - {M}arathi {O}ffensive {L}anguage {D}ataset

The {M}arathi {O}ffensive {L}anguage {D}ataset (MOLD) contains a collection of 2500 annotated Marathi tweets.

The files included are: 
```
MOLD
└─  experiments
└───MOLD_1.0
│   │   MOLD_train.csv
│   │   MOLD_test.csv
└───MOLD_2.0
│   │   MOLDv2_train.csv
│   │   MOLDV2_test.csv
└───SeMOLD
│   │   tweets.csv
│   README.md
```

## MOLD 1.0
- `MOLD_train.csv`: contains 1,875 annotated tweets for the training set.  
- `MOLD_test.csv`: contains 625 annotated tweets for the test set. 

The dataset was annotated using crowdsourcing. The gold labels were assigned taking the agreement of six annotators into consideration. No correction has been carried out on the crowdsourcing annotations. 
Each instance in MOLD 1.0 has been annotated as offensive or not_offensive

## MOLD 2.0
- `MOLDv2_train.csv`: contains 3,100 annotated tweets for the training set.  
- `MOLDV2_test.csv`: contains 500 annotated tweets for the test set. 

The dataset was annotated using crowdsourcing. The gold labels were assigned taking the agreement of six annotators into consideration. No correction has been carried out on the crowdsourcing annotations. 
Each instance in MOLD 1.0 has been annotated for three levels annotated using the popular OLID three-level hierarchical annotation schema; (A) Offensive Language Detection (B) Categorization of Offensive Language (C) Offensive Language Target Identification. 

## SeMOLD 
- `MOLD_train.csv`: contains 8000 tweets annotated using semi-supervised learning.  





## Citation
If you use MOLD 1.0, please refer to this paper:

```bash
@InProceedings{mold,
author = {Gaikwad, Saurabh and Ranasinghe, Tharindu and Zampieri, Marcos and Homan, Christopher M.},
title = {Cross-lingual Offensive Language Identification for Low Resource Languages: The Case of Marathi},
booktitle = {Proceedings of RANLP},
year = {2021}
}
```

If you use MOLD 2.0 or SeMOLD, please refer to this paper:

```bash
@article{Zampieri2022,
author={Zampieri, Marcos and Ranasinghe, Tharindu and Chaudhari, Mrinal and Gaikwad, Saurabh and Krishna, Prajwal and Nene, Mayuresh and Paygude, Shrunali},
title={Predicting the type and target of offensive social media posts in Marathi},
journal={Social Network Analysis and Mining},
year={2022},
month={Jul},
day={09},
volume={12},
number={1},
pages={77},
issn={1869-5469},
doi={10.1007/s13278-022-00906-8},
url={https://doi.org/10.1007/s13278-022-00906-8}
}
```
