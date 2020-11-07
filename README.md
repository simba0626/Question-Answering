# Question Answering over Knowledge Base (KBQA) Resources

This repository provides resources for KBQA , including benchmark datasets, papers, tutorials, PhD thesis, and systems.

Contributed by [simba0626](https://github.com/simba0626). Email him if you have any questions.

## Tutorials or Slides

1. **Semanitc Parsing slides**  
[[website](https://github.com/scottyih/Slides)]  
Lecturer: scottyih  

1. **Semantic Parsing Resources**  
[[website](https://github.com/casnlu/Semantic-Parsing)]  
cite: Bo Chen

1. **Question Answering Systems**  
[[website](https://www.mpi-inf.mpg.de/question-answering-systems/)]  
Lecturer: Dr. Rishiraj Saha Roy

1. **Question Answering over Curated and Open Web Sources**  
[[website](https://www.avishekanand.com/talk/sigir20-tute/)]  
Lecturer: Rishiraj Saha Roy and Avishek Anand  
Abstract: the tutorial would cover the highlights of this really active period of growth for QA.

1. **Question Answering**  
[[website](https://github.com/xanhho/Reading-Comprehension-Question-Answering-Papers)]  
cite: Xanh Ho


## Datasets

1. **MSParS (V1.0)**  
[[website](https://github.com/JunweiBao/MSParS)]  
Abstract: a Multi-perspective Semantic ParSing Dataset  

1. **GraphQuestions**  
[[website](https://github.com/ysu1989/GraphQuestions)]  
cite: Yu Su, Huan Sun, Brian Sadler, Mudhakar Srivatsa, Izzeddin Gur¨, Zenghui Yan, Xifeng Yan. 2016. On Generating Characteristic-rich Question Sets for QA Evaluation. In EMNLP.

1. **LC-QuAD**  
[[website](https://github.com/AskNowQA/LC-QuAD)]  
cite: Trivedi, Priyansh and Maheshwari, Gaurav and Dubey, Mohnish and Lehmann, Jens. 2017. Lc-quad: A corpus for complex question answering over knowledge graphs. In ISWC.

1. **KQA Pro**  
[[website]()]
Title: KQA Pro: A Large Diagnostic Dataset for Complex Question Answering over Knowledge Base  
Abstract: KQA Pro, a large-scale dataset for Complex KBQA. They generate questions, SPARQLs, and functional programs with recursive templates and then paraphrase the questions by crowdsourcing, giving rise to around 120K diverse instances; They contribute a unified codebase and conduct extensive evaluations for baselines and state-of-the-arts.

## QA over knowledge base and text Papers



## Question Decomposition Papers

1. **Unsupervised Question Decomposition for Question Answering (Facebook AI 2020)**  
[[website](https://arxiv.org/pdf/2002.09758.pdf)]  
Author: Ethan Perez, Patrick Lewis, Wen-tau Yih, Kyunghyun Cho, Douwe Kiela  
Abstract: an unsupervised approach to produce sub-questions.  

1. **Processing knowledge graph-based complex questions through question decomposition and recomposition (Information Sciences 2020)**  
[[website](https://www.sciencedirect.com/science/article/pii/S002002552030150X)]  
Author: Sangjin Shin, Kyond-Ho Lee.  
Abstract: a novel QA method that first decomposes an input question and then generates a correct query graph with fully complete semantics.  

1. **Multi-hop Reading Comprehension through Question Decomposition and Rescoring (2019 ACL Long Paper)**  
[[website](https://www.aclweb.org/anthology/P19-1613/)]  
Author: Sewon Min, Victor Zhong, Luke Zettlemoyer, Hannaneh Hajishirzi  
Abstract: a system for multi-hop RC that decomposes a compositional question into simpler sub-questions that can be answered by off-the-shelf single-hop RC models.  


## KBQA Papers
(ordered by year)

### 2020

1. **Few-Shot Complex Knowledge Base Question Answering via Meta Reinforcement Learning (EMNLP)**  
Author: Yuncheng Hua, Yuan-Fang Li et al.. 

1. **Retrieve, Program, Repeat: Complex Knowledge Base Question Answering via Alternate Meta-learning (IJCAI)**  
Author: Yuncheng Hua, Yuan-Fang Li et al.. 

1. **Less is more: Data-efficient complex question answering over knowledge bases (JWS) **
Author: Yuncheng Hua, Yuan-Fang Li et al.. 

1. **PNEL: Pointer Network Based End-To-End Entity Linking over Knowledge Graphs  (ISWC)**  
Author: Debayan Banerjee, Debanjan Chaudhuri, Mohnish Dubey, and Jens Lehmann

1. **Leveraging Semantic Parsing for Relation Linking over Knowledge Bases (ISWC)**  
Author: Nandana Mihindukulasooriya. et al..  

1. **Retrieve, Program, Repeat: Complex Knowledge Base Question Answering via Alternate Meta-learning**  
Author: Yuncheng Hua1, Yuan-Fang Li, Gholamreza Haffari, Guilin Qi1, and Wei Wu

1. **The Value of Paraphrase for Knowledge Base Predicates**  
[[website](https://github.com/pkumod/Paraphrase)]  
Author: Bingcong Xue, Sen Hu, Lei Zou, Jiashu Cheng
Abstract: a full process of collecting large-scale and high-quality paraphrase dictionaries for predicates in knowledge bases.  

1. **Relationship Search over Knowledge Graphs**  
Author: Dr. Gong Cheng  
Abstract: the author introduces their recent studies on relationship search, including search algorithms based on novel index structures, methods for relationship clustering to support result exploration, and query relaxation techniques to provide alternative results for failed searches.  

1. **Scalable Multi-Hop Relational Reasoning for Knowledge-Aware Question Answering**  
Abstract: they propose a novel knowledgeaware approach that equips PTLMs with a multi-hop relational reasoning module, named multi-hop graph relation networks (MHGRN).

1. **Improving Multi-hop Question Answering over Knowledge Graphs using Knowledge Base Embeddings**  
[[website](https://github.com/malllabiisc/EmbedKGQA)]  
Abstract: EmbedKGQA is particularly effective in performing multi-hop KGQA over sparse KGs. EmbedKGQA also relaxes the requirement of answer selection from a prespecified neighborhood, a sub-optimal constraint enforced by previous multi-hop KGQA methods.

1. **Domain Adaptation for Semantic Parsing**   
[[website](https://github.com/zechagl/DAMP)]  
Abstract: The semantic parser benefits from a two-stage coarse-to-fine framework, thus can provide different and accurate treatments for the two stages, i.e., focusing on domain invariant and domain specific information.
cite: in IJCAI

1. **Falcon 2.0: An Entity and Relation Linking Tool over Wikidata**   
[[website](https://labs.tib.eu/falcon/falcon2/)]  
Abstract: Falcon 2.0 resorts to the English language model for the recognition task (e.g., N-Gram tiling and N-Gram splitting), and then an optimization approach for linking task.  

1. **Faithful Embeddings for Knowledge Base Queries**  
Abstract: a novel QE method that is more faithful to deductive reasoning, and show and show that this leads to better performance on complex queries to incomplete KBs.

1. **Compositional Generalization in Semantic Parsing: Pre-training vs. Specialized Architectures**   
Abstract: They investigate state-of-the-art techniques and architectures in order to assess new architectures and techniques' effectiveness in improving compositional generalization in semantic parsing tasks based on the SCAN and CFQ datasets.  

1. **No One is Perfect: Analysing the Performance of Question Answering Components over the DBpedia Knowledge Graph**  
[[website](https://arxiv.org/abs/1809.10044)]  
Author: Kuldeep Singh  
Abstract: They analyse and micro evaluate the behaviour of 29 available QA components for the DBpedia knowledge graph that were released by the research community since 2010.

### 2019

1. **Message Passing for Complex Question Answering over Knowledge Graphs (CIKM-long paper)**  
[[website](https://dl.acm.org/doi/10.1145/3357384.3358026)]  
[[code](https://github.com/svakulenk0/KBQA]  
Abstract: a novel approach for complex KGQA that uses unsupervised message passing, which propagates confidence scores obtained by parsing an input question and matching terms in the knowledge graph to a set of possible answers. First, identify entity, relationship, and class names mentioned in a natural language question, and map these to their counterparts in the graph. Then, the confidence scores of these mappings propagate through the graph structure to locate the answer entities. Finally, these are aggregated depending on the identified question type.

1. **Stepwise Reasoning for Multi-Relation Question Answering over Knowledge Graph withWeak Supervision (WSDM-long paper)**  
[[website](https://dl.acm.org/doi/abs/10.1145/3336191.3371812)]  
Abstract: this paper proposes a neural method based on reinforcement learning, namely Stepwise Reasoning Network, which formulates multirelation question answering as a sequential decision problem.  

1. **Complex Program Induction for Querying Knowledge Bases in the Absence of Gold Programs (TACL)**  
[[website](https://www.aclweb.org/anthology/Q19-1012/)]  
Abstract: They present Complex Imperative Program Induction from Terminal Rewards (CIPITR), an advanced neural programmer that mitigates reward sparsity with auxiliary rewards, and restricts the program space to semantically correct programs using high-level constraints, KB schema, and inferred answer type.  

1. **Neural program induction for KBQA without gold programs or query annotations (IJCAI)**
Author: Ghulam Ahmed Ansari

### 2018

1. **Sequence-to-Action: End-to-End Semantic Graph Generation for Semantic Parsing (ACL-long paper)**  
[[website](https://www.aclweb.org/anthology/P18-1071/)]  
Author: Bo Chen, Le Sun, Xianpei Han  
Abstract: Sequence-to-Action models semantic parsing as an end-to-end semantic graph generation process.  

1. **Embedding Logical Queries on Knowledge Graphs (NIPS)**  
[[website](https://papers.nips.cc/paper/7473-embedding-logical-queries-on-knowledge-graphs.pdf)]  
Author: William L. Hamilton, Payal Bajaj, Marinka Zitnik, Dan Jurafsky, Jure Leskovec  
Abstract: a framework to efficiently make predictions about conjunctive logical queries—a flexible but tractable subset of first-order logic—on incomplete knowledge graphs.

1. **The Web as a Knowledge-base for Answering Complex Questions (NAACL)**  
Author: Alon Talmor and Jonathan Berant  

### before 2018

1. **MulCQA (2016 COLING)**  
[[website](https://github.com/JunweiBao/MulCQA)]  
Author: Junwei Bao  

1. **Semantic Parsing via Staged Query Graph Generation: Question Answering with Knowledge Base (2015 ACL)**  
Author: Scott Wen-tau Yih

1. **Traversing Knowledge Graphs in Vector Space (2015 EMNLP)**
Author: Kelvin Guu, John Miller, and Percy Liang

1. **Schemaless and Structureless Graph Querying (2014 VLDB)**  
[[website](https://dl.acm.org/doi/abs/10.14778/2732286.2732293)]  
Author: Shengqi Yang, Yinghui Wu, Huan Sun, Xifeng Yan  
Abstract: a novel framework enabling schemaless and structureless graph querying (SLQ).  

1. **Semantic Parsing on Freebase from Question-Answer Pairs (2013 EMNLP)**  
Author: J. Berant

## PhD thesis

## Survey

1. **Interpretable Complex Question Answering (2020 WWW)**  
[[website](https://dl.acm.org/doi/fullHtml/10.1145/3366423.3380764)]  
Author: Soumen Chakrabarti  
Abstract: review cross-community co-evolution of QA with the advent of large-scale knowledge graphs (KGs).

1. **A Survey on Complex Question Answering over Knowledge Base: Recent Advances and Challenges (2020 arXiv)**  
[[website](https://arxiv.org/abs/2007.13069)]  
Author: Bin Fu, Yunqi Qiu, Chengguang Tang, Yang Li, Haiyang Yu, Jian Sun  
Abstract: the recent advances in complex QA.

1. **A Survey of Question Answering over Knowledge Base (2019 CCKS)**  
[[website](https://link.springer.com/chapter/10.1007/978-981-15-1956-7_8)]  
Author: Peiyun Wu, Xiaowang Zhang, and Zhiyong Feng
Abstract: a survey of KBQA approaches by classifying them in two categories: semantic parsing and information retrieval.

1. **Deep Learning in Question Answering (LDNLP book chapter 7)**  
[[website](https://link.springer.com/chapter/10.1007/978-981-10-5209-5_7)]  
Author: Kang Liu and Yansong Feng  
Abstract: deep learning in KBQA and deep learning in MRC. The former is information extraction style and semantic parsing style. The latter is feature engineering and deep learning.  

1. **A Survey on Semantic Parsing (2018 arXiv)**  
[[website](https://arxiv.org/abs/1812.00978)]  
Author: Aishwarya Kamath, Rajarshi Das  
Abstract: they examine the various components of a semantic parsing system and discuss prominent work ranging from the initial rule based methods to the current neural approaches to program synthesis.  

1. **Review on the advancements of disambiguation in semantic question answering system (2017 IPM)**  
[[website](https://www.sciencedirect.com/science/article/abs/pii/S0306457316302102)]  
Author: Sofian Hazrina  
Abstract: formulating an SQA conceptual framework based on an in-depth study of existing SQA processes; identifying and highlighting the ambiguity types; analysing the results of the existing SQA disambiguation solutions.  

1. **Survey on Challenges of Question Answering in the Semantic Web (2016 SWJ)**  
[[website](http://www.semantic-web-journal.net/system/files/swj1375.pdf)]  
Author: Konrad Höffner,  Sebastian Walter, Edgard Marx, Ricardo Usbeck,  Jens Lehmann, Axel-Cyrille Ngonga Ngomo  
Abstract: the survey analyszes 62 SQA systems.

1. **An introduction to Question Answering over Linked Data (2014 RW)**  
[[website](https://link.springer.com/chapter/10.1007/978-3-319-10587-1_2)]  
Author: Christina Unger, André Freitas, Philipp Cimiano  
Abstract: the paper summarizes the main existing approaches and systems including available tools and resources, benchmarks and evaluation campaigns.  

1. **Evaluating question answering over linked data (2013 JWS)**  
[[website](https://www.sciencedirect.com/science/article/abs/pii/S157082681300022X)]  
Author: Vanessa Lopez, Christina Unger, Philipp Cimiano, Enrico Motta  
Abstract: a series of evaluation challenges for question answering over linked data (QALD).  

1. **Is Question Answering fit for the Semantic Web?: A survey (2011 SWJ)**  
[[website](http://www.semantic-web-journal.net/content/question-answering-fit-semantic-web-survey)]  
Author: Vanessa Lopez, Victoria Uren, Marta Sabou and Enrico Motta  
Abstract: a survey on ontology-based Question Answering (QA).


