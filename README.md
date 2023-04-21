This page refers to two datasets:
# 1. The MD-Agreement dataset
This dataset contains more than 10k tweet IDs associated with 5 offensive/non-offensive labels from different annotators collected through Amazon Mechanical Turk. The tweets are retrieved from multi-domains (MD): Covid-19, BLM and US Elections. The text of the tweet, the individual annotations and anonymized IDs of annotators are released.

This dataset has been described in the paper:
Agreeing to Disagree: Annotating Offensive Language Datasets with Annotators’ Disagreement. *Elisa Leonardelli, Stefano Menini, Alessio Palmero Aprosio, Marco Guerini and Sara Tonelli*, In Proceedings of EMNLP 2021 (https://aclanthology.org/2021.emnlp-main.822/)

This dataset is also part of the datasets used for the "Learning With Disagreements" task 11 at Semeval 2023 (https://le-wi-di.github.io/). 
# 2. The  MD-Agreement-v2 dataset
This dataset represents a subportion of the MD-Agreement dataset that has been further annotated. In particular, tweets containing disagreement (part of the train and the entire test) have been manually labelled by an expert linguist that judged the type of disagreement contained. The annotation follows a two levels taxonomy of disagreement. 
The MD-Agreement-v2 dataset and the taxonomy of disagreement are presented in the paper:

Marta Sandri, Elisa Leonardelli, Sara Tonelli, and Elis- abetta Jezek. 2023. Why don’t you do it right? analysing annotators’ disagreement in subjective tasks. In Proceedings of the 2023 Conference of the European Chapter of the Association for Computational Linguistics.

-------

In compliance with Twitter policy, the datasets are available for non-commercial research only (https://developer.twitter.com/en/developer-terms/policy) and cannot be used for any discriminatory purpose, event monitoring, profiling or targeting of individuals. 

The datasets **can be obtained upon request to the authors** by filling the following form: https://forms.gle/hBKTUbCR1zimNhicA.
Requestors will be asked to declare that they will not use the datasets to collect any sensitive category of personal information. 


-------

If you use the MD-Agreement dataset, please cite:

@inproceedings{leonardelli-etal-2021-agreeing,  
    title = "Agreeing to Disagree: Annotating Offensive Language Datasets with Annotators{'} Disagreement",  
    author = "Leonardelli, Elisa  and. 
      Menini, Stefano  and <br>
      Palmero Aprosio, Alessio  and <br>
      Guerini, Marco  and  <br>
      Tonelli, Sara",  
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",  
    month = nov,  
    year = "2021",  
    address = "Online and Punta Cana, Dominican Republic",  
    publisher = "Association for Computational Linguistics",  
    url = "https://aclanthology.org/2021.emnlp-main.822",  
    pages = "10528--10539",  
}

If you use the MD-Agreement-v2 dataset, please cite:

@inproceedings{sandri2023,
  title = Why Don’t You Do It Right? Analysing Annotators’ Disagreement in Subjective Tasks, <br>
  author = "Sandri, Marta and 
  Leonardelli, Elisa and <br>
  Tonelli, Sara and  <br>
  Jezek, Elisabetta",
  booktitle = "Proceedings of the 2023 Conference of the European Chapter of the Association for Computational Linguistics",
  year = "2023"
}

