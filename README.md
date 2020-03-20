# IE Dataset Zoo
Information extraction dataset zoo.

Contributed by **[Ningyu Zhang](zxlzr.github.io)**, Shumin Deng, Haiyang Yu, Hongbin Ye.


# Relation Extraction

| Dataset | #Rel.|#Inst.|Feature|Source |Resource| Origin |  
|---------|------:|------:|-------:|-------:|-------:|----------| 
|    Fewrel    |    100   | 44,800      | Supervised| Wikipedia+Wikidata |  [url](http://47.92.96.190/dataset/fewrel.tar.gz)     |  [url](http://www.zhuhao.me/fewrel/)        |      
|    TACRED    |    42   | 68,120    | Supervised |Newswire+web  |  -    |  [url](https://nlp.stanford.edu/projects/tacred/)        |  
|    Semeval     |   19    |   8,000    | Supervised|Web|  [url](http://47.92.96.190/dataset/semeval.tar.gz)     |  [url](https://www.kaggle.com/drtoshi/semeval2010-task-8-dataset#__sid=js0)        |    
|    Wikidata     |    352   | 495,883      | Distent-supervision|Wikipedia+Wikidata|  [url](http://47.92.96.190/dataset/wikidata.tar.gz)     |  [url](https://public.ukp.informatik.tu-darmstadt.de/UKP_Webpage/DATA/WikipediaWikidataDistantSupervisionAnnotations.v1.0.zip)        |    
|    NYT10(tsinghua)     |   53    |   522,043    |Distent-supervision | NYT+Freebase|  [url](http://47.92.96.190/dataset/nyt10.tar.gz)     |  [url](https://github.com/thunlp/OpenNRE/)        |    
|    NYT10-large(tsinghua)     |   53    |   570,088   |Distent-supervision | NYT+Freebase|  [url](http://47.92.96.190/dataset/nyt10-large.tar.gz)     |  [url](https://github.com/thunlp/HNRE)      
|    NYT-Wikidata     |       |     | Distent-supervision| NYT+Wikidata |   [url](http://47.92.96.190/dataset/nyt-wikidata.tar.gz)     |  [url](https://github.com/thunlp/PathNRE)        |   
|    NYT10-29     |    29   | 70,339    | Distent-supervision| NYT+Freebase |   [url](http://47.92.96.190/dataset/NYT10.rar)     |  [url](https://github.com/truthless11/HRL-RE/tree/master/data)        |    
|    NYT11-12    |     12  |  62,648   | DS+supervised|  NYT+Freebase|   [url](http://47.92.96.190/dataset/NYT11.rar)     |  [url](https://github.com/truthless11/HRL-RE/tree/master/data)        |  
|   NYT-manual    |    24   | 235,982  |Distent-supervision| NYT+Freebase   |   [url](http://47.92.96.190/dataset/nyt-manual.tar.gz)     |  [url](https://github.com/INK-USC/USC-DS-RelationExtraction)        |  
|   NYT-Wiki(zju)    |  73    | 1,989,377 |Distent-supervision| NYT-Wikipedia-Wikidata   |   [url](http://47.92.96.190/dataset/nyt-wiki.tar.gz)     |  [url](https://github.com/zxlzr/RAN/tree/master/data/NYT-Wiki)        |  
|    Wiki-KBP    |    19   |  23,784  |Distent-supervision| Wikipedia+KBP+Freebase  |   [url](http://47.92.96.190/dataset/kbp.tar.gz)     |  [url](https://github.com/INK-USC/USC-DS-RelationExtraction)        |    
|    PubMed-BioInfer     |   94  | 1,580 | Distent-supervision |  PubMed+NESH     | -   |  [url](https://github.com/INK-USC/USC-DS-RelationExtraction)        |    
|    WebNLG     |   14    | 75,325    |  Supervised | Web |   -   |  [url](https://drive.google.com/open?id=1zISxYa-8ROe2Zv8iRc82jY9QsQrfY1Vj)        |    
|    SKE     |    50   |     | Supervised | Web  |   [url](http://47.92.96.190/dataset/ske.tar.gz)     |  [url](https://ai.baidu.com/broad/download?dataset=sked)        |    
|    KBP37     |    37  |  15,916   | Supervised  | Web |   [url](http://47.92.96.190/dataset/ske.tar.gz)     |  [url](https://github.com/zhangdongxu/kbp37)        |  
|    T-REx    |   642   |  6.3M  | Distent-supervision   | Wikipedia+Wikidata |  -   |  [url](https://hadyelsahar.github.io/t-rex/)        |  
|   Google-RE    |   5   |  59,576  | Supervised | Wikipedia |  -    |  [url](https://github.com/google-research-datasets/relation-extraction-corpus)        |  
|   ADE   |    3  | 23,516 | Supervised|  Medical Report | [url](http://47.92.96.190/dataset/ade.tar.gz)     |  [url](https://github.com/davidsbatista/Annotated-Semantic-Relationships-Datasets)        |  

Other Datasets

- [WikiReading](https://github.com/google-research-datasets/wiki-reading) 


## Fewrel

FewRel : A Large-Scale Supervised Few-Shot Relation Classification Dataset with State-of-the-Art Evaluation 

Matching the Blanks : Distributional Similarity for Relation Learning ACL2019

Multi-Level Matching and Aggregation Network for Few-Shot Relation Classification ACL2019

## TACRED

Position-aware attention and supervised data improve slot filling.

Matching the Blanks : Distributional Similarity for Relation Learning ACL2019


## Semeval

Matching the Blanks : Distributional Similarity for Relation Learning

## Wikidata

Context-Aware Representations for Knowledge Base Relation Extraction

Attention-Based Capsule Networks with Dynamic Routing for Relation Extraction




## NYT10(tsinghua) 

Distant Supervision for Relation Extraction via Piecewise Convolutional Neural Networks

Self-Attention Enhanced Selective Gate with Entity-Aware Embedding for Distantly Supervised Relation Extraction


## NYT10-large (tsinghua)

Attention-Based Capsule Networks with Dynamic Routing for Relation Extraction EMNLP2018

Hierarchical Relation Extraction with Coarse-to-Fine Grained Attention EMNLP2018

Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks NAACL2019




## NYT-Wikidata

Incorporating Relation Paths in Neural Relation Extraction EMNLP2017

   
## NYT10-29     

A Hierarchical Framework for Relation Extraction with Reinforcement Learning

Joint Extraction of Entities and Relations with a Hierarchical Multi-task Tagging Model

## NYT11-12    

A Hierarchical Framework for Relation Extraction with Reinforcement Learning

Joint Extraction of Entities and Relations with a Hierarchical Multi-task Tagging Model

## NYT-manual

Indirect Supervision for Relation Extraction Using Question-Answer Pairs

CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases.

Joint Extraction of Entities and Relations Based on a Novel Decomposition Strategy

Extracting Relational Facts by an End-to-End Neural Model with Copy Mechanism

Joint Extraction of Entities and Relations Based on a Novel Tagging Scheme

 
##  NYT-Wiki(zju)    


Relation Adversarial Network for Low Resource Knowledge Graph Completion







## Wiki-KBP

CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases.

Indirect Supervision for Relation Extraction Using Question-Answer Pairs


 
 


## PubMed-BioInfer

CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases.

## WebNLG

Extracting relational facts by an end-to-end neural model with copy mechanism


## SKE

MrMep: joint extraction of multiple relations and multiple entity pairs based on triplet attention


## KBP37

Matching the Blanks : Distributional Similarity for Relation Learning ACL2019

Relation classification via recurrent neural network



## T-REx 

T-Rex : A Large Scale Alignment of Natural Language with Knowledge Base Triples

K-ADAPTER: Infusing Knowledge into Pre-Trained Models with Adapters

 

 
# Event Extraction


| Dataset |# Inst.|Feature|Source |Resource| Origin |  
|---------|------:|-------:|-------:|-------:|----------| 
|    ACE05    |   599        | Supervised| Web  |  -  |  [url](https://catalog.ldc.upenn.edu/LDC2006T06)        |      
 |    FewEvent(zju)  |    71,385      | Supervised| ACE05+_TAC-KBP17| [url](http://47.92.96.190/dataset/FewEvent.tar.gz)   |  [url](https://github.com/231sm/Low_Resource_KBP)        | 
 |   CCKS2019_Event   |    17,815       | Supervised|  Financial Announcements  |  [url](http://47.92.96.190/dataset/ccks2019_event.tar.gz) |  [url](https://www.biendata.com/competition/ccks_2019_4/data/)        | 
 |  Doc2EDAG    |       32,040    | Supervised| Financial Announcements | [url](http://47.92.96.190/dataset/doc2edag.tar.gz) |    [url](https://github.com/dolphin-zs/Doc2EDAG)        | 

## ACE05

too many papers

## FewEvent(zju)

Meta-Learning with Dynamic-Memory-Based Prototypical Network for Few-Shot Event Detection

 
## DEE

Doc2EDAG: An End-to-End Document-level Framework for Chinese Financial Event Extraction




