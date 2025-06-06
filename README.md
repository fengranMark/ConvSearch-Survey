# ConvSearch-Survey
This is the collection of papers related to conversarional search. These papers are organized according to our survey paper [A Survey of Conversational Search](https://arxiv.org/pdf/2410.15576). 

Feel free to contact us if you find a mistake or have any advice.

## 🌟 Citation
Please kindly cite our paper if helps your research:
```BibTex
@article{convsearch_survey,
  title={A Survey of Conversational Search},
  author={Mo, Fengran and Mao, Kelong and Zhao, Ziliang and Qian, Hongjin and Chen, Haonan and Cheng, Yiruo and Li, Xiaoxi and Zhu, Yutao and Dou, Zhicheng and Nie, Jian-Yun},
  journal={arXiv preprint arXiv:2410.15576},
  year={2024}
}
```

## 📋 Table of Content
- [Query Reformulation](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#query-reformulation)
  - [Query Reformulation in Conversational Search](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#query-reformulation-in-conversational-search)
  - [Analysis of Existing Datasets](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#analysis-of-existing-datasets)
  - [Evaluation of Query Reformulation](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#evaluation-of-query-reformulation)
- [Search Clarification](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#search-clarification)
  - [Clarification for Conversational Retrieval](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#clarification-for-conversational-retrieval)
  - [Web Search Clarification](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#web-search-clarification)
  - [Search Clarification for Question Answering](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#search-clarification-for-question-answering)
  - [Domain-specific Search Clarification](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#domain-specific-search-clarification)
  - [Search Clarification with LLMs](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#search-clarification-with-llms)
- [Conversational Retrieval](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#conversational-retrieval)
  - [Conversation Modeling](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#conversation-modeling)
  - [Context Denoising](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#context-denoising)
  - [Data Augmentation](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#data-augmentation)
  - [Interpretation in Conversational Dense Retrieval](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#interpretation-in-conversational-dense-retrieval)
  - [Re-ranking in Conversational Search](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#re-ranking-in-conversational-search)
- [Generation in Conversational Search](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#generation-in-conversatational-search)
  - [Utilization of Historical Search Results](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#utilization-of-historical-search-results)
  - [Context Dependency Modeling](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#context-dependency-modeling)
  - [Conversational Knowledge Attribution](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#conversational-knowledge-attribution)
- [Domain-specific and User-centric Conversational Search](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#domain-specific-and-user-centric-conversational-search)
  - [Domain-specific Conversational Search](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#domain-specific-conversational-search)
  - [User-centric Conversational Search](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#user-centric-conversational-search)
- [Other Resources](https://github.com/fengranMark/ConvSearch-Survey?tab=readme-ov-file#other-resources)

## 📄 Paper List

### Query Reformulation

#### Query Reformulation in Conversational Search

1. **Selecting good expansion terms for pseudo- relevance feedback**, *Cao et al*. SIGIR 2008. \[[Paper](https://doi.org/10.1145/1390334.1390377)\]
2. **Finding good feedback documents**, *He et al*. CIKM 2009.  \[[Paper](https://doi.org/10.1145/1645953.1646289)\]
3. **Acquiring lexical knowledge from query logs for query expansion in patent searching**, *Tannebaum et al*. ICSC 2012. \[[Paper](https://doi.org/10.1109/ICSC.2012.15)\]
4. **Can you unpack that? learning to rewrite questions-in-context**, *Elgohary et al*. EMNLP-IJCNLP 2019. \[[Paper](https://doi.org/10.18653/v1/D19-1605)\]
5. **TREC cast 2019: The conversational assistance track overview**, *Dalton et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2003.13624)\]
6. **Making information seeking easier: An improved pipeline for conversational search**, *Kumar et al*. EMNLP 2020. \[[Paper](https://doi.org/10.18653/v1/2020.findings-emnlp.354)\]
7. **Query resolution for conversational search with limited supervision**, *Voskarides et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2005.11723)\]
8. **Question rewriting for conversational question answering**, *Vakulenko et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2004.14652)\]
9. **Topic propagation in conversational search**, *Askari et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2004.14054)\]
10. **Few-shot generative conversational query rewriting**, *Yu et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2006.05009)\]
11. **Conversational question reformulation via sequence-to-sequence architectures and pretrained language models**, *Lin et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2004.01909)\]
12. **Contextualized query embeddings for conversational search**, *Lin et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2104.08707)\]
13. **Multi-stage conversational passage retrieval: An approach to fusing term importance estimation and neural query rewriting**, *Lin et al*. ACM Trans. Inf. Syst. 2021. \[[Paper](https://doi.org/10.1145/3446426)\]
14. **Question rewriting for open-domain conversational QA: best practices and limitations**, *Tredici et al*. CIKM 2021. \[[Paper](https://doi.org/10.1145/3459637.3482164)\]
15. **A comparison of question rewriting methods for conversational passage retrieval**, *Vakulenko et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2101.07382)\]
16. **CONQRR: conversational query rewriting for retrieval with reinforcement learning**, *Wu et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2112.08558)\]
17. **TREC cast 2022: Going beyond user ask and system retrieve with initiative and response generation**, *Owoicho et al*. TREC 2022. \[[Paper](https://trec.nist.gov/pubs/trec31/papers/Overview_cast.pdf)\]
18. **Explicit query rewriting for conversational dense retrieval**, *Qian et al*. EMNLP 2022. \[[Paper](https://doi.org/10.18653/v1/2022.emnlp-main.311)\]
19. **Reinforced question rewriting for conversational question answering**, *Chen et al*. arXiv 2022. \[[Paper](https://doi.org/10.48550/arXiv.2210.15777)\]
20. **Explicit query rewriting for conversational dense retrieval**, *Qian et al*. EMNLP 2022. \[[Paper](https://doi.org/10.18653/v1/2022.emnlp-main.311)\]
21. **Query2doc: Query Expansion with Large Language Models**, *Wang et al*. arXiv 2023. \[[Paper](https://arxiv.org/pdf/2303.07678.pdf)\]
22. **Learning to relate to previous turns in conversational search**, *Mo et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2306.02553)\]
23. **Large language models know your contextual search intent: A prompting framework for conversational search**, *Mao et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2303.06573)\]
24. **Enhancing conversational search: Large language model-aided informative query rewriting**, *Ye et al*. arXiv 2023.  \[[Paper](https://doi.org/10.48550/arXiv.2310.09716)\]
25. **Itercqr: Iterative conversational query reformulation without human supervision**, *Jang et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2311.09820)\]
26. **Convgqr: Generative query reformulation for conversational search**, *Mo et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2305.15645)\]
27. **Ask optimal questions: Aligning large languagemodels with retriever’s preference in conversational search**, *Yoon et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2402.11827)\]
28. **CHIQ: contextual history enhancement for improving query rewriting in conversational search**, *Mo et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2406.05013)\]

#### Analysis of Existing Datasets

1. **Can you unpack that? learning to rewrite questions-in-context**, *Elgohary et al*. EMNLP-IJCNLP 2019. \[[Paper](https://doi.org/10.18653/v1/D19-1605)\]
2. **Open-domain question answering goes conversational via question rewriting**, *Ananha et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2010.04898)\]
3. **TREC cast 2019: The conversational assistance track overview**, *Dalton et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2003.13624)\]
4. **TREC cast 2021: The conversational assistance track overview**, *Dalton et al*. TREC 2021. \[[Paper](https://trec.nist.gov/pubs/trec30/papers/Overview-CAsT.pdf)\]
5. **TREC cast 2022: Going beyond user ask and system retrieve with initiative and response generation**, *Owoicho et al*. TREC 2022. \[[Paper](https://trec.nist.gov/pubs/trec31/papers/Overview_cast.pdf)\]

#### Evaluation of Query Reformulation

1. **Can you unpack that? learning to rewrite questions-in-context**, *Elgohary et al*. EMNLP-IJCNLP 2019. \[[Paper](https://doi.org/10.18653/v1/D19-1605)\]
2. **Open-domain question answering goes conversational via question rewriting**, *Ananha et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2010.04898)\]
3. **Search-oriented conversational query editing**, *Mao et al*. ACL 2023. \[[Paper]( https://doi.org/10.18653/v1/2023.findings-acl.256)\]
4. **Learning to relate to previous turns in conversational search**, *Mo et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2306.02553)\]

### Search Clarification

#### Clarification for Conversational Retrieval

1. **Asking clarifying questions in open-domain information-seeking conversations**, *Aliannejadi et al*. arXiv 2019. \[[Paper](https://arxiv.org/abs/1907.06554)\]
2. **Convai3: Generating clarifying questions for open-domain dialogue systems (clariq)**, *Aliannejadi et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2009.11352)\]
3. **Analysing the effect of clarifying questions on document ranking in conversational search**, *Karasakis et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2008.03717)\]
4. **Guided transformer: Leveraging multiple external sources for representation learning in conversational search**, *Hashemi et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2006.07548)\]
5. **Asking clarifying questions based on negative feedback in conversational search**, *Bi et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2107.05760)\]
6. **Conversational search with mixed-initiative - asking good clarification questions backed-up by passage retrieval**, *Mass et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2112.07308)\]
7. **Towards facet-driven generation of clarifying questions for conversational search**， *Sekulic et al*. ICTIR 2021. \[[Paper](https://doi.org/10.1145/3471158.3472257)\]
8. **Building and evaluating open-domain dialogue corpora with clarifying questions**, *Aliannejadi et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2109.05794)\]
9. **Analysing mixed initiatives and search strategies during conversational search**, *Aliannejadi et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2109.05955)\]
10. **Zero-shot clarifying question generation for conversational search**, *Wang et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2301.12660)\]
11. **An in-depth investigation of user response simulation for conversational search**, *Wang et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2304.07944)\]
12. **Asking multimodal clarifying questions in mixed-initiative conversational search**, *Yuan et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2402.07742)\]
13. **Estimating the usefulness of clarifying questions and answers for conversational search**, *Sekulic et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2401.11463)\]

#### Web Search Clarification

1. **Finding dimensions for queries**, *Dou et al*. CIKM 2011. \[[Paper](https://doi.org/10.1145/2063576.2063767)\]
2. **Extracting query facets from search results**, *Kong et al*. SIGIR 2013. \[[Paper](https://doi.org/10.1145/2484028.2484097)\]
3. **Extending faceted search to the general web**, *Kong et al*. CIKM 2014. \[[Paper](https://doi.org/10.1145/2661829.2661964)\]
4. **Generating clarifying questions for information retrieval**, *Zamani et al*. WWW 2020. \[[Paper](https://doi.org/10.1145/3366423.3380126)\]
5. **Analyzing and learning from user interactions for search clarification**, *Zamani et al*. arXiv 2020. \[[Paper]( https://arxiv.org/abs/2006.00166)\]
6. **MIMICS: A large-scale data collection for search clarification**, *Zamani et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2006.10174)\]
7. **Template-guided clarifying question generation for web search clarification**, *Wang et al*. CIKM 2021. \[[Paper](https://doi.org/10.1145/3459637.3482199)\]
8. **Learning multiple intent representations for search queries**, *Hashemi et al*. CIKM 2021. \[[Paper](https://doi.org/10.1145/3459637.3482445)\]
9. **Ranking clarifying questions based on predicted user engagement**, *Lotze et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2103.06192)\]
10. **Generating clarifying questions with web search results**, *Zhao et al*. SIGIR 2022. \[[Paper]( https://doi.org/10.1145/3477495.3531981)\]
11. **Stochastic optimization of text set generation for learning multiple query intent representations**, *Hashemi et al*. CIKM 2022. \[[Paper](https://doi.org/10.1145/3511808.3557666)\]
12. **Revisiting open domain query facet extraction and generation**, *Samarinas et al*. ICTIR 2022. \[[Paper](https://doi.org/10.1145/3539813.3545138)\]
13. **Search clarification selection via query-intent-clarification graph attention**, *Gao et al*. ECIR 2022. \[[Paper](https://doi.org/10.1007/978-3-030-99736-6_16)\]
14. **Mimics-duo: Offline & online evaluation of search clarification**, *Tavakoli et al*. arXiv 2022. \[[Paper](https://doi.org/10.48550/arXiv.2206.04417)\]
15. **Improving search clarification with structured information extracted from search results**, *Zhao et al*. SIGKDD 2023. \[[Paper](https://doi.org/10.1145/3580305.3599389)\]
16. **A comparative study of training objectives for clarification facet generation**, *Ni et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2310.00703)\]
17. **Clarifying the path to user satisfaction: An investigation into clarification usefulness**, *Rahmani et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2402.01934)\]
18. **Analyzing coherency in facet-based clarification prompt generation for search**, *Litvinov et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2401.04524)\]
19. **Generating multi-turn clarification for web information seeking**, *Zhao et al*. WWW 2024. \[[Paper](https://doi.org/10.1145/3589334.3645712)\]
20. **Enhanced facet generation with LLM editing**, *Lee et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2403.16345)\]
21. **Mining exploratory queries for conversational search**, *Liu et al*. WWW 2024. \[[Paper](https://doi.org/10.1145/3589334.3645424)\]
22. **User engagement prediction for clarification in search**, *Sekulic et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2102.04163)\]

#### Search Clarification for Question Answering

1. **What do you mean exactly?: Analyzing clarification questions in CQA**. *Braslavski et al*. CHIIR 2017. \[[Paper](https://doi.org/10.1145/3020165.3022149)\]
2. **Learning to ask good questions: Ranking clarification questions using neural expected value of perfect information**, *Rao et al*. arXiv 2018. \[[Paper](http://arxiv.org/abs/1805.04655)\]
3. **Answer-based adversarial training for generating clarification questions**, *Rao et al*. arXiv 2019. \[[Paper](http://arxiv.org/abs/1904.02281)\]
4. **Identifying unclear questions in community question answering websites**,* Trienes et al*. arXiv 2019. \[[Paper](http://arxiv.org/abs/1901.06168)\]
5. **Asking clarification questions in knowledge-based question answering**, *Xu et al*. EMNLP-IJCNLP 2019. \[[Paper](https://doi.org/10.18653/v1/D19-1172)\]
6. **Ranking clarification questions via natural language inference**, *Kumar et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2008.07688)\]
7. **Clarq: A large-scale and diverse dataset for clarification question generation**, *Kumar et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2006.05986)\]
8. **Generating clarifying questions in conversational search systems**, *Tavakoli et al*. CIKM 2020. \[[Paper](https://doi.org/10.1145/3340531.3418513)\]
9. **Abg-coqa: Clarifying ambiguity in conversational question answering**, *Guo et al*. AKBC 2021. \[[Paper](https://doi.org/10.24432/C5F30Z)\]
10. **Pseudo ambiguous and clarifying questions based on sentence structures toward clarifying question answering system**, *Nakano et al*. DialDoc@ACL 2022. \[[Paper](https://doi.org/10.18653/v1/2022.dialdoc-1.4)\]
11. **Analyzing clarification in asynchronous information-seeking conversations**, *Tavakoli et al*. J. Assoc. Inf. Sci. Technol. 2022. \[[Paper](https://doi.org/10.1002/asi.24562)\]
12. **Asking clarification questions to handle ambiguity in open-domain QA**, *Lee et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2305.13808)\]
13. **Tree of clarifications: Answering ambiguous questions with retrieval-augmented large language models**, *Kim et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2310.14696)\]

#### Domain-specific Search Clarification

1. **A survey on conversational recommender systems**, *Jannach et al*. arXiv 2020. \[[Paper](https://arxiv.org/abs/2004.00646)\]
2. **Conversational recommendation: Formulation, methods, and evaluation**, *Lei et al*. SIGIR 2020. \[[Paper](https://doi.org/10.1145/3397271.3401419)\]
3. **Advances and challenges in conversational recommender systems: A survey**, *Gao et al*. AI Open 2021. \[[Paper](https://doi.org/10.1016/j.aiopen.2021.06.002)\]
4. **Open-domain clarification question generation without question examples**, *White et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2110.09779)\]
5. **Ask what’s missing and what’s useful: Improving clarification question generation using global knowledge**, *Majumder et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2104.06828)\]
6. **Diverse and specific clarification question generation with keywords**, *Zhang et al*. arXiv 2021. \[[Paper](https://arxiv.org/abs/2104.10317)\]
7. **Conversational vs traditional: Comparing search behavior and outcome in legal case retrieval**, *Liu et al*. SIGIR 2021. \[[Paper](https://doi.org/10.1145/3404835.3463064)\]
8. **Learning to execute actions or ask clarification questions**, *Shi et al*. arXiv 2022. \[[Paper](https://doi.org/10.48550/arXiv.2204.08373)\]
9. **Generating clarifying questions for query refinement in source code search**, *Eberhart et al*. arXiv 2022. \[[Paper](https://arxiv.org/abs/2201.09974)\]
10. **Interactive query clarification and refinement via user simulation**, *Erbacher et al*. arXiv 2022. \[[Paper](https://doi.org/10.48550/arXiv.2205.15918)\]
11. **Query generation and buffer mechanism: Towards a better conversational agent for legal case retrieval**, *Liu et al*. Inf. Process. Manag. 2022. \[[Paper](https://doi.org/10.1016/j.ipm.2022.103051)\]
12. **Leveraging large language models in conversational recommender systems**, *Friedman et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2305.07961)\]
13. **Rethinking the evaluation for conversational recommendation in the era of large language models**, *Wang et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2305.13112)\]
14. **Leveraging event schema to ask clarifying questions for conversational legal case retrieval**, *Liu et al*. CIKM 2023. \[[Paper](https://doi.org/10.1145/3583780.3614953)\]
15. **Python code generation by asking clarification questions**, *Li et al*. ACL 2023. \[[Paper](https://doi.org/10.18653/v1/2023.acl-long.799)\]
16. **Clarifying questions in math information retrieval**, *Mansouri et al*. ICTIR 2023. \[[Paper](https://doi.org/10.1145/3578337.3605123)\]
17. **Learning to ask clarification questions with spatial reasoning**, *Deng et al*. SIGIR 2023. \[[Paper](https://doi.org/10.1145/3539618.3592009)\]
18. **Clarifydelphi: Reinforced clarification questions with defeasibility rewards for social and moral situations**, *Pyatkin et al*. ACL 2023. \[[Paper](https://doi.org/10.18653/v1/2023.acl-long.630)\]
19. **Towards asking clarification questions for information seeking on task-oriented dialogues**, *Feng et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2305.13690)\]
20. **Asking the right question at the right time: Human and model uncertainty guidance to ask clarification questions**, *Testoni et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2402.06509)\]

#### Search Clarification with LLMs

1. **Zero-shot clarifying question generation for conversational search**, *Wang et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2301.12660)\]
2. **An in-depth investigation of user response simulation for conversational search**, *Wang et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2304.07944)\]
3. **A comparative study of training objectives for clarification facet generation**, *Ni et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2310.00703)\]
4. **Clarifygpt: Empowering llm-based code generation with intention clarification**, *Mu et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2310.10996)\]
5. **Eliciting human preferences with language models**, *Tamkin et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2310.11589)\]
6. **Rephrase and respond: Let large language models ask better questions for themselves**, *Deng et al*. arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2311.04205)\]
7. **Generating multi-turn clarification for web information seeking**, *Zhao et al*. WWW 2024. \[[Paper](https://doi.org/10.1145/3589334.3645712)\]
8. **Enhanced facet generation with LLM editing**, *Lee et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2403.16345)\]
9. **Mining exploratory queries for conversational search**, *Liu et al*. WWW 2024. \[[Paper](https://doi.org/10.1145/3589334.3645424)\]
10. **Star-gate: Teaching language models to ask clarifying questions**, *Andukuri et al*. arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2403.19154)\]

### Conversational Retrieval
#### Conversation Modeling
#### Context Denoising
#### Data Augmentation
#### Interpretation in Conversational Dense Retrieval
#### Re-ranking in Conversational Search

### Generation in Conversational Search
#### Utilization of Historical Search Results
#### Context Dependency Modeling
#### Conversational Knowledge Attribution

### Domain-specific and User-centric Conversational Search
#### Domain-specific Conversational Search
#### User-centric Conversational Search

### BENCHMARK AND EVALUATION
#### Retrieval-based Evaluation

1. **Evaluating the Cranfield Paradigm for Conversational Search Systems**, *Fu et al.* ICTIR 2022. \[[Paper](https://doi.org/10.1145/3539813.3545126)\]
2. **Ditch the Gold Standard: Re-evaluating Conversational Question Answering**, *Li et al.* ACL 2022. \[[Paper](https://arxiv.org/abs/2112.08812)\]
3. **Towards a more Robust Evaluation for Conversational Question Answering**, *Siblini et al.* ACL 2021. \[[Paper](https://doi.org/10.18653/v1/2021.acl-short.130)\]
4. **Studying the Effectiveness of Conversational Search Refinement Through User Simulation**, *Salle et al.* ECIR 2021. \[[Paper](https://doi.org/10.1007/978-3-030-72113-8\_39)\]
5. **How Am {I} Doing?: Evaluating Conversational Search Systems Offline**, *Lipani et al.* TOIS 2022. \[[Paper](https://doi.org/10.1145/3451160)\]
6. **Simulating and Modeling the Risk of Conversational Search**, *Wang et al.* TOIS 2022. \[[Paper](https://doi.org/10.1145/3507357)\]
7. **An In-depth Investigation of User Response Simulation for Conversational Search**, *Wang et al.* arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2304.07944)\]
8. **Exploiting Simulated User Feedback for Conversational Search: Ranking**, *Owoicho et al.* SIGIR 2023. \[[Paper](https://doi.org/10.48550/arXiv.2304.13874)\]
9. **Leveraging User Simulation to Develop and Evaluate Conversational Information Access Agents**, *Bernard et al.* arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2312.08041)\]
10. **Evaluating Mixed-initiative Conversational Search Systems via User Simulation**, *Sekulic et al.* arXiv 2022. \[[Paper](https://doi.org/10.48550/arXiv.2204.08046)\]
11. **Analysing Mixed Initiatives and Search Strategies during Conversational Search**, *Aliannejadi et al.* arXiv 2021. \[[Paper](https://arxiv.org/abs/2109.05955)\]
12. **Evaluating Mixed-initiative Conversational Search Systems via User Simulation**, *Sekulic et al.* arXiv 2022. \[[Paper](https://doi.org/10.48550/arXiv.2204.08046)\]
13. **System Initiative Prediction for Multi-turn Conversational Information Seeking**, *Meng et al.* CIKM 2023. \[[Paper](https://doi.org/10.1145/3583780.3615070)\]
14. **Priming and Actions: An Analysis in Conversational Search Systems**, *Fu et al.* SIGIR 2023. \[[Paper](https://doi.org/10.1145/3539618.3592041)\]
    
#### Generation-based Evaluation

1. **How Easily do Irrelevant Inputs Skew the Responses of Large Language Models?**, *Ye et al.* arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2404.03302)\]
2. **Towards Filling the Gap in Conversational Search: From Passage Retrieval to Conversational Response Generation**, *Lajewska et al.* arXiv 2023. \[[Paper](https://doi.org/10.48550/arXiv.2308.08911)\]
3. **Evaluating Retrieval Quality in Retrieval-Augmented Generation**, *Salemi et al.* SIGIR 2024. \[[Paper](https://arxiv.org/abs/2404.13781)\]
4. **The Power of Noise: Redefining Retrieval for {RAG} Systems**, *Cuconasu et al.* arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2401.14887)\]
5. **Evaluating the Retrieval Component in LLM-Based Question Answering Systems**, *Alinejad et al.* arXiv 2024. \[[Paper](https://doi.org/10.48550/arXiv.2406.06458)\]


#### User-based Evaluation
