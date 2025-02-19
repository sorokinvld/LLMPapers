# Resources on ChatGPT and Large Language Models
Collection of  papers and related works for Large Language Models (ChatGPT, GPT-3, Codex etc.).
## Contributors
This repository is contributed by the following contributors.
- **Organizers**: [Guilin Qi (漆桂林)](https://cse.seu.edu.cn/2019/0103/c23024a257135/page.htm), [Xiaofang Qi (戚晓芳)](https://cse.seu.edu.cn/2019/0103/c23024a257134/page.htm)
- **Paper Collectors**: Zafar Ali, [Sheng Bi (毕胜)](https://github.com/bisheng), [Yongrui Chen (陈永锐)](https://github.com/Bahuia), Zizhuo Chen (陈孜卓), [Xinbang Dai (戴鑫邦)](https://github.com/OBriennnnn), Huan Gao (高桓), [Nan Hu (胡楠)](https://github.com/HuuuNan), Shilong Hu (胡世龙), [Jingqi Kang (康婧淇)](https://github.com/JingqiKang), [Jiaqi Li (李嘉琦)](https://github.com/aoluming), [Dehai Min (闵德海)](https://github.com/ZhishanQ), Yiming Tan (谭亦鸣), [Tongtong Wu (吴桐桐)](http://wutong8023.site/), [Songlin Zhai (翟松林)](https://github.com/SonglinZhai), [Yuxin Zhang (张裕欣)](https://github.com/Zzyx1996)
- **Maintainers**: [Runzhe Wang (王润哲)](https://github.com/sid0527), [Shenyu Zhang (张沈昱)](https://github.com/ZSY-SZ) 

The automation script of this repo is powered by [Auto-Bibfile](https://github.com/wutong8023/Auto-Bibfile.git). If you'd like to commit to this repo, please modify [bibtex.bib](https://github.com/KSESEU/LLMPapers/blob/main/bibtex.bib) or [related_works.json](https://github.com/KSESEU/LLMPapers/blob/main/related_works.json) and re-generate [README.md](https://github.com/KSESEU/LLMPapers/blob/main/README.md) using `python scripts/run.py`.



## Papers

### Outline 
- [<img src=https://img.shields.io/badge/Evaluation-23-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#evaluation)
- [<img src=https://img.shields.io/badge/Survey-21-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#survey)
- [<img src=https://img.shields.io/badge/In--Context_Learning-26-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#in-context-learning)
- [<img src=https://img.shields.io/badge/Instruction_Tuning-8-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#instruction-tuning)
- [<img src=https://img.shields.io/badge/RLHF-17-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#rlhf)
- [<img src=https://img.shields.io/badge/Pre--Training_Techniques-19-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#pre-training-techniques)
  - [<img src=https://img.shields.io/badge/Mixtures_of_Experts-4-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#mixtures-of-experts)
- [<img src=https://img.shields.io/badge/Knowledge_Enhanced-21-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#knowledge-enhanced)
- [<img src=https://img.shields.io/badge/Knowledge_Distillation-23-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#knowledge-distillation)
- [<img src=https://img.shields.io/badge/Knowledge_Generation-9-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#knowledge-generation)
- [<img src=https://img.shields.io/badge/Knowledge_Editing-7-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#knowledge-editing)
- [<img src=https://img.shields.io/badge/Reasoning-60-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#reasoning)
  - [<img src=https://img.shields.io/badge/Chain_of_Thought-27-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#chain-of-thought)
  - [<img src=https://img.shields.io/badge/Multi--Step_Reasoning-3-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#multi-step-reasoning)
  - [<img src=https://img.shields.io/badge/Arithmetic_Reasoning-4-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#arithmetic-reasoning)
  - [<img src=https://img.shields.io/badge/Symbolic_Reasoning-5-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#symbolic-reasoning)
- [<img src=https://img.shields.io/badge/Federated_Learning-14-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#federated-learning)
- [<img src=https://img.shields.io/badge/Distributed_AI-9-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#distributed-ai)
- [<img src=https://img.shields.io/badge/Selective_Annotation-2-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#selective-annotation)
- [<img src=https://img.shields.io/badge/Code_Generation-41-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#code-generation)
  - [<img src=https://img.shields.io/badge/Code_Representation-5-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#code-representation)
  - [<img src=https://img.shields.io/badge/Code_Fixing-8-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#code-fixing)
  - [<img src=https://img.shields.io/badge/Code_Review-5-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#code-review)
- [<img src=https://img.shields.io/badge/Software_Engineering-5-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#software-engineering)
- [<img src=https://img.shields.io/badge/AIGC-78-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#aigc)
  - [<img src=https://img.shields.io/badge/Controllable_Text_Generation-9-deepskyblue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#controllable-text-generation)
- [<img src=https://img.shields.io/badge/Continual_Learning-42-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#continual-learning)
- [<img src=https://img.shields.io/badge/Prompt_Engineering-30-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#prompt-engineering)
- [<img src=https://img.shields.io/badge/Natural_Language_Understanding-8-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#natural-language-understanding)
- [<img src=https://img.shields.io/badge/Multimodal-21-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#multimodal)
- [<img src=https://img.shields.io/badge/Multilingual-1-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#multilingual)
- [<img src=https://img.shields.io/badge/Reliability-5-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#reliability)
- [<img src=https://img.shields.io/badge/Robustness-2-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#robustness)
- [<img src=https://img.shields.io/badge/Dialogue_System-15-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#dialogue-system)
- [<img src=https://img.shields.io/badge/Recommender_System-7-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#recommender-system)
- [<img src=https://img.shields.io/badge/Event_Extraction-6-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#event-extraction)
- [<img src=https://img.shields.io/badge/Event_Relation_Extraction-6-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#event-relation-extraction)
- [<img src=https://img.shields.io/badge/Data_Argumentation-4-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#data-argumentation)
- [<img src=https://img.shields.io/badge/Data_Annotation-2-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#data-annotation)
- [<img src=https://img.shields.io/badge/Information_Extraction-4-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#information-extraction)
- [<img src=https://img.shields.io/badge/Domain_Adaptive-3-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#domain-adaptive)
- [<img src=https://img.shields.io/badge/Question_Answering-6-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#question-answering)
- [<img src=https://img.shields.io/badge/Application-3-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#application)
- [<img src=https://img.shields.io/badge/Meta_Learning-2-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#meta-learning)
- [<img src=https://img.shields.io/badge/Generalizability-3-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#generalizability)
- [<img src=https://img.shields.io/badge/Language_Model_as_Knowledge_Base-6-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#language-model-as-knowledge-base)
- [<img src=https://img.shields.io/badge/Retrieval--Augmented_Language_Model-11-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#retrieval-augmented-language-model)
- [<img src=https://img.shields.io/badge/Quality-1-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#quality)
- [<img src=https://img.shields.io/badge/Interpretability/Explainability-3-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#interpretability/explainability)
- [<img src=https://img.shields.io/badge/Data_Generation-3-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#data-generation)
- [<img src=https://img.shields.io/badge/Others-6-blue style="zoom:100%; vertical-align: middle">](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./README.md#others)
### Hyperlinks 
- [[Overview]](https://github.com/KSESEU/LLMPapers/blob/main/README.md) -- [Homepage](https://github.com/KSESEU/LLMPapers/blob/main/README.md)
-  -- [Summary](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/./)
-  -- [Author](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/author)
-  -- [Techniques](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/techniques)
-  -- [Published Time](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/time)
-  -- [Published Venue](https://github.com/KSESEU/LLMPapers/blob/main/taxonomy/venue)

### Evaluation

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.04023) [**A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning,
Hallucination, and Interactivity**](https://doi.org/10.48550/arXiv.2302.04023),<br> by *Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji et al.*
<br>``
本文提出了一个使用公开数据集定量评估交互式LLM（如ChatGPT）的框架。我们使用涵盖8个不同的常见NLP应用任务的21个数据集对ChatGPT进行了广泛的技术评估。我们基于这些数据集和一个新设计的多模态数据集评估了ChatGPT的多任务、多语言和多模态方面。
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2302.06476) [**Is ChatGPT a General-Purpose Natural Language Processing Task Solver?**](https://arxiv.org/abs/2302.06476),<br> by *Qin, Chengwei, Zhang, Aston, Zhang, Zhuosheng, Chen, Jiaao, Yasunaga, Michihiro and Yang, Diyi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.06466) [**ChatGPT versus Traditional Question Answering for Knowledge Graphs:
Current Status and Future Directions Towards Knowledge Graph Chatbots**](https://doi.org/10.48550/arXiv.2302.06466),<br> by *Reham Omar, Omij Mangukiya, Panos Kalnis and Essam Mansour*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.13867) [**Mathematical Capabilities of ChatGPT**](https://doi.org/10.48550/arXiv.2301.13867),<br> by *Simon Frieder, Luca Pinchetti, Ryan-Rhys Griffiths, Tommaso Salvatori, Thomas Lukasiewicz, Philipp Christian Petersen, Alexis Chevalier and Julius Berner*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.08081) [**Exploring the Limits of ChatGPT for Query or Aspect-based Text Summarization**](https://doi.org/10.48550/arXiv.2302.08081),<br> by *Xianjun Yang, Yan Li, Xinlu Zhang, Haifeng Chen and Wei Cheng*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.12095) [**On the Robustness of ChatGPT: An Adversarial and Out-of-distribution
Perspective**](https://doi.org/10.48550/arXiv.2302.12095),<br> by *Jindong Wang, Xixu Hu, Wenxin Hou, Hao Chen, Runkai Zheng, Yidong Wang, Linyi Yang, Haojun Huang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.04655) [**ChatGPT is not all you need. A State of the Art Review of large
Generative AI models**](https://doi.org/10.48550/arXiv.2301.04655),<br> by *Roberto Gozalo-Brizuela and Eduardo C. Garrido-Merch\'an*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2302.10198) [**Can ChatGPT Understand Too? A Comparative Study on ChatGPT and Fine-tuned
BERT**](https://arxiv.org/abs/2302.10198),<br> by *Qihuang Zhong, Liang Ding, Juhua Liu, Bo Du and Dacheng Tao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.07992) [**Evaluation of ChatGPT as a Question Answering System for Answering
Complex Questions**](https://doi.org/10.48550/arXiv.2303.07992),<br> by *Yiming Tan, Dehai Min, Yu Li, Wenbo Li, Nan Hu, Yongrui Chen and Guilin Qi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.09110) [**Holistic Evaluation of Language Models**](https://doi.org/10.48550/arXiv.2211.09110),<br> by *Percy Liang, Rishi Bommasani, Tony Lee, Dimitris Tsipras, Dilara Soylu, Michihiro Yasunaga, Yian Zhang, Deepak Narayanan et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2204.00498) [**Evaluating the Text-to-SQL Capabilities of Large Language Models**](https://doi.org/10.48550/arXiv.2204.00498),<br> by *Nitarshan Rajkumar, Raymond Li and Dzmitry Bahdanau*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.coling-1.491) [**Are Visual-Linguistic Models Commonsense Knowledge Bases?**](https://aclanthology.org/2022.coling-1.491),<br> by *Hsiu-Yu Yang and Carina Silberer*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10529) [**Is GPT-3 a Psychopath? Evaluating Large Language Models from a Psychological
Perspective**](https://doi.org/10.48550/arXiv.2212.10529),<br> by *Xingxuan Li, Yutong Li, Linlin Liu, Lidong Bing and Shafiq R. Joty*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.132) [**GeoMLAMA: Geo-Diverse Commonsense Probing on Multilingual Pre-Trained
Language Models**](https://aclanthology.org/2022.emnlp-main.132),<br> by *Da Yin, Hritik Bansal, Masoud Monajatipoor, Liunian Harold Li and Kai-Wei Chang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.653) [**RobustLR: A Diagnostic Benchmark for Evaluating Logical Robustness
of Deductive Reasoners**](https://aclanthology.org/2022.emnlp-main.653),<br> by *Soumya Sanyal, Zeyi Liao and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.03374) [**Evaluating Large Language Models Trained on Code**](https://arxiv.org/abs/2107.03374),<br> by *Mark Chen, Jerry Tworek, Heewoo Jun, Qiming Yuan, Henrique Pond\'e de Oliveira Pinto, Jared Kaplan, Harrison Edwards, Yuri Burda et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.36) [**GLGE: A New General Language Generation Evaluation Benchmark**](https://doi.org/10.18653/v1/2021.findings-acl.36),<br> by *Dayiheng Liu, Yu Yan, Yeyun Gong, Weizhen Qi, Hang Zhang, Jian Jiao, Weizhu Chen, Jie Fu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2104.05861) [**Evaluating Pre-Trained Models for User Feedback Analysis in Software
Engineering: A Study on Classification of App-Reviews**](https://arxiv.org/abs/2104.05861),<br> by *Mohammad Abdul Hadi and Fatemeh H. Fard*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.322) [**Do Language Models Perform Generalizable Commonsense Inference?**](https://doi.org/10.18653/v1/2021.findings-acl.322), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/wangpf3/LM-for-CommonsenseInference)<br> by *Peifeng Wang, Filip Ilievski, Muhao Chen and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.598) [**RICA: Evaluating Robust Inference Capabilities Based on Commonsense
Axioms**](https://doi.org/10.18653/v1/2021.emnlp-main.598),<br> by *Pei Zhou, Rahul Khanna, Seyeon Lee, Bill Yuchen Lin, Daniel Ho, Jay Pujara and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.14799) [**Evaluation of Text Generation: A Survey**](https://arxiv.org/abs/2006.14799),<br> by *Asli Celikyilmaz, Elizabeth Clark and Jianfeng Gao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2007.15780) [**Neural Language Generation: Formulation, Methods, and Evaluation**](https://arxiv.org/abs/2007.15780),<br> by *Cristina Garbacea and Qiaozhu Mei*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=SkeHuCVFDr) [**BERTScore: Evaluating Text Generation with BERT**](https://openreview.net/forum?id=SkeHuCVFDr),<br> by *Tianyi Zhang, Varsha Kishore, Felix Wu, Kilian Q. Weinberger and Yoav Artzi*
<br><br>
### Survey

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.00234) [**A Survey for In-context Learning**](https://doi.org/10.48550/arXiv.2301.00234),<br> by *Qingxiu Dong, Lei Li, Damai Dai, Ce Zheng, Zhiyong Wu, Baobao Chang, Xu Sun, Jingjing Xu et al.*
<br>``
This paper surveys and summarizes the progress and challenges of ICL, including ICL's formal definition, correlation to related studies, advanced techniques (training strategies, related analysis) and potential directions.
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.09419) [**A Comprehensive Survey on Pretrained Foundation Models: A History
from BERT to ChatGPT**](https://doi.org/10.48550/arXiv.2302.09419),<br> by *Ce Zhou, Qian Li, Chen Li, Jun Yu, Yixin Liu, Guangjing Wang, Kai Zhang, Cheng Ji et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.09051) [**Complex QA and language models hybrid architectures, Survey**](https://doi.org/10.48550/arXiv.2302.09051),<br> by *Xavier Daull, Patrice Bellot, Emmanuel Bruno, Vincent Martin and Elisabeth Murisasco*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.07842) [**Augmented Language Models: a Survey**](https://doi.org/10.48550/arXiv.2302.07842),<br> by *Gr\'egoire Mialon, Roberto Dess\`\i, Maria Lomeli, Christoforos Nalmpantis, Ramakanth Pasunuru, Roberta Raileanu, Baptiste Rozi\`ere, Timo Schick et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.07616) [**The Life Cycle of Knowledge in Big Language Models: A Survey**](https://doi.org/10.48550/arXiv.2303.07616),<br> by *Boxi Cao, Hongyu Lin, Xianpei Han and Le Sun*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09420) [**When Neural Model Meets NL2Code: A Survey**](https://doi.org/10.48550/arXiv.2212.09420),<br> by *Daoguang Zan, Bei Chen, Fengji Zhang, Dianjie Lu, Bingchao Wu, Bei Guan, Yongji Wang and Jian-Guang Lou*
<br><br>
- [<img src=https://img.shields.io/badge/TKDE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.13428) [**A Survey on Knowledge-Enhanced Pre-trained Language Models**](https://doi.org/10.48550/arXiv.2212.13428),<br> by *Chaoqi Zhen, Yanlei Shang, Xiangyu Liu, Yifei Li, Yong Chen and Dell Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/T--PAMI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/TPAMI.2021.3057446) [**A Continual Learning Survey: Defying Forgetting in Classification
Tasks**](https://doi.org/10.1109/TPAMI.2021.3057446),<br> by *Matthias De Lange, Rahaf Aljundi, Marc Masana, Sarah Parisot, Xu Jia, Ales Leonardis, Gregory G. Slabaugh and Tinne Tuytelaars*
<br><br>
- [<img src=https://img.shields.io/badge/JKSUCIS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1016/j.jksuci.2020.04.001) [**The survey: Text generation models in deep learning**](https://doi.org/10.1016/j.jksuci.2020.04.001),<br> by *Touseef Iqbal and Shaima Qureshi*
<br><br>
- [<img src=https://img.shields.io/badge/KIS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/s10115-022-01664-x) [**From distributed machine learning to federated learning: a survey**](https://doi.org/10.1007/s10115-022-01664-x),<br> by *Ji Liu, Jizhou Huang, Yang Zhou, Xuhong Li, Shilei Ji, Haoyi Xiong and Dejing Dou*
<br><br>
- [<img src=https://img.shields.io/badge/IJCAI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.24963/ijcai.2022/775) [**Deep Learning Meets Software Engineering: A Survey on Pre-Trained
Models of Source Code**](https://doi.org/10.24963/ijcai.2022/775),<br> by *Changan Niu, Chuanyi Li, Bin Luo and Vincent Ng*
<br><br>
- [<img src=https://img.shields.io/badge/TKDE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/TKDE.2020.3028705) [**A Survey on Knowledge Graph-Based Recommender Systems**](https://doi.org/10.1109/TKDE.2020.3028705),<br> by *Qingyu Guo, Fuzhen Zhuang, Chuan Qin, Hengshu Zhu, Xing Xie, Hui Xiong and Qing He*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09252) [**Mind the Knowledge Gap: A Survey of Knowledge-enhanced Dialogue
Systems**](https://doi.org/10.48550/arXiv.2212.09252),<br> by *Sagi Shaier, Lawrence Hunter and Katharina Kann*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10403) [**Towards Reasoning in Large Language Models: A Survey**](https://doi.org/10.48550/arXiv.2212.10403),<br> by *Jie Huang and Kevin Chen-Chuan Chang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09597) [**Reasoning with Language Model Prompting: A Survey**](https://doi.org/10.48550/arXiv.2212.09597),<br> by *Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2202.01110) [**A Survey on Retrieval-Augmented Text Generation**](https://arxiv.org/abs/2202.01110),<br> by *Huayang Li, Yixuan Su, Deng Cai, Yan Wang and Lemao Liu*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/21496) [**Commonsense Knowledge Reasoning and Generation with Pre-trained Language
Models: A Survey**](https://ojs.aaai.org/index.php/AAAI/article/view/21496),<br> by *Prajjwal Bhargava and Vincent Ng*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2101.09459) [**Advances and Challenges in Conversational Recommender Systems: A
Survey**](https://arxiv.org/abs/2101.09459),<br> by *Chongming Gao, Wenqiang Lei, Xiangnan He, Maarten de Rijke and Tat-Seng Chua*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2105.04387) [**Recent Advances in Deep Learning Based Dialogue Systems: A Systematic
Survey**](https://arxiv.org/abs/2105.04387),<br> by *Jinjie Ni, Tom Young, Vlad Pandelea, Fuzhao Xue, Vinay Adiga and Erik Cambria*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.81) [**Relational World Knowledge Representation in Contextual Language Models:
A Review**](https://doi.org/10.18653/v1/2021.emnlp-main.81),<br> by *Tara Safavi and Danai Koutra*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.14799) [**Evaluation of Text Generation: A Survey**](https://arxiv.org/abs/2006.14799),<br> by *Asli Celikyilmaz, Elizabeth Clark and Jianfeng Gao*
<br><br>
### In-Context Learning

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.00234) [**A Survey for In-context Learning**](https://doi.org/10.48550/arXiv.2301.00234),<br> by *Qingxiu Dong, Lei Li, Damai Dai, Ce Zheng, Zhiyong Wu, Baobao Chang, Xu Sun, Jingjing Xu et al.*
<br>``
This paper surveys and summarizes the progress and challenges of ICL, including ICL's formal definition, correlation to related studies, advanced techniques (training strategies, related analysis) and potential directions.
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.04813) [**Explanation Selection Using Unlabeled Data for In-Context Learning**](https://doi.org/10.48550/arXiv.2302.04813),<br> by *Xi Ye and Greg Durrett*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.04931) [**In-Context Learning with Many Demonstration Examples**](https://doi.org/10.48550/arXiv.2302.04931),<br> by *Mukai Li, Shansan Gong, Jiangtao Feng, Yiheng Xu, Jun Zhang, Zhiyong Wu and Lingpeng Kong*
<br>``
This paper proposes a LM named EvaLM to scale up the sequence length (trained with 8k tokens per batch line). Experiments based on EvaLM prove that in-context learning can achieve higher performance with more demonstrations under many-shot instruction tuning (8k) and further extending the length of instructions (16k) can further improve the upper bound of scaling in-context  learning.
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.11916) [**Large Language Models Are Implicitly Topic Models: Explaining and
Finding Good Demonstrations for In-Context Learning**](https://doi.org/10.48550/arXiv.2301.11916),<br> by *Xinyi Wang, Wanrong Zhu and William Yang Wang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.13539) [**Finding Supporting Examples for In-Context Learning**](https://doi.org/10.48550/arXiv.2302.13539),<br> by *Xiaonan Li and Xipeng Qiu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.07895) [**The Learnability of In-Context Learning**](https://doi.org/10.48550/arXiv.2303.07895),<br> by *Noam Wies, Yoav Levine and Amnon Shashua*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.53) [**Meta-learning via Language Model In-context Tuning**](https://doi.org/10.18653/v1/2022.acl-long.53), [<img src=https://img.shields.io/badge/BERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/N19-1423/) [<img src=https://img.shields.io/badge/DeBERTa-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.03654) [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) <br> by *Yanda Chen, Ruiqi Zhong, Sheng Zha, George Karypis and He He*
<br>``
This paper proposes in-context tuning, which recasts task adaptation and prediction as a simple sequence prediction problem: to form the input sequence,  concatenate the task instruction, labeled in-context examples, and the target input to predict; to meta train the model to learn from in-context examples, finetune a PLM to predict the target label given the input sequence on a collection of tasks (very similar to MetaICL). On LAMA and BinaryClfs, the proposed method outperforms MAML.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.201) [**MetaICL: Learning to Learn In Context**](https://doi.org/10.18653/v1/2022.naacl-main.201), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/facebookresearch/MetaICL) [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) <br> by *Sewon Min, Mike Lewis, Luke Zettlemoyer and Hannaneh Hajishirzi*
<br>``
MetaICL proposes a supervised meta-training framework to enable LMs to more effectively learn a new task in context. In MetaICL, each meta-training example includes several training examples from one task that will be presented together as a single sequence to the LM, and the prediction of the final example is used to calculate the loss.
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.01975) [**Selective Annotation Makes Language Models Better Few-Shot Learners**](https://doi.org/10.48550/arXiv.2209.01975), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/HKUNLP/icl-selective-annotation) [<img src=https://img.shields.io/badge/SBERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/D19-1410/) [<img src=https://img.shields.io/badge/GPT--J-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://huggingface.co/docs/transformers/model_doc/gptj) [<img src=https://img.shields.io/badge/GPT--Neo-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://huggingface.co/docs/transformers/model_doc/gpt_neo) [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) [<img src=https://img.shields.io/badge/Codex-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.03374) [<img src=https://img.shields.io/badge/OPT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2205.01068) <br> by *Hongjin Su, Jungo Kasai, Chen Henry Wu, Weijia Shi, Tianlu Wang, Jiayi Xin, Rui Zhang, Mari Ostendorf et al.*
<br>``
This paper proposes a graph-based selective annotation method named vote-k to
``<br>``
(1) select a pool of examples to annotate from unlabeled data,
``<br>``
(2) retrieve prompts (contexts) from the annotated data pool for in-context learning.
``<br>``
Specifically, the selection method first selects a small set of unlabeled examples iteratively and then labels them to serve as contexts for LLMs to predict the labels of the rest unlabeled data. The method selects the predictions with highest confidence (log probability of generation output) to fill up the selective annotation pool.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.260) [**Improving In-Context Few-Shot Learning via Self-Supervised Training**](https://doi.org/10.18653/v1/2022.naacl-main.260), [<img src=https://img.shields.io/badge/MoE-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.260) <br> by *Mingda Chen, Jingfei Du, Ramakanth Pasunuru, Todor Mihaylov, Srini Iyer, Veselin Stoyanov and Zornitsa Kozareva*
<br>``
This paper proposes to use self-supervision (MLM, NSP, CL, etc.) between pre-training and downstream usage to teach the LM to perform in-context learning. Analysis reveals that:
``<br>``
(1) benefits of self-supervised depends on the amount of training data,
``<br>``
(2) semantic similarity between training and evaluation tasks matters,
``<br>``
(3) adding training objectives without diversity does not help,
``<br>``
(4) model performance improves when choosing similar templates for both self-supervised and downstream tasks,
``<br>``
(5) self-supervised  tasks and human-annotated datasets are complementary,
``<br>``
(6) self-supervised-trained models are better at following task instructions.
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.10782) [**Instruction Induction: From Few Examples to Natural Language Task
Descriptions**](https://doi.org/10.48550/arXiv.2205.10782),<br> by *Or Honovich, Uri Shaham, Samuel R. Bowman and Omer Levy*
<br>``
(1) 探索了利用LLM在几个样本的情况下归纳出任务指令的能力；
``<br>``
(2) 测量两个指标：1. 模型归纳指令与人类归纳的指令对比，2. 利用模型归纳的指令作为prompt进行预测的执行准确率；
``<br>``
(3) 相比于GPT-3，InstructGPT效果更好，理所当然。
``
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.556) [**Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot
Prompt Order Sensitivity**](https://doi.org/10.18653/v1/2022.acl-long.556), [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) <br> by *Yao Lu, Max Bartolo, Alastair Moore, Sebastian Riedel and Pontus Stenetorp*
<br>``
(1) This work demonstrates that few-shot prompts suffer from order sensitivity, in that for the same prompt the order in which samples are provided can make a difference to model performance.
``<br>``
(2) This work introduces a probing method which constructs an artificial development set by language models themselves to alleviate the order sensitivity problem.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.191) [**Learning To Retrieve Prompts for In-Context Learning**](https://doi.org/10.18653/v1/2022.naacl-main.191), [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) [<img src=https://img.shields.io/badge/GPT--Neo-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://huggingface.co/docs/transformers/model_doc/gpt_neo) [<img src=https://img.shields.io/badge/Codex-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.03374) [<img src=https://img.shields.io/badge/GPT--J-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://huggingface.co/docs/transformers/model_doc/gptj) [<img src=https://img.shields.io/badge/SBERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/D19-1410/) [<img src=https://img.shields.io/badge/BERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/N19-1423/) <br> by *Ohad Rubin, Jonathan Herzig and Jonathan Berant*
<br>``
This paper proposes a method to retrieve good contexts for in-context learning. Specifically, the method
``<br>``
(1) uses an unsupervised retriever (BM25/SBERT) to obtain a set of context candidates,
``<br>``
(2) passes the candidates to a scoring model (GPT-Neo/GPT-J/GPT-3/Codex) and select the top/bottom k as positive/negative examples,
``<br>``
(3) uses the examples to train a dense retriever (BERT-based).
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.622) [**Active Example Selection for In-Context Learning**](https://aclanthology.org/2022.emnlp-main.622), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/ChicagoHAI/active-example-selection) [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) <br> by *Yiming Zhang, Shi Feng and Chenhao Tan*
<br>``
(1) This paper revisits the  effect of example selection (re-ordering & calibration) for ICL, observing that a large variance across set of demonstration examples still exists.
``<br>``
(2) This paper applies reinforcement learning (Q-Learning) to optimize example selection by formulating this task as sequential decision-making problem, which is appropriate for example selection from unlabeled datasets. 
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.08082) [**Self-Generated In-Context Learning: Leveraging Auto-regressive Language
Models as a Demonstration Generator**](https://doi.org/10.48550/arXiv.2206.08082),<br> by *Hyuhng Joon Kim, Hyunsoo Cho, Junyeob Kim, Taeuk Kim, Kang Min Yoo and Sang-goo Lee*
<br><br>
- [<img src=https://img.shields.io/badge/ISoLA-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-031-19759-8\_15) [**Measuring Convergence Inertia: Online Learning in Self-adaptive Systems
with Context Shifts**](https://doi.org/10.1007/978-3-031-19759-8\_15),<br> by *Elvin Alberts and Ilias Gerostathopoulos*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=RdJVFCHjUMI) [**An Explanation of In-context Learning as Implicit Bayesian Inference**](https://openreview.net/forum?id=RdJVFCHjUMI),<br> by *Sang Michael Xie, Aditi Raghunathan, Percy Liang and Tengyu Ma*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.759) [**Rethinking the Role of Demonstrations: What Makes In-Context Learning
Work?**](https://aclanthology.org/2022.emnlp-main.759),<br> by *Sewon Min, Xinxi Lyu, Ari Holtzman, Mikel Artetxe, Mike Lewis, Hannaneh Hajishirzi and Luke Zettlemoyer*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.08686) [**The Impact of Symbolic Representations on In-context Learning for
Few-shot Reasoning**](https://doi.org/10.48550/arXiv.2212.08686),<br> by *Hanlin Zhang, Yi-Fan Zhang, Li Erran Li and Eric P. Xing*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.deelio-1.10) [**What Makes Good In-Context Examples for GPT-3?**](https://doi.org/10.18653/v1/2022.deelio-1.10), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/jiachangliu/KATEGPT3) [<img src=https://img.shields.io/badge/RoBERTa-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/1907.11692) [<img src=https://img.shields.io/badge/T5-yellow alt="img" style="zoom:100%; vertical-align: middle" />](http://jmlr.org/papers/v21/20-074.html) [<img src=https://img.shields.io/badge/SBERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/D19-1410/) [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) <br> by *Jiachang Liu, Dinghan Shen, Yizhe Zhang, Bill Dolan, Lawrence Carin and Weizhu Chen*
<br>``
(1) 探索了在in-context learning中什么样的demonstration example可以对GPT-3的效果取得帮助；
``<br>``
(2) 利用roberta对样本进行编码，并计算demonstration与test example的向量距离（欧氏距离），最终发现与test example越相近的demonstration越能取得较好的效果。
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.329) [**Thinking about GPT-3 In-Context Learning for Biomedical IE? Think
Again**](https://aclanthology.org/2022.findings-emnlp.329),<br> by *Bernal Jimenez Gutierrez, Nikolas McNeal, Clayton Washington, You Chen, Lang Li, Huan Sun and Yu Su*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10559) [**Why Can GPT Learn In-Context? Language Models Secretly Perform Gradient
Descent as Meta-Optimizers**](https://doi.org/10.48550/arXiv.2212.10559),<br> by *Damai Dai, Yutao Sun, Li Dong, Yaru Hao, Zhifang Sui and Furu Wei*
<br>``
(1) 与The Dual Form of Neural Networks Revisited结合一起看，可以进一步理解in-context learning，通过与NN线性层对偶形式的类比，可以将ICL流程描述为：1. 基于Transformer的预训练语言模型作为元优化器；2. 通过正向计算，根据示范例子产生元梯度；3. 通过关注，将元梯度应用于原始语言模型，建立一个ICL模型；
``<br>``
(2)与Fine-tune类似，ICL也是在zero-shot learning参数的基础上，提供了一个更新量。
``
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.mlr.press/v162/irie22a.html) [**The Dual Form of Neural Networks Revisited: Connecting Test Time Predictions
to Training Patterns via Spotlights of Attention**](https://proceedings.mlr.press/v162/irie22a.html),<br> by *Kazuki Irie, R\'obert Csord\'as and J\"urgen Schmidhuber*
<br>``
(1) 很有意思的一篇，回顾神经网络（NN）线性层Y=WX（省略偏置b）的原始形式与对偶形式，两种形式完全等价；
``<br>``
(2) 从对偶形式中可以发现，通过反向传播训练的NN线性层的输出主要是该层在训练期间的训练误差信号et的线性组合，其中权重是通过比较测试查询x和每个训练输入计算出来的；进一步可以得出，如果测试时输入的x和训练时的输入是正交的，那么梯度下降所得到的参数更新对于该样本x完全没有影响。
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10375) [**Self-adaptive In-context Learning**](https://doi.org/10.48550/arXiv.2212.10375),<br> by *Zhiyong Wu, Yaoxiang Wang, Jiacheng Ye and Lingpeng Kong*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10378) [**Careful Data Curation Stabilizes In-context Learning**](https://doi.org/10.48550/arXiv.2212.10378),<br> by *Ting-Yun Chang and Robin Jia*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09095) [**Rethinking the Role of Scale for In-Context Learning: An Interpretability-based
Case Study at 66 Billion Scale**](https://doi.org/10.48550/arXiv.2212.09095),<br> by *Hritik Bansal, Karthik Gopalakrishnan, Saket Dingliwal, Sravan Bodapati, Katrin Kirchhoff and Dan Roth*
<br><br>
### Instruction Tuning

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.00093) [**Large Language Models Can Be Easily Distracted by Irrelevant Context**](https://doi.org/10.48550/arXiv.2302.00093),<br> by *Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed H. Chi, Nathanael Sch\"arli and Denny Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.07459) [**The Capacity for Moral Self-Correction in Large Language Models**](https://doi.org/10.48550/arXiv.2302.07459),<br> by *Deep Ganguli, Amanda Askell, Nicholas Schiefer, Thomas I. Liao, Kamile Lukosiute, Anna Chen, Anna Goldie, Azalia Mirhoseini et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=gEZrGCozdqR) [**Finetuned Language Models are Zero-Shot Learners**](https://openreview.net/forum?id=gEZrGCozdqR),<br> by *Jason Wei, Maarten Bosma, Vincent Y. Zhao, Kelvin Guu, Adams Wei Yu, Brian Lester, Nan Du, Andrew M. Dai et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2201.08239) [**LaMDA: Language Models for Dialog Applications**](https://arxiv.org/abs/2201.08239),<br> by *Romal Thoppilan, Daniel De Freitas, Jamie Hall, Noam Shazeer, Apoorv Kulshreshtha, Heng-Tze Cheng, Alicia Jin, Taylor Bos et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.11416) [**Scaling Instruction-Finetuned Language Models**](https://doi.org/10.48550/arXiv.2210.11416),<br> by *Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Eric Li, Xuezhi Wang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.340) [**Super-NaturalInstructions: Generalization via Declarative Instructions
on 1600+ NLP Tasks**](https://aclanthology.org/2022.emnlp-main.340),<br> by *Yizhong Wang, Swaroop Mishra, Pegah Alipoormolabashi, Yeganeh Kordi, Amirreza Mirzaei, Atharva Naik, Arjun Ashok, Arut Selvan Dhanasekaran et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10560) [**Self-Instruct: Aligning Language Model with Self Generated Instructions**](https://doi.org/10.48550/arXiv.2212.10560),<br> by *Yizhong Wang, Yeganeh Kordi, Swaroop Mishra, Alisa Liu, Noah A. Smith, Daniel Khashabi and Hannaneh Hajishirzi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2203.09161) [**How Many Data Samples is an Additional Instruction Worth?**](https://doi.org/10.48550/arXiv.2203.09161),<br> by *Ravsehaj Singh Puri, Swaroop Mishra, Mihir Parmar and Chitta Baral*
<br><br>
### RLHF

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.07459) [**The Capacity for Moral Self-Correction in Large Language Models**](https://doi.org/10.48550/arXiv.2302.07459),<br> by *Deep Ganguli, Amanda Askell, Nicholas Schiefer, Thomas I. Liao, Kamile Lukosiute, Anna Chen, Anna Goldie, Azalia Mirhoseini et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.12192) [**Aligning Text-to-Image Models using Human Feedback**](https://doi.org/10.48550/arXiv.2302.12192),<br> by *Kimin Lee, Hao Liu, Moonkyung Ryu, Olivia Watkins, Yuqing Du, Craig Boutilier, Pieter Abbeel, Mohammad Ghavamzadeh et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2204.05862) [**Training a Helpful and Harmless Assistant with Reinforcement Learning
from Human Feedback**](https://doi.org/10.48550/arXiv.2204.05862),<br> by *Yuntao Bai, Andy Jones, Kamal Ndousse, Amanda Askell, Anna Chen, Nova DasSarma, Dawn Drain, Stanislav Fort et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.01241) [**Is Reinforcement Learning (Not) for Natural Language Processing?:
Benchmarks, Baselines, and Building Blocks for Natural Language Policy
Optimization**](https://doi.org/10.48550/arXiv.2210.01241),<br> by *Rajkumar Ramamurthy, Prithviraj Ammanabrolu, Kiant\'e Brantley, Jack Hessel, Rafet Sifa, Christian Bauckhage, Hannaneh Hajishirzi and Yejin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2203.11147) [**Teaching language models to support answers with verified quotes**](https://doi.org/10.48550/arXiv.2203.11147),<br> by *Jacob Menick, Maja Trebacz, Vladimir Mikulik, John Aslanides, H. Francis Song, Martin Chadwick, Mia Glaese, Susannah Young et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.14375) [**Improving alignment of dialogue agents via targeted human judgements**](https://doi.org/10.48550/arXiv.2209.14375),<br> by *Amelia Glaese, Nat McAleese, Maja Trebacz, John Aslanides, Vlad Firoiu, Timo Ewalds, Maribeth Rauh, Laura Weidinger et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2210.10760) [**Scaling Laws for Reward Model Overoptimization**](https://arxiv.org/abs/2210.10760),<br> by *Gao, Leo, Schulman, John and Hilton, Jacob*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.07858) [**Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors,
and Lessons Learned**](https://doi.org/10.48550/arXiv.2209.07858),<br> by *Deep Ganguli, Liane Lovitt, Jackson Kernion, Amanda Askell, Yuntao Bai, Saurav Kadavath, Ben Mann, Ethan Perez et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2208.02294) [**Dynamic Planning in Open-Ended Dialogue using Reinforcement Learning**](https://doi.org/10.48550/arXiv.2208.02294),<br> by *Deborah Cohen, Moonkyung Ryu, Yinlam Chow, Orgad Keller, Ido Greenberg, Avinatan Hassidim, Michael Fink, Yossi Matias et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2203.02155) [**Training language models to follow instructions with human feedback**](https://doi.org/10.48550/arXiv.2203.02155),<br> by *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal et al.*
<br><br>
- [<img src=https://img.shields.io/badge/IJRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1177/02783649211041652) [**Learning reward functions from diverse sources of human feedback:
Optimally integrating demonstrations and preferences**](https://doi.org/10.1177/02783649211041652),<br> by *Erdem Biyik, Dylan P. Losey, Malayandi Palan, Nicholas C. Landolfi, Gleb Shevchuk and Dorsa Sadigh*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2112.09332) [**WebGPT: Browser-assisted question-answering with human feedback**](https://arxiv.org/abs/2112.09332),<br> by *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2109.10862) [**Recursively Summarizing Books with Human Feedback**](https://arxiv.org/abs/2109.10862),<br> by *Jeff Wu, Long Ouyang, Daniel M. Ziegler, Nisan Stiennon, Ryan Lowe, Jan Leike and Paul F. Christiano*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1f89885d556929e98d3ef9b86448f951-Abstract.html) [**Learning to summarize with human feedback**](https://proceedings.neurips.cc/paper/2020/hash/1f89885d556929e98d3ef9b86448f951-Abstract.html),<br> by *Nisan Stiennon, Long Ouyang, Jeffrey Wu, Daniel M. Ziegler, Ryan Lowe, Chelsea Voss, Alec Radford, Dario Amodei et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.28) [**Dialogue Response Ranking Training with Large-Scale Human Feedback
Data**](https://doi.org/10.18653/v1/2020.emnlp-main.28),<br> by *Xiang Gao, Yizhe Zhang, Michel Galley, Chris Brockett and Bill Dolan*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1909.08593) [**Fine-Tuning Language Models from Human Preferences**](http://arxiv.org/abs/1909.08593),<br> by *Daniel M. Ziegler, Nisan Stiennon, Jeffrey Wu, Tom B. Brown, Alec Radford, Dario Amodei, Paul F. Christiano and Geoffrey Irving*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2017-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2017/hash/d5e2c0adad503c91f91df240d0cd4e49-Abstract.html) [**Deep Reinforcement Learning from Human Preferences**](https://proceedings.neurips.cc/paper/2017/hash/d5e2c0adad503c91f91df240d0cd4e49-Abstract.html),<br> by *Paul F. Christiano, Jan Leike, Tom B. Brown, Miljan Martic, Shane Legg and Dario Amodei*
<br><br>
### Pre-Training Techniques

- [<img src=https://img.shields.io/badge/OpenAI-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) [**GPT-4 Technical Report**](https://cdn.openai.com/papers/gpt-4.pdf), [<img src=https://img.shields.io/badge/GPT--4-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) <br> by *OpenAI*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4-system-card.pdf) [**GPT-4 System Card**](https://cdn.openai.com/papers/gpt-4-system-card.pdf), [<img src=https://img.shields.io/badge/GPT--4-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) <br> by *OpenAI*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.01068) [**OPT: Open Pre-trained Transformer Language Models**](https://doi.org/10.48550/arXiv.2205.01068), [<img src=https://img.shields.io/badge/OPT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2205.01068) <br> by *Susan Zhang, Stephen Roller, Naman Goyal, Mikel Artetxe, Moya Chen, Shuohui Chen, Christopher Dewan, Mona T. Diab et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.10372) [**WeLM: A Well-Read Pre-trained Language Model for Chinese**](https://doi.org/10.48550/arXiv.2209.10372), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://welm.weixin.qq.com/docs/api/)<br> by *Hui Su, Xiao Zhou, Houjin Yu, Yuwen Chen, Zilin Zhu, Yang Yu and Jie Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) [**Language Models are Few-Shot Learners**](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html), [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) <br> by *Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=r1xMH1BtvB) [**ELECTRA: Pre-training Text Encoders as Discriminators Rather Than
Generators**](https://openreview.net/forum?id=r1xMH1BtvB), [<img src=https://img.shields.io/badge/ELECTRA-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=r1xMH1BtvB) <br> by *Kevin Clark, Minh-Thang Luong, Quoc V. Le and Christopher D. Manning*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.58) [**Revisiting Pre-Trained Models for Chinese Natural Language Processing**](https://doi.org/10.18653/v1/2020.findings-emnlp.58),<br> by *Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang and Guoping Hu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.03654) [**DeBERTa: Decoding-enhanced BERT with Disentangled Attention**](https://arxiv.org/abs/2006.03654), [<img src=https://img.shields.io/badge/DeBERTa-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.03654) <br> by *Pengcheng He, Xiaodong Liu, Jianfeng Gao and Weizhu Chen*
<br><br>
- [<img src=https://img.shields.io/badge/JMLR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://jmlr.org/papers/v21/20-074.html) [**Exploring the Limits of Transfer Learning with a Unified Text-to-Text
Transformer**](http://jmlr.org/papers/v21/20-074.html), [<img src=https://img.shields.io/badge/T5-yellow alt="img" style="zoom:100%; vertical-align: middle" />](http://jmlr.org/papers/v21/20-074.html) <br> by *Colin Raffel, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li et al.*
<br><br>
- [<img src=https://img.shields.io/badge/TACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1162/tacl\_a\_00349) [**A Primer in BERTology: What We Know About How BERT Works**](https://doi.org/10.1162/tacl\_a\_00349),<br> by *Anna Rogers, Olga Kovaleva and Anna Rumshisky*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) [**Language Models are Unsupervised Multitask Learners**](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf), [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) <br> by *Radford, Alec, Wu, Jeffrey, Child, Rewon, Luan, David, Amodei, Dario and Sutskever, Ilya*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/n19-1423) [**BERT: Pre-training of Deep Bidirectional Transformers for Language
Understanding**](https://doi.org/10.18653/v1/n19-1423), [<img src=https://img.shields.io/badge/BERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/N19-1423/) <br> by *Jacob Devlin, Ming-Wei Chang, Kenton Lee and Kristina Toutanova*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1907.11692) [**RoBERTa: A Robustly Optimized BERT Pretraining Approach**](http://arxiv.org/abs/1907.11692), [<img src=https://img.shields.io/badge/RoBERTa-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/1907.11692) <br> by *Yinhan Liu, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/D19-1410) [**Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks**](https://doi.org/10.18653/v1/D19-1410), [<img src=https://img.shields.io/badge/SBERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/D19-1410/) <br> by *Nils Reimers and Iryna Gurevych*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2018-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) [**Improving language understanding by generative pre-training**](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf), [<img src=https://img.shields.io/badge/GPT--1-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) <br> by *Radford, Alec, Narasimhan, Karthik, Salimans, Tim, Sutskever, Ilya and others*
<br><br>
#### Mixtures of Experts

- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.804) [**Efficient Large Scale Language Modeling with Mixtures of Experts**](https://aclanthology.org/2022.emnlp-main.804), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/facebookresearch/fairseq/tree/main/examples/moe_lm) [<img src=https://img.shields.io/badge/MoE-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.804) <br> by *Mikel Artetxe, Shruti Bhosale, Naman Goyal, Todor Mihaylov, Myle Ott, Sam Shleifer, Xi Victoria Lin, Jingfei Du et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.116) [**MoEBERT: from BERT to Mixture-of-Experts via Importance-Guided Adaptation**](https://doi.org/10.18653/v1/2022.naacl-main.116),<br> by *Simiao Zuo, Qingru Zhang, Chen Liang, Pengcheng He, Tuo Zhao and Weizhu Chen*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.05055) [**Sparse Upcycling: Training Mixture-of-Experts from Dense Checkpoints**](https://doi.org/10.48550/arXiv.2212.05055),<br> by *Aran Komatsuzaki, Joan Puigcerver, James Lee-Thorp, Carlos Riquelme Ruiz, Basil Mustafa, Joshua Ainslie, Yi Tay, Mostafa Dehghani et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.03885) [**Meta-DMoE: Adapting to Domain Shift by Meta-Distillation from Mixture-of-Experts**](https://doi.org/10.48550/arXiv.2210.03885),<br> by *Tao Zhong, Zhixiang Chi, Li Gu, Yang Wang, Yuanhao Yu and Jin Tang*
<br><br>
### Knowledge Enhanced

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.02093) [**Knowledge-enhanced Neural Machine Reasoning: A Review**](https://doi.org/10.48550/arXiv.2302.02093),<br> by *Tanmoy Chowdhury, Chen Ling, Xuchao Zhang, Xujiang Zhao, Guangji Bai, Jian Pei, Haifeng Chen and Liang Zhao*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.09338) [**Deep Bidirectional Language-Knowledge Graph Pretraining**](https://doi.org/10.48550/arXiv.2210.09338),<br> by *Michihiro Yasunaga, Antoine Bosselut, Hongyu Ren, Xikun Zhang, Christopher D. Manning, Percy Liang and Jure Leskovec*
<br><br>
- [<img src=https://img.shields.io/badge/TKDE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.13428) [**A Survey on Knowledge-Enhanced Pre-trained Language Models**](https://doi.org/10.48550/arXiv.2212.13428),<br> by *Chaoqi Zhen, Yanlei Shang, Xiangyu Liu, Yifei Li, Yong Chen and Dell Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/FCST-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.3778/j.issn.1673-9418.2108105) [**Review of Knowledge-Enhanced Pre-trained Language Models**](https://doi.org/10.3778/j.issn.1673-9418.2108105),<br> by *Yi, HAN, Linbo, QIAO, Dongsheng, LI and Xiangke, LIAO*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09252) [**Mind the Knowledge Gap: A Survey of Knowledge-enhanced Dialogue
Systems**](https://doi.org/10.48550/arXiv.2212.09252),<br> by *Sagi Shaier, Lawrence Hunter and Katharina Kann*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.coling-1.85) [**A Domain Knowledge Enhanced Pre-Trained Language Model for Vertical
Search: Case Study on Medicinal Products**](https://aclanthology.org/2022.coling-1.85),<br> by *Kesong Liu, Jianhui Jiang and Feifei Lyu*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.207) [**Knowledge Prompting in Pre-trained Language Model for Natural Language
Understanding**](https://aclanthology.org/2022.emnlp-main.207),<br> by *Jianing Wang, Wenkang Huang, Minghui Qiu, Qiuhui Shi, Hongbin Wang, Xiang Li and Ming Gao*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.findings-acl.150) [**Dict-BERT: Enhancing Language Model Pre-training with Dictionary**](https://doi.org/10.18653/v1/2022.findings-acl.150),<br> by *Wenhao Yu, Chenguang Zhu, Yuwei Fang, Donghan Yu, Shuohang Wang, Yichong Xu, Michael Zeng and Meng Jiang*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=41e9o6cQPj) [**GreaseLM: Graph REASoning Enhanced Language Models**](https://openreview.net/forum?id=41e9o6cQPj),<br> by *Xikun Zhang, Antoine Bosselut, Michihiro Yasunaga, Hongyu Ren, Percy Liang, Christopher D. Manning and Jure Leskovec*
<br><br>
- [<img src=https://img.shields.io/badge/CIKM-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3511808.3557459) [**SPOT: Knowledge-Enhanced Language Representations for Information
Extraction**](https://doi.org/10.1145/3511808.3557459),<br> by *Jiacheng Li, Yannis Katsis, Tyler Baldwin, Ho-Cheol Kim, Andrew Bartko, Julian J. McAuley and Chun-Nan Hsu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.00975) [**Relation-aware Language-Graph Transformer for Question Answering**](https://doi.org/10.48550/arXiv.2212.00975),<br> by *Jinyoung Park, Hyeong Kyu Choi, Juyeon Ko, Hyeon-Jin Park, Ji-Hoon Kim, Jisu Jeong, Kyung-Min Kim and Hyunwoo J. Kim*
<br><br>
- [<img src=https://img.shields.io/badge/SIGIR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3404835.3462865) [**Knowledge-based Review Generation by Coherence Enhanced Text Planning**](https://doi.org/10.1145/3404835.3462865),<br> by *Junyi Li, Wayne Xin Zhao, Zhicheng Wei, Nicholas Jing Yuan and Ji-Rong Wen*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.173) [**A Three-Stage Learning Framework for Low-Resource Knowledge-Grounded
Dialogue Generation**](https://doi.org/10.18653/v1/2021.emnlp-main.173),<br> by *Shilei Liu, Xiaofeng Zhao, Bochao Li, Feiliang Ren, Longhui Zhang and Shujuan Yin*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.340) [**Ask what's missing and what's useful: Improving Clarification Question
Generation using Global Knowledge**](https://doi.org/10.18653/v1/2021.naacl-main.340),<br> by *Bodhisattwa Prasad Majumder, Sudha Rao, Michel Galley and Julian J. McAuley*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.02137) [**ERNIE 3.0: Large-scale Knowledge Enhanced Pre-training for Language
Understanding and Generation**](https://arxiv.org/abs/2107.02137),<br> by *Yu Sun, Shuohuan Wang, Shikun Feng, Siyu Ding, Chao Pang, Junyuan Shang, Jiaxiang Liu, Xuyi Chen et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.bionlp-1.20) [**Improving Biomedical Pretrained Language Models with Knowledge**](https://doi.org/10.18653/v1/2021.bionlp-1.20),<br> by *Zheng Yuan, Yijia Liu, Chuanqi Tan, Songfang Huang and Fei Huang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.697) [**KGPT: Knowledge-Grounded Pre-Training for Data-to-Text Generation**](https://doi.org/10.18653/v1/2020.emnlp-main.697),<br> by *Wenhu Chen, Yu Su, Xifeng Yan and William Yang Wang*
<br><br>
- [<img src=https://img.shields.io/badge/TACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1162/tacl\_a\_00302) [**A Knowledge-Enhanced Pretraining Model for Commonsense Story Generation**](https://doi.org/10.1162/tacl\_a\_00302),<br> by *Jian Guan, Fei Huang, Minlie Huang, Zhihao Zhao and Xiaoyan Zhu*
<br><br>
- [<img src=https://img.shields.io/badge/CIKM-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3340531.3411893) [**Knowledge-Enhanced Personalized Review Generation with Capsule Graph
Neural Network**](https://doi.org/10.1145/3340531.3411893),<br> by *Junyi Li, Siqing Li, Wayne Xin Zhao, Gaole He, Zhicheng Wei, Nicholas Jing Yuan and Ji-Rong Wen*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.226) [**MEGATRON-CNTRL: Controllable Story Generation with External Knowledge
Using Large-Scale Language Models**](https://doi.org/10.18653/v1/2020.emnlp-main.226),<br> by *Peng Xu, Mostofa Patwary, Mohammad Shoeybi, Raul Puri, Pascale Fung, Anima Anandkumar and Bryan Catanzaro*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2009-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2009/hash/1543843a4723ed2ab08e18053ae6dc5b-Abstract.html) [**Zero-shot Learning with Semantic Output Codes**](https://proceedings.neurips.cc/paper/2009/hash/1543843a4723ed2ab08e18053ae6dc5b-Abstract.html),<br> by *Mark Palatucci, Dean Pomerleau, Geoffrey E. Hinton and Tom M. Mitchell*
<br><br>
### Knowledge Distillation

- [<img src=https://img.shields.io/badge/ASE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3551349.3556964) [**Compressing Pre-trained Models of Code into 3 MB**](https://doi.org/10.1145/3551349.3556964),<br> by *Jieke Shi, Zhou Yang, Bowen Xu, Hong Jin Kang and David Lo*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.01351) [**Less is More: Task-aware Layer-wise Distillation for Language Model
Compression**](https://doi.org/10.48550/arXiv.2210.01351),<br> by *Chen Liang, Simiao Zuo, Qingru Zhang, Pengcheng He, Weizhu Chen and Tuo Zhao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.03885) [**Meta-DMoE: Adapting to Domain Shift by Meta-Distillation from Mixture-of-Experts**](https://doi.org/10.48550/arXiv.2210.03885),<br> by *Tao Zhong, Zhixiang Chi, Li Gu, Yang Wang, Yuanhao Yu and Jin Tang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.628) [**CN-AutoMIC: Distilling Chinese Commonsense Knowledge from Pretrained
Language Models**](https://aclanthology.org/2022.emnlp-main.628),<br> by *Chenhao Wang, Jiachun Li, Yubo Chen, Kang Liu and Jun Zhao*
<br><br>
- [<img src=https://img.shields.io/badge/the_60th_Annual_Meeting_of_the_Association_for_Computational
Linguistics_(Volume_1:_Long_Papers),_{ACL}_2022,_Dublin,_Ireland,
May_22--27,_2022-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.116) [**Domain Knowledge Transferring for Pre-trained Language Model via Calibrated
Activation Boundary Distillation**](https://doi.org/10.18653/v1/2022.acl-long.116),<br> by *Dongha Choi, Hongseok Choi and Hyunju Lee*
<br><br>
- [<img src=https://img.shields.io/badge/Neurocomputing-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1016/j.neucom.2021.04.102) [**Preparing lessons: Improve knowledge distillation with better supervision**](https://doi.org/10.1016/j.neucom.2021.04.102), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Tiancheng Wen, Shenqi Lai and Xueming Qian*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.40) [**Adapt-and-Distill: Developing Small, Fast and Effective Pretrained
Language Models for Domains**](https://doi.org/10.18653/v1/2021.findings-acl.40),<br> by *Yunzhi Yao, Shaohan Huang, Wenhui Wang, Li Dong and Furu Wei*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.259) [**Taming Pre-trained Language Models with N-gram Representations for
Low-Resource Domain Adaptation**](https://doi.org/10.18653/v1/2021.acl-long.259),<br> by *Shizhe Diao, Ruijia Xu, Hongjin Su, Yilei Jiang, Yan Song and Tong Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.705) [**Distilling Knowledge Learned in BERT for Text Generation**](https://doi.org/10.18653/v1/2020.acl-main.705),<br> by *Yen-Chun Chen, Zhe Gan, Yu Cheng, Jingzhou Liu and Jingjing Liu*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/5963) [**Improved Knowledge Distillation via Teacher Assistant**](https://ojs.aaai.org/index.php/AAAI/article/view/5963), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Seyed-Iman Mirzadeh, Mehrdad Farajtabar, Ang Li, Nir Levine, Akihiro Matsukawa and Hassan Ghasemzadeh*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yun_Regularizing_Class-Wise_Predictions_via_Self-Knowledge_Distillation_CVPR_2020_paper.pdf) [**Regularizing Class-Wise Predictions via Self-Knowledge Distillation**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yun_Regularizing_Class-Wise_Predictions_via_Self-Knowledge_Distillation_CVPR_2020_paper.pdf), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Sukmin Yun, Jongjin Park, Kimin Lee and Jinwoo Shin*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://openaccess.thecvf.com/content\_CVPR\_2019/html/Park\_Relational\_Knowledge\_Distillation\_CVPR\_2019\_paper.html) [**Relational Knowledge Distillation**](http://openaccess.thecvf.com/content\_CVPR\_2019/html/Park\_Relational\_Knowledge\_Distillation\_CVPR\_2019\_paper.html), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Wonpyo Park, Dongju Kim, Yan Lu and Minsu Cho*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1909.11723) [**Revisit Knowledge Distillation: a Teacher-free Framework**](http://arxiv.org/abs/1909.11723), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Li Yuan, Francis E. H. Tay, Guilin Li, Tao Wang and Jiashi Feng*
<br><br>
- [<img src=https://img.shields.io/badge/ICCV-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/ICCV.2019.00143) [**Knowledge Distillation via Route Constrained Optimization**](https://doi.org/10.1109/ICCV.2019.00143), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Xiao Jin, Baoyun Peng, Yichao Wu, Yu Liu, Jiaheng Liu, Ding Liang, Junjie Yan and Xiaolin Hu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1910.05057) [**Improving Generalization and Robustness with Noisy Collaboration in
Knowledge Distillation**](http://arxiv.org/abs/1910.05057), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Elahe Arani, Fahad Sarfraz and Bahram Zonooz*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1903.12136) [**Distilling Task-Specific Knowledge from BERT into Simple Neural
Networks**](http://arxiv.org/abs/1903.12136), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Raphael Tang, Yao Lu, Linqing Liu, Lili Mou, Olga Vechtomova and Jimmy Lin*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=rJl-b3RcF7) [**The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks**](https://openreview.net/forum?id=rJl-b3RcF7), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Jonathan Frankle and Michael Carbin*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2018-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://proceedings.mlr.press/v80/furlanello18a.html) [**Born-Again Neural Networks**](http://proceedings.mlr.press/v80/furlanello18a.html), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Tommaso Furlanello, Zachary Chase Lipton, Michael Tschannen, Laurent Itti and Anima Anandkumar*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2017-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=Sks9\_ajex) [**Paying More Attention to Attention: Improving the Performance of Convolutional
Neural Networks via Attention Transfer**](https://openreview.net/forum?id=Sks9\_ajex), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Sergey Zagoruyko and Nikos Komodakis*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2017-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=ry8u21rtl) [**Mean teachers are better role models: Weight-averaged consistency
targets improve semi-supervised deep learning results**](https://openreview.net/forum?id=ry8u21rtl), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Antti Tarvainen and Harri Valpola*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2017-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1706.00384) [**Deep Mutual Learning**](http://arxiv.org/abs/1706.00384), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Ying Zhang, Tao Xiang, Timothy M. Hospedales and Huchuan Lu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2016-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1610.09650) [**Deep Model Compression: Distilling Knowledge from Noisy Teachers**](http://arxiv.org/abs/1610.09650), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Bharat Bhusan Sau and Vineeth N. Balasubramanian*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2015-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1503.02531) [**Distilling the Knowledge in a Neural Network**](http://arxiv.org/abs/1503.02531), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/SforAiDl/KD_Lib)<br> by *Geoffrey E. Hinton, Oriol Vinyals and Jeffrey Dean*
<br><br>
### Knowledge Generation

- [<img src=https://img.shields.io/badge/EACL-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.12810) [**Crawling the Internal Knowledge-Base of Language Models**](https://doi.org/10.48550/arXiv.2301.12810),<br> by *Roi Cohen, Mor Geva, Jonathan Berant and Amir Globerson*
<br>``
本文提出一种从语言模型中提取结构化知识图谱的方法；使用专门设计的提示来控制提取过程中的精度和召回率；在GPT-3上进行了评估，显示了高精确度的结果。
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.11293) [**Understanding Finetuning for Factual Knowledge Extraction from Language
Models**](https://doi.org/10.48550/arXiv.2301.11293),<br> by *Mehran Kazemi, Sid Mittal and Deepak Ramachandran*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.1) [**Generative Knowledge Graph Construction: A Review**](https://aclanthology.org/2022.emnlp-main.1),<br> by *Hongbin Ye, Ningyu Zhang, Hui Chen and Huajun Chen*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.438) [**Calibrating Factual Knowledge in Pretrained Language Models**](https://aclanthology.org/2022.findings-emnlp.438),<br> by *Qingxiu Dong, Damai Dai, Yifan Song, Jingjing Xu, Zhifang Sui and Lei Li*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=DhzIU48OcZh) [**P-Adapters: Robustly Extracting Factual Information from Language
Models with Diverse Prompts**](https://openreview.net/forum?id=DhzIU48OcZh),<br> by *Benjamin Newman, Prafulla Kumar Choubey and Nazneen Rajani*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.225) [**Generated Knowledge Prompting for Commonsense Reasoning**](https://doi.org/10.18653/v1/2022.acl-long.225),<br> by *Jiacheng Liu, Alisa Liu, Ximing Lu, Sean Welleck, Peter West, Ronan Le Bras, Yejin Choi and Hannaneh Hajishirzi*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.611) [**Rainier: Reinforced Knowledge Introspector for Commonsense Question
Answering**](https://aclanthology.org/2022.emnlp-main.611),<br> by *Jiacheng Liu, Skyler Hallinan, Ximing Lu, Pengfei He, Sean Welleck, Hannaneh Hajishirzi and Yejin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/the_2022_Conference_of_the_North_American_Chapter_of
the_Association_for_Computational_Linguistics:_Human_Language_Technologies,
{NAACL}_2022,_Seattle,_WA,_United_States,_July_10--15,_2022-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.341) [**Symbolic Knowledge Distillation: from General Language Models to Commonsense
Models**](https://doi.org/10.18653/v1/2022.naacl-main.341),<br> by *Peter West, Chandra Bhagavatula, Jack Hessel, Jena D. Hwang, Liwei Jiang, Ronan Le Bras, Ximing Lu, Sean Welleck et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09246) [**I2D2: Inductive Knowledge Distillation with NeuroLogic and Self-Imitation**](https://doi.org/10.48550/arXiv.2212.09246),<br> by *Chandra Bhagavatula, Jena D. Hwang, Doug Downey, Ronan Le Bras, Ximing Lu, Keisuke Sakaguchi, Swabha Swayamdipta, Peter West et al.*
<br><br>
### Knowledge Editing

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.00046) [**Robustness of edited neural networks**](https://doi.org/10.48550/arXiv.2303.00046),<br> by *Davis Brown, Charles Godfrey, Cody Nizinski, Jonathan Tu and Henry Kvinge*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.09785) [**Transformer-Patcher: One Mistake worth One Neuron**](https://doi.org/10.48550/arXiv.2301.09785),<br> by *Zeyu Huang, Yikang Shen, Xiaofeng Zhang, Jie Zhou, Wenge Rong and Zhang Xiong*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=0DcZxeWfOPt) [**Fast Model Editing at Scale**](https://openreview.net/forum?id=0DcZxeWfOPt),<br> by *Eric Mitchell, Charles Lin, Antoine Bosselut, Chelsea Finn and Christopher D. Manning*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.mlr.press/v162/mitchell22a.html) [**Memory-Based Model Editing at Scale**](https://proceedings.mlr.press/v162/mitchell22a.html),<br> by *Eric Mitchell, Charles Lin, Antoine Bosselut, Christopher D. Manning and Chelsea Finn*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=-h6WAS6eE4) [**Locating and editing factual associations in gpt**](https://openreview.net/forum?id=-h6WAS6eE4),<br> by *Meng, Kevin, Bau, David, Andonian, Alex J and Belinkov, Yonatan*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.11031) [**Aging with GRACE: Lifelong Model Editing with Discrete Key-Value
Adaptors**](https://doi.org/10.48550/arXiv.2211.11031),<br> by *Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim and Marzyeh Ghassemi*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.522) [**Editing Factual Knowledge in Language Models**](https://doi.org/10.18653/v1/2021.emnlp-main.522),<br> by *Nicola De Cao, Wilker Aziz and Ivan Titov*
<br><br>
### Reasoning

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.11596) [**ThoughtSource: A central hub for large language model reasoning
data**](https://doi.org/10.48550/arXiv.2301.11596),<br> by *Simon Ott, Konstantin Hebenstreit, Valentin Li\'evin, Christoffer Egeberg Hother, Milad Moradi, Maximilian Mayrhauser, Robert Praas, Ole Winther et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.02093) [**Knowledge-enhanced Neural Machine Reasoning: A Review**](https://doi.org/10.48550/arXiv.2302.02093),<br> by *Tanmoy Chowdhury, Chen Ling, Xuchao Zhang, Xujiang Zhao, Guangji Bai, Jian Pei, Haifeng Chen and Liang Zhao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.13808) [**Large Language Models are Versatile Decomposers: Decompose Evidence
and Questions for Table-based Reasoning**](https://doi.org/10.48550/arXiv.2301.13808),<br> by *Yunhu Ye, Binyuan Hui, Min Yang, Binhua Li, Fei Huang and Yongbin Li*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.12726) [**Specializing Smaller Language Models towards Multi-Step Reasoning**](https://doi.org/10.48550/arXiv.2301.12726),<br> by *Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal and Tushar Khot*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2303.05398) [**MathPrompter: Mathematical Reasoning using Large Language Models**](https://arxiv.org/abs/2303.05398),<br> by *Imani, Shima, Du, Liang and Shrivastava, Harsh*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=8lNy3QCaxHX) [**Improved logical reasoning of language models via differentiable symbolic programming**](https://openreview.net/forum?id=8lNy3QCaxHX),<br> by *Zhang, Hanlin, Li, Ziyang, Huang, Jiani, Naik, Mayur and Xing, Eric*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.392) [**LILA: A Unified Benchmark for Mathematical Reasoning**](https://aclanthology.org/2022.emnlp-main.392),<br> by *Swaroop Mishra, Matthew Finlayson, Pan Lu, Leonard Tang, Sean Welleck, Chitta Baral, Tanmay Rajpurohit, Oyvind Tafjord et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.82) [**Maieutic Prompting: Logically Consistent Reasoning with Recursive
Explanations**](https://aclanthology.org/2022.emnlp-main.82),<br> by *Jaehun Jung, Lianhui Qin, Sean Welleck, Faeze Brahman, Chandra Bhagavatula, Ronan Le Bras and Yejin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.08607) [**MURMUR: Modular Multi-Step Reasoning for Semi-Structured Data-to-Text
Generation**](https://doi.org/10.48550/arXiv.2212.08607),<br> by *Swarnadeep Saha, Xinyan Velocity Yu, Mohit Bansal, Ramakanth Pasunuru and Asli Celikyilmaz*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.12588) [**Program of Thoughts Prompting: Disentangling Computation from Reasoning
for Numerical Reasoning Tasks**](https://doi.org/10.48550/arXiv.2211.12588),<br> by *Wenhu Chen, Xueguang Ma, Xinyi Wang and William W. Cohen*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.08686) [**The Impact of Symbolic Representations on In-context Learning for
Few-shot Reasoning**](https://doi.org/10.48550/arXiv.2212.08686),<br> by *Hanlin Zhang, Yi-Fan Zhang, Li Erran Li and Eric P. Xing*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10403) [**Towards Reasoning in Large Language Models: A Survey**](https://doi.org/10.48550/arXiv.2212.10403),<br> by *Jie Huang and Kevin Chen-Chuan Chang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.218) [**UniGeo: Unifying Geometry Logical Reasoning via Reformulating Mathematical
Expression**](https://aclanthology.org/2022.emnlp-main.218),<br> by *Jiaqi Chen, Tong Li, Jinghui Qin, Pan Lu, Liang Lin, Chongyu Chen and Xiaodan Liang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.10625) [**Least-to-Most Prompting Enables Complex Reasoning in Large Language
Models**](https://doi.org/10.48550/arXiv.2205.10625),<br> by *Denny Zhou, Nathanael Sch\"arli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet et al.*
<br>``
(1) 两阶段的prompt，第一阶段问题分解（通过in-context learning实现，context中包含了其他问题的分解示例），对于每个问题，分解出回答该问题需要先回答什么子问题；
``<br>``
(2) 在第二阶段中，从后往前依次解决子问题，同样通过in-context learing得到，每次LLM的回答会参与组成下一个问题的prompt。
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2207.00747) [**Rationale-Augmented Ensembles in Language Models**](https://doi.org/10.48550/arXiv.2207.00747),<br> by *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc V. Le, Ed H. Chi and Denny Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://par.nsf.gov/biblio/10380030) [**The unreliability of explanations in few-shot prompting for textual reasoning**](https://par.nsf.gov/biblio/10380030),<br> by *Ye, Xi and Durrett, Greg*
<br><br>
- [<img src=https://img.shields.io/badge/KDD-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3534678.3539131) [**JiuZhang: A Chinese Pre-trained Language Model for Mathematical
Problem Understanding**](https://doi.org/10.1145/3534678.3539131),<br> by *Wayne Xin Zhao, Kun Zhou, Zheng Gong, Beichen Zhang, Yuanhang Zhou, Jing Sha, Zhigang Chen, Shijin Wang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.01293) [**ThinkSum: Probabilistic reasoning over sets using large language models**](https://doi.org/10.48550/arXiv.2210.01293),<br> by *Batu Ozturkler, Nikolay Malkin, Zhen Wang and Nebojsa Jojic*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.653) [**RobustLR: A Diagnostic Benchmark for Evaluating Logical Robustness
of Deductive Reasoners**](https://aclanthology.org/2022.emnlp-main.653),<br> by *Soumya Sanyal, Zeyi Liao and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.14858) [**Solving Quantitative Reasoning Problems with Language Models**](https://doi.org/10.48550/arXiv.2206.14858),<br> by *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay V. Ramasesh, Ambrose Slone, Cem Anil et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.418) [**Thinking Like a Skeptic: Defeasible Inference in Natural Language**](https://doi.org/10.18653/v1/2020.findings-emnlp.418),<br> by *Rachel Rudinger, Vered Shwartz, Jena D. Hwang, Chandra Bhagavatula, Maxwell Forbes, Ronan Le Bras, Noah A. Smith and Yejin Choi*
<br><br>
#### Chain of Thought

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.00923) [**Multimodal Chain-of-Thought Reasoning in Language Models**](https://doi.org/10.48550/arXiv.2302.00923),<br> by *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis and Alex Smola*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.00303) [**Rethinking with Retrieval: Faithful Large Language Model Inference**](https://doi.org/10.48550/arXiv.2301.00303),<br> by *Hangfeng He, Hongming Zhang and Dan Roth*
<br>``
本文通过用GPT-3在三个复杂的推理任务：常识推理，时间推理和表格推理上进行大量实验来评估RR的有效性。结果表明，RR可以产生更忠实的解释，并提高LLM的性能。
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.12246) [**Active Prompting with Chain-of-Thought for Large Language Models**](https://doi.org/10.48550/arXiv.2302.12246),<br> by *Shizhe Diao, Pengcheng Wang, Yong Lin and Tong Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.12822) [**Automatic Prompt Augmentation and Selection with Chain-of-Thought
from Labeled Data**](https://doi.org/10.48550/arXiv.2302.12822),<br> by *Kashun Shum, Shizhe Diao and Tong Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.10782) [**Instruction Induction: From Few Examples to Natural Language Task
Descriptions**](https://doi.org/10.48550/arXiv.2205.10782),<br> by *Or Honovich, Uri Shaham, Samuel R. Bowman and Omer Levy*
<br>``
(1) 探索了利用LLM在几个样本的情况下归纳出任务指令的能力；
``<br>``
(2) 测量两个指标：1. 模型归纳指令与人类归纳的指令对比，2. 利用模型归纳的指令作为prompt进行预测的执行准确率；
``<br>``
(3) 相比于GPT-3，InstructGPT效果更好，理所当然。
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.174) [**Iteratively Prompt Pre-trained Language Models for Chain of Thought**](https://aclanthology.org/2022.emnlp-main.174),<br> by *Boshi Wang, Xiang Deng and Huan Sun*
<br>``
(1) 提出了一种迭代式的prompt-tuning方法，他们认为soft prompt应该带有语境，即在自回归解码时不同时刻应该有不同的prompt向量；
``<br>``
(2) 利用BERT为encoder-decoder架构的PLM生成prompt，在每个解码时刻BERT都会根据先前时刻的上下文生成一组新的prompt向量，提供给PLM生成新的上下文，迭代往复。
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.00720) [**Complexity-Based Prompting for Multi-Step Reasoning**](https://doi.org/10.48550/arXiv.2210.00720),<br> by *Yao Fu, Hao Peng, Ashish Sabharwal, Peter Clark and Tushar Khot*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.03350) [**Measuring and Narrowing the Compositionality Gap in Language Models**](https://doi.org/10.48550/arXiv.2210.03350),<br> by *Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith and Mike Lewis*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.03493) [**Automatic Chain of Thought Prompting in Large Language Models**](https://doi.org/10.48550/arXiv.2210.03493),<br> by *Zhuosheng Zhang, Aston Zhang, Mu Li and Alex Smola*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2201.11903) [**Chain of Thought Prompting Elicits Reasoning in Large Language Models**](https://arxiv.org/abs/2201.11903),<br> by *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Ed H. Chi, Quoc Le and Denny Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2203.11171) [**Self-Consistency Improves Chain of Thought Reasoning in Language Models**](https://doi.org/10.48550/arXiv.2203.11171),<br> by *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc V. Le, Ed H. Chi and Denny Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.07686) [**Text and Patterns: For Effective Chain of Thought, It Takes Two to
Tango**](https://doi.org/10.48550/arXiv.2209.07686),<br> by *Aman Madaan and Amir Yazdanbakhsh*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10001) [**Towards Understanding Chain-of-Thought Prompting: An Empirical Study
of What Matters**](https://doi.org/10.48550/arXiv.2212.10001),<br> by *Boshi Wang, Sewon Min, Xiang Deng, Jiaming Shen, You Wu, Luke Zettlemoyer and Huan Sun*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2204.02311) [**PaLM: Scaling Language Modeling with Pathways**](https://doi.org/10.48550/arXiv.2204.02311),<br> by *Aakanksha Chowdhery, Sharan Narang, Jacob Devlin, Maarten Bosma, Gaurav Mishra, Adam Roberts, Paul Barham, Hyung Won Chung et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.13894) [**LAMBADA: Backward Chaining for Automated Reasoning in Natural Language**](https://doi.org/10.48550/arXiv.2212.13894),<br> by *Seyed Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu and Deepak Ramachandran*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://research.google/pubs/pub51694/) [**Star: Self-taught reasoner bootstrapping reasoning with reasoning**](https://research.google/pubs/pub51694/),<br> by *Zelikman, Eric, Mu, Jesse, Goodman, Noah D and Wu, Yuhuai Tony*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.01240) [**Language Models Are Greedy Reasoners: A Systematic Formal Analysis
of Chain-of-Thought**](https://doi.org/10.48550/arXiv.2210.01240),<br> by *Abulhair Saparov and He He*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.11916) [**Large Language Models are Zero-Shot Reasoners**](https://doi.org/10.48550/arXiv.2205.11916),<br> by *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo and Yusuke Iwasawa*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.09712) [**Selection-Inference: Exploiting Large Language Models for Interpretable
Logical Reasoning**](https://doi.org/10.48550/arXiv.2205.09712),<br> by *Antonia Creswell, Murray Shanahan and Irina Higgins*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.07682) [**Emergent Abilities of Large Language Models**](https://doi.org/10.48550/arXiv.2206.07682),<br> by *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma et al.*
<br><br>
- [<img src=https://img.shields.io/badge/KDD-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3534678.3539131) [**JiuZhang: A Chinese Pre-trained Language Model for Mathematical
Problem Understanding**](https://doi.org/10.1145/3534678.3539131),<br> by *Wayne Xin Zhao, Kun Zhou, Zheng Gong, Beichen Zhang, Yuanhang Zhou, Jing Sha, Zhigang Chen, Shijin Wang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10071) [**Large Language Models Are Reasoning Teachers**](https://doi.org/10.48550/arXiv.2212.10071),<br> by *Namgyu Ho, Laura Schmid and Se-Young Yun*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09561) [**Large Language Models are reasoners with Self-Verification**](https://doi.org/10.48550/arXiv.2212.09561),<br> by *Yixuan Weng, Minjun Zhu, Shizhu He, Kang Liu and Jun Zhao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09597) [**Reasoning with Language Model Prompting: A Survey**](https://doi.org/10.48550/arXiv.2212.09597),<br> by *Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.10435) [**PAL: Program-aided Language Models**](https://doi.org/10.48550/arXiv.2211.10435),<br> by *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan and Graham Neubig*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.06710) [**Large Language Models are few(1)-shot Table Reasoners**](https://doi.org/10.48550/arXiv.2210.06710),<br> by *Wenhu Chen*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.11610) [**Large Language Models Can Self-Improve**](https://doi.org/10.48550/arXiv.2210.11610),<br> by *Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu and Jiawei Han*
<br><br>
#### Multi-Step Reasoning

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.12726) [**Specializing Smaller Language Models towards Multi-Step Reasoning**](https://doi.org/10.48550/arXiv.2301.12726),<br> by *Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal and Tushar Khot*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.08607) [**MURMUR: Modular Multi-Step Reasoning for Semi-Structured Data-to-Text
Generation**](https://doi.org/10.48550/arXiv.2212.08607),<br> by *Swarnadeep Saha, Xinyan Velocity Yu, Mohit Bansal, Ramakanth Pasunuru and Asli Celikyilmaz*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2207.00747) [**Rationale-Augmented Ensembles in Language Models**](https://doi.org/10.48550/arXiv.2207.00747),<br> by *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc V. Le, Ed H. Chi and Denny Zhou*
<br><br>
#### Arithmetic Reasoning

- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.392) [**LILA: A Unified Benchmark for Mathematical Reasoning**](https://aclanthology.org/2022.emnlp-main.392),<br> by *Swaroop Mishra, Matthew Finlayson, Pan Lu, Leonard Tang, Sean Welleck, Chitta Baral, Tanmay Rajpurohit, Oyvind Tafjord et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.12588) [**Program of Thoughts Prompting: Disentangling Computation from Reasoning
for Numerical Reasoning Tasks**](https://doi.org/10.48550/arXiv.2211.12588),<br> by *Wenhu Chen, Xueguang Ma, Xinyi Wang and William W. Cohen*
<br><br>
- [<img src=https://img.shields.io/badge/KDD-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3534678.3539131) [**JiuZhang: A Chinese Pre-trained Language Model for Mathematical
Problem Understanding**](https://doi.org/10.1145/3534678.3539131),<br> by *Wayne Xin Zhao, Kun Zhou, Zheng Gong, Beichen Zhang, Yuanhang Zhou, Jing Sha, Zhigang Chen, Shijin Wang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.14858) [**Solving Quantitative Reasoning Problems with Language Models**](https://doi.org/10.48550/arXiv.2206.14858),<br> by *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay V. Ramasesh, Ambrose Slone, Cem Anil et al.*
<br><br>
#### Symbolic Reasoning

- [<img src=https://img.shields.io/badge/ICML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=8lNy3QCaxHX) [**Improved logical reasoning of language models via differentiable symbolic programming**](https://openreview.net/forum?id=8lNy3QCaxHX),<br> by *Zhang, Hanlin, Li, Ziyang, Huang, Jiani, Naik, Mayur and Xing, Eric*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.82) [**Maieutic Prompting: Logically Consistent Reasoning with Recursive
Explanations**](https://aclanthology.org/2022.emnlp-main.82),<br> by *Jaehun Jung, Lianhui Qin, Sean Welleck, Faeze Brahman, Chandra Bhagavatula, Ronan Le Bras and Yejin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.08686) [**The Impact of Symbolic Representations on In-context Learning for
Few-shot Reasoning**](https://doi.org/10.48550/arXiv.2212.08686),<br> by *Hanlin Zhang, Yi-Fan Zhang, Li Erran Li and Eric P. Xing*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.218) [**UniGeo: Unifying Geometry Logical Reasoning via Reformulating Mathematical
Expression**](https://aclanthology.org/2022.emnlp-main.218),<br> by *Jiaqi Chen, Tong Li, Jinghui Qin, Pan Lu, Liang Lin, Chongyu Chen and Xiaodan Liang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.418) [**Thinking Like a Skeptic: Defeasible Inference in Natural Language**](https://doi.org/10.18653/v1/2020.findings-emnlp.418),<br> by *Rachel Rudinger, Vered Shwartz, Jena D. Hwang, Chandra Bhagavatula, Maxwell Forbes, Ronan Le Bras, Noah A. Smith and Yejin Choi*
<br><br>
### Federated Learning

- [<img src=https://img.shields.io/badge/JIS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1016/j.ins.2021.12.102) [**Fairness and accuracy in horizontal federated learning**](https://doi.org/10.1016/j.ins.2021.12.102),<br> by *Wei Huang, Tianrui Li, Dexian Wang, Shengdong Du, Junbo Zhang and Tianqiang Huang*
<br><br>
- [<img src=https://img.shields.io/badge/TNSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/TNSE.2022.3169117) [**Federated Learning Meets Multi-Objective Optimization**](https://doi.org/10.1109/TNSE.2022.3169117),<br> by *Zeou Hu, Kiarash Shaloudegi, Guojun Zhang and Yaoliang Yu*
<br><br>
- [<img src=https://img.shields.io/badge/KIS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/s10115-022-01664-x) [**From distributed machine learning to federated learning: a survey**](https://doi.org/10.1007/s10115-022-01664-x),<br> by *Ji Liu, Jizhou Huang, Yang Zhou, Xuhong Li, Shilei Ji, Haoyi Xiong and Dejing Dou*
<br><br>
- [<img src=https://img.shields.io/badge/IJCAI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.24963/ijcai.2022/273) [**Meta-Learning Based Knowledge Extrapolation for Knowledge Graphs in
the Federated Setting**](https://doi.org/10.24963/ijcai.2022/273),<br> by *Mingyang Chen, Wen Zhang, Zhen Yao, Xiangnan Chen, Mengxiao Ding, Fei Huang and Huajun Chen*
<br><br>
- [<img src=https://img.shields.io/badge/CIKM-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3511808.3557108) [**Mitigating Biases in Student Performance Prediction via Attention-Based
Personalized Federated Learning**](https://doi.org/10.1145/3511808.3557108),<br> by *Yun-Wei Chu, Seyyedali Hosseinalipour, Elizabeth Tenorio, Laura M. Cruz Castro, Kerrie A. Douglas, Andrew Lan and Christopher G. Brinton*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.101) [**Pretrained Models for Multilingual Federated Learning**](https://doi.org/10.18653/v1/2022.naacl-main.101),<br> by *Orion Weller, Marc Marone, Vladimir Braverman, Dawn J. Lawrie and Benjamin Van Durme*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/CVPR52688.2022.00982) [**Rethinking Architecture Design for Tackling Data Heterogeneity in
Federated Learning**](https://doi.org/10.1109/CVPR52688.2022.00982),<br> by *Liangqiong Qu, Yuyin Zhou, Paul Pu Liang, Yingda Xia, Feifei Wang, Ehsan Adeli, Li Fei-Fei and Daniel L. Rubin*
<br><br>
- [<img src=https://img.shields.io/badge/TIST-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510033) [**FedBERT: When Federated Learning Meets Pre-training**](https://doi.org/10.1145/3510033),<br> by *Yuanyishu Tian, Yao Wan, Lingjuan Lyu, Dezhong Yao, Hai Jin and Lichao Sun*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.08090) [**Where to Begin? On the Impact of Pre-Training and Initialization in
Federated Learning**](https://doi.org/10.48550/arXiv.2210.08090),<br> by *John Nguyen, Jianyu Wang, Kshitiz Malik, Maziar Sanjabi and Michael Rabbat*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://proceedings.mlr.press/v139/li21h.html) [**Ditto: Fair and Robust Federated Learning Through Personalization**](http://proceedings.mlr.press/v139/li21h.html),<br> by *Tian Li, Shengyuan Hu, Ahmad Beirami and Virginia Smith*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2108.07313) [**Fine-tuning is Fine in Federated Learning**](https://arxiv.org/abs/2108.07313),<br> by *Gary Cheng, Karan N. Chadha and John C. Duchi*
<br><br>
- [<img src=https://img.shields.io/badge/IJCAI-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.24963/ijcai.2021/223) [**Federated Learning with Fair Averaging**](https://doi.org/10.24963/ijcai.2021/223),<br> by *Zheng Wang, Xiaoliang Fan, Jianzhong Qi, Chenglu Wen, Cheng Wang and Rongshan Yu*
<br><br>
- [<img src=https://img.shields.io/badge/FLPI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-030-63076-8\_14) [**Collaborative Fairness in Federated Learning**](https://doi.org/10.1007/978-3-030-63076-8\_14),<br> by *Lingjuan Lyu, Xinyi Xu, Qian Wang and Han Yu*
<br><br>
- [<img src=https://img.shields.io/badge/ECCV-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-030-58607-2\_5) [**Federated Visual Classification with Real-World Data Distribution**](https://doi.org/10.1007/978-3-030-58607-2\_5),<br> by *Tzu-Ming Harry Hsu, Hang Qi and Matthew Brown*
<br><br>
### Distributed AI

- [<img src=https://img.shields.io/badge/EDBT-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48786/edbt.2022.48) [**Distributed Training of Knowledge Graph Embedding Models using Ray**](https://doi.org/10.48786/edbt.2022.48),<br> by *Nasrullah Sheikh, Xiao Qin, Yaniv Gur and Berthold Reinwald*
<br><br>
- [<img src=https://img.shields.io/badge/IEEE_-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/JSTSP.2022.3162989) [**Distributed Learning With Sparsified Gradient Differences**](https://doi.org/10.1109/JSTSP.2022.3162989),<br> by *Yicheng Chen, Rick S. Blum, Martin Tak\'ac and Brian M. Sadler*
<br><br>
- [<img src=https://img.shields.io/badge/AIIoT-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ieeexplore.ieee.org/document/9817156) [**Graph Attention Neural Network Distributed Model Training**](https://ieeexplore.ieee.org/document/9817156),<br> by *Esmaeilzadeh, Armin, Zadeh Nojoo Kambar, Mina Esmail and Heidari, Maryam*
<br><br>
- [<img src=https://img.shields.io/badge/Euro--Par-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-031-06156-1\_10) [**Elastic Deep Learning Using Knowledge Distillation with Heterogeneous
Computing Resources**](https://doi.org/10.1007/978-3-031-06156-1\_10),<br> by *Daxiang Dong, Ji Liu, Xi Wang, Weibao Gong, An Qin, Xingjian Li, Dianhai Yu, Patrick Valduriez et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ICDCS-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/ICDCS51616.2021.00060) [**GRACE: A Compressed Communication Framework for Distributed Machine
Learning**](https://doi.org/10.1109/ICDCS51616.2021.00060),<br> by *Hang Xu, Chen-Yu Ho, Ahmed M. Abdelmoniem, Aritra Dutta, El Houcine Bergou, Konstantinos Karatsenidis, Marco Canini and Panos Kalnis*
<br><br>
- [<img src=https://img.shields.io/badge/ICPADS-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/ICPADS53394.2021.00109) [**Load Balancing Optimization for Transformer in Distributed Environment**](https://doi.org/10.1109/ICPADS53394.2021.00109),<br> by *Delu Ma, Zhou Lei, Shengbo Chen and Peng Wang*
<br><br>
- [<img src=https://img.shields.io/badge/IA3-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/IA351965.2020.00011) [**DistDGL: Distributed Graph Neural Network Training for Billion-Scale
Graphs**](https://doi.org/10.1109/IA351965.2020.00011),<br> by *Da Zheng, Chao Ma, Minjie Wang, Jinjing Zhou, Qidong Su, Xiang Song, Quan Gan, Zheng Zhang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/VLDB-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://www.vldb.org/pvldb/vol13/p3005-li.pdf) [**PyTorch Distributed: Experiences on Accelerating Data Parallel Training**](http://www.vldb.org/pvldb/vol13/p3005-li.pdf),<br> by *Shen Li, Yanli Zhao, Rohan Varma, Omkar Salpekar, Pieter Noordhuis, Teng Li, Adam Paszke, Jeff Smith et al.*
<br><br>
- [<img src=https://img.shields.io/badge/OSDI-2018-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.usenix.org/conference/osdi18/presentation/nishihara) [**Ray: A Distributed Framework for Emerging AI Applications**](https://www.usenix.org/conference/osdi18/presentation/nishihara),<br> by *Philipp Moritz, Robert Nishihara, Stephanie Wang, Alexey Tumanov, Richard Liaw, Eric Liang, Melih Elibol, Zongheng Yang et al.*
<br><br>
### Selective Annotation

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.01975) [**Selective Annotation Makes Language Models Better Few-Shot Learners**](https://doi.org/10.48550/arXiv.2209.01975), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/HKUNLP/icl-selective-annotation) [<img src=https://img.shields.io/badge/SBERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/D19-1410/) [<img src=https://img.shields.io/badge/GPT--J-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://huggingface.co/docs/transformers/model_doc/gptj) [<img src=https://img.shields.io/badge/GPT--Neo-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://huggingface.co/docs/transformers/model_doc/gpt_neo) [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) [<img src=https://img.shields.io/badge/Codex-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.03374) [<img src=https://img.shields.io/badge/OPT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2205.01068) <br> by *Hongjin Su, Jungo Kasai, Chen Henry Wu, Weijia Shi, Tianlu Wang, Jiayi Xin, Rui Zhang, Mari Ostendorf et al.*
<br>``
This paper proposes a graph-based selective annotation method named vote-k to
``<br>``
(1) select a pool of examples to annotate from unlabeled data,
``<br>``
(2) retrieve prompts (contexts) from the annotated data pool for in-context learning.
``<br>``
Specifically, the selection method first selects a small set of unlabeled examples iteratively and then labels them to serve as contexts for LLMs to predict the labels of the rest unlabeled data. The method selects the predictions with highest confidence (log probability of generation output) to fill up the selective annotation pool.
``
<br><br>
- [<img src=https://img.shields.io/badge/VLDB-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.vldb.org/pvldb/vol15/p1466-li.pdf) [**Selective Data Acquisition in the Wild for Model Charging**](https://www.vldb.org/pvldb/vol15/p1466-li.pdf),<br> by *Chengliang Chai, Jiabin Liu, Nan Tang, Guoliang Li and Yuyu Luo*
<br><br>
### Code Generation

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.12868) [**On Robustness of Prompt-based Semantic Parsing with Large Pre-trained
Language Model: An Empirical Study on Codex**](https://doi.org/10.48550/arXiv.2301.12868),<br> by *Terry Yue Zhuo, Zhuang Li, Yujin Huang, Yuan-Fang Li, Weiqing Wang, Gholamreza Haffari and Fatemeh Shiri*
<br><br>
- [<img src=https://img.shields.io/badge/openreview-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/pdf?id=VPCi3STZcaO) [**CodeT5Mix: A Pretrained Mixture of Encoder-decoder Transformers for Code Understanding and Generation**](https://openreview.net/pdf?id=VPCi3STZcaO),<br> by *Wang, Yue, Le, Hung, Gotmare, Akhilesh Deepak, Li, Junnan and Hoi, Steven*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2302.05527) [**CodeBERTScore: Evaluating Code Generation with Pretrained Models of Code**](https://arxiv.org/abs/2302.05527),<br> by *Zhou, Shuyan, Alon, Uri, Agarwal, Sumit and Neubig, Graham*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.12810) [**Code4Struct: Code Generation for Few-Shot Structured Prediction from
Natural Language**](https://doi.org/10.48550/arXiv.2210.12810),<br> by *Xingyao Wang, Sha Li and Heng Ji*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.07128) [**Language Models of Code are Few-Shot Commonsense Learners**](https://doi.org/10.48550/arXiv.2210.07128),<br> by *Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang and Graham Neubig*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09420) [**When Neural Model Meets NL2Code: A Survey**](https://doi.org/10.48550/arXiv.2212.09420),<br> by *Daoguang Zan, Bei Chen, Fengji Zhang, Dianjie Lu, Bingchao Wu, Bei Guan, Yongji Wang and Jian-Guang Lou*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2204.00498) [**Evaluating the Text-to-SQL Capabilities of Large Language Models**](https://doi.org/10.48550/arXiv.2204.00498),<br> by *Nitarshan Rajkumar, Raymond Li and Dzmitry Bahdanau*
<br><br>
- [<img src=https://img.shields.io/badge/ISSTA-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3533767.3534390) [**An extensive study on pre-trained models for program understanding
and generation**](https://doi.org/10.1145/3533767.3534390),<br> by *Zhengran Zeng, Hanzhuo Tan, Haotian Zhang, Jing Li, Yuqun Zhang and Lingming Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2207.01780) [**CodeRL: Mastering Code Generation through Pretrained Models and Deep
Reinforcement Learning**](https://doi.org/10.48550/arXiv.2207.01780),<br> by *Hung Le, Yue Wang, Akhilesh Deepak Gotmare, Silvio Savarese and Steven C. H. Hoi*
<br><br>
- [<img src=https://img.shields.io/badge/ASE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3551349.3556955) [**CoditT5: Pretraining for Source Code and Natural Language Editing**](https://doi.org/10.1145/3551349.3556955),<br> by *Jiyang Zhang, Sheena Panthaplackel, Pengyu Nie, Junyi Jessy Li and Milos Gligoric*
<br><br>
- [<img src=https://img.shields.io/badge/ASE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3551349.3556964) [**Compressing Pre-trained Models of Code into 3 MB**](https://doi.org/10.1145/3551349.3556964),<br> by *Jieke Shi, Zhou Yang, Bowen Xu, Hong Jin Kang and David Lo*
<br><br>
- [<img src=https://img.shields.io/badge/FSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3540250.3549094) [**Diet code is healthy: simplifying programs for pre-trained models
of code**](https://doi.org/10.1145/3540250.3549094),<br> by *Zhaowei Zhang, Hongyu Zhang, Beijun Shen and Xiaodong Gu*
<br><br>
- [<img src=https://img.shields.io/badge/FSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3540250.3549162) [**NatGen: generative pre-training by "naturalizing" source code**](https://doi.org/10.1145/3540250.3549162),<br> by *Saikat Chakraborty, Toufique Ahmed, Yangruibo Ding, Premkumar T. Devanbu and Baishakhi Ray*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510003.3510203) [**Jigsaw: Large Language Models meet Program Synthesis**](https://doi.org/10.1145/3510003.3510203),<br> by *Naman Jain, Skanda Vaidyanath, Arun Shankar Iyer, Nagarajan Natarajan, Suresh Parthasarathy, Sriram K. Rajamani and Rahul Sharma*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510003.3510146) [**Natural Attack for Pre-trained Models of Code**](https://doi.org/10.1145/3510003.3510146),<br> by *Zhou Yang, Jieke Shi, Junda He and David Lo*
<br><br>
- [<img src=https://img.shields.io/badge/ICER-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3501385.3543957) [**Automatic Generation of Programming Exercises and Code Explanations
Using Large Language Models**](https://doi.org/10.1145/3501385.3543957),<br> by *Sami Sarsa, Paul Denny, Arto Hellas and Juho Leinonen*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.03374) [**Evaluating Large Language Models Trained on Code**](https://arxiv.org/abs/2107.03374),<br> by *Mark Chen, Jerry Tworek, Heewoo Jun, Qiming Yuan, Henrique Pond\'e de Oliveira Pinto, Jared Kaplan, Harrison Edwards, Yuri Burda et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.685) [**CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models
for Code Understanding and Generation**](https://doi.org/10.18653/v1/2021.emnlp-main.685),<br> by *Yue Wang, Weishi Wang, Shafiq R. Joty and Steven C. H. Hoi*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/c16a5320fa475530d9583c34fd356ef5-Abstract-round1.html) [**CodeXGLUE: A Machine Learning Benchmark Dataset for Code Understanding
and Generation**](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/c16a5320fa475530d9583c34fd356ef5-Abstract-round1.html),<br> by *Shuai Lu, Daya Guo, Shuo Ren, Junjie Huang, Alexey Svyatkovskiy, Ambrosio Blanco, Colin B. Clement, Dawn Drain et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.211) [**Unified Pre-training for Program Understanding and Generation**](https://doi.org/10.18653/v1/2021.naacl-main.211),<br> by *Wasi Uddin Ahmad, Saikat Chakraborty, Baishakhi Ray and Kai-Wei Chang*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/ICSE43902.2021.00040) [**Traceability Transformed: Generating more Accurate Links with Pre-Trained
BERT Models**](https://doi.org/10.1109/ICSE43902.2021.00040),<br> by *Jinfeng Lin, Yalin Liu, Qingkai Zeng, Meng Jiang and Jane Cleland-Huang*
<br><br>
- [<img src=https://img.shields.io/badge/FSE-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3368089.3417058) [**IntelliCode compose: code generation using transformer**](https://doi.org/10.1145/3368089.3417058),<br> by *Alexey Svyatkovskiy, Shao Kun Deng, Shengyu Fu and Neel Sundaresan*
<br><br>
- [<img src=https://img.shields.io/badge/ASE-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3324884.3416591) [**Multi-task Learning based Pre-trained Language Model for Code Completion**](https://doi.org/10.1145/3324884.3416591),<br> by *Fang Liu, Ge Li, Yunfei Zhao and Zhi Jin*
<br><br>
#### Code Representation

- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.findings-naacl.80) [**CODE-MVP: Learning to Represent Source Code from Multiple Views
with Contrastive Pre-Training**](https://doi.org/10.18653/v1/2022.findings-naacl.80),<br> by *Xin Wang, Yasheng Wang, Yao Wan, Jiawei Wang, Pingyi Zhou, Li Li, Hao Wu and Jin Liu*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.499) [**UniXcoder: Unified Cross-Modal Pre-training for Code Representation**](https://doi.org/10.18653/v1/2022.acl-long.499),<br> by *Daya Guo, Shuai Lu, Nan Duan, Yanlin Wang, Ming Zhou and Jian Yin*
<br><br>
- [<img src=https://img.shields.io/badge/ASE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3551349.3556900) [**AST-Probe: Recovering abstract syntax trees from hidden representations
of pre-trained language models**](https://doi.org/10.1145/3551349.3556900),<br> by *Jos\'e Antonio Hern\'andez L\'opez, Martin Weyssow, Jes\'us S\'anchez Cuadrado and Houari A. Sahraoui*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=jLoC4ez43PZ) [**GraphCodeBERT: Pre-training Code Representations with Data Flow**](https://openreview.net/forum?id=jLoC4ez43PZ),<br> by *Daya Guo, Shuo Ren, Shuai Lu, Zhangyin Feng, Duyu Tang, Shujie Liu, Long Zhou, Nan Duan et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2108.04556) [**CLSEBERT: Contrastive Learning for Syntax Enhanced Code Pre-Trained
Model**](https://arxiv.org/abs/2108.04556),<br> by *Xin Wang, Yasheng Wang, Pingyi Zhou, Fei Mi, Meng Xiao, Yadao Wang, Li Li, Xiao Liu et al.*
<br><br>
#### Code Fixing

- [<img src=https://img.shields.io/badge/ISSTA-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3533767.3534219) [**CIRCLE: continual repair across programming languages**](https://doi.org/10.1145/3533767.3534219),<br> by *Wei Yuan, Quanjun Zhang, Tieke He, Chunrong Fang, Nguyen Quoc Viet Hung, Xiaodong Hao and Hongzhi Yin*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.57) [**Detect-Localize-Repair: A Unified Framework for Learning to Debug
with CodeT5**](https://aclanthology.org/2022.findings-emnlp.57),<br> by *Nghi Bui, Yue Wang and Steven C. H. Hoi*
<br><br>
- [<img src=https://img.shields.io/badge/WASA-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-031-19211-1\_11) [**Multi-view Pre-trained Model for Code Vulnerability Identification**](https://doi.org/10.1007/978-3-031-19211-1\_11),<br> by *Xuxiang Jiang, Yinhao Xiao, Jun Wang and Wei Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3524459.3527350) [**Towards JavaScript program repair with Generative Pre-trained Transformer
(GPT-2)**](https://doi.org/10.1145/3524459.3527350),<br> by *M\'ark Lajk\'o, Viktor Csuvik and L\'aszl\'o Vid\'acs*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510003.3510042) [**Fast Changeset-based Bug Localization with BERT**](https://doi.org/10.1145/3510003.3510042),<br> by *Agnieszka Ciborowska and Kostadin Damevski*
<br><br>
- [<img src=https://img.shields.io/badge/MSR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/MSR52588.2021.00063) [**Applying CodeBERT for Automated Program Repair of Java Simple Bugs**](https://doi.org/10.1109/MSR52588.2021.00063),<br> by *Ehsan Mashhadi and Hadi Hemmati*
<br><br>
- [<img src=https://img.shields.io/badge/Applied_Sciences-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.mdpi.com/2076-3417/11/11/4755) [**A model with iterative trials for correcting logic errors in source code**](https://www.mdpi.com/2076-3417/11/11/4755),<br> by *Matsumoto, Taku, Watanobe, Yutaka and Nakamura, Keita*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2105.09352) [**DeepDebug: Fixing Python Bugs Using Stack Traces, Backtranslation,
and Code Skeletons**](https://arxiv.org/abs/2105.09352),<br> by *Dawn Drain, Colin B. Clement, Guillermo Serrato and Neel Sundaresan*
<br><br>
#### Code Review

- [<img src=https://img.shields.io/badge/FSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3540250.3549099) [**AUGER: automatically generating review comments with pre-training
models**](https://doi.org/10.1145/3540250.3549099),<br> by *Lingwei Li, Li Yang, Huaxi Jiang, Jun Yan, Tiejian Luo, Zihan Hua, Geng Liang and Chun Zuo*
<br><br>
- [<img src=https://img.shields.io/badge/FSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3540250.3549081) [**Automating code review activities by large-scale pre-training**](https://doi.org/10.1145/3540250.3549081),<br> by *Zhiyu Li, Shuai Lu, Daya Guo, Nan Duan, Shailesh Jannu, Grant Jenks, Deep Majumder, Jared Green et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510003.3510062) [**Bridging Pre-trained Models and Downstream Tasks for Source Code Understanding**](https://doi.org/10.1145/3510003.3510062),<br> by *Deze Wang, Zhouyang Jia, Shanshan Li, Yue Yu, Yun Xiong, Wei Dong and Xiangke Liao*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510003.3510621) [**Using Pre-Trained Models to Boost Code Review Automation**](https://doi.org/10.1145/3510003.3510621),<br> by *Rosalia Tufano, Simone Masiero, Antonio Mastropaolo, Luca Pascarella, Denys Poshyvanyk and Gabriele Bavota*
<br><br>
- [<img src=https://img.shields.io/badge/ICSE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3510003.3510050) [**What Do They Capture? - A Structural Analysis of Pre-Trained Language
Models for Source Code**](https://doi.org/10.1145/3510003.3510050),<br> by *Yao Wan, Wei Zhao, Hongyu Zhang, Yulei Sui, Guandong Xu and Hai Jin*
<br><br>
### Software Engineering

- [<img src=https://img.shields.io/badge/IJCAI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.24963/ijcai.2022/775) [**Deep Learning Meets Software Engineering: A Survey on Pre-Trained
Models of Source Code**](https://doi.org/10.24963/ijcai.2022/775),<br> by *Changan Niu, Chuanyi Li, Bin Luo and Vincent Ng*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.10623) [**Do Pre-trained Language Models Indeed Understand Software Engineering
Tasks?**](https://doi.org/10.48550/arXiv.2211.10623),<br> by *Yao Li, Tao Zhang, Xiapu Luo, Haipeng Cai, Sen Fang and Dawei Yuan*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2104.05861) [**Evaluating Pre-Trained Models for User Feedback Analysis in Software
Engineering: A Study on Classification of App-Reviews**](https://arxiv.org/abs/2104.05861),<br> by *Mohammad Abdul Hadi and Fatemeh H. Fard*
<br><br>
- [<img src=https://img.shields.io/badge/ASE-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/ASE51524.2021.9678927) [**What do pre-trained code models know about code?**](https://doi.org/10.1109/ASE51524.2021.9678927),<br> by *Anjan Karmakar and Romain Robbes*
<br><br>
- [<img src=https://img.shields.io/badge/ICSME-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ieeexplore.ieee.org/abstract/document/9240704/) [**Sentiment analysis for software engineering: How far can pre-trained transformer models go?**](https://ieeexplore.ieee.org/abstract/document/9240704/),<br> by *Zhang, Ting, Xu, Bowen, Thung, Ferdian, Haryono, Stefanus Agus, Lo, David and Jiang, Lingxiao*
<br><br>
### AIGC

- [<img src=https://img.shields.io/badge/OpenAI-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) [**GPT-4 Technical Report**](https://cdn.openai.com/papers/gpt-4.pdf), [<img src=https://img.shields.io/badge/GPT--4-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) <br> by *OpenAI*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4-system-card.pdf) [**GPT-4 System Card**](https://cdn.openai.com/papers/gpt-4-system-card.pdf), [<img src=https://img.shields.io/badge/GPT--4-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) <br> by *OpenAI*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.01580) [**Mixture of Soft Prompts for Controllable Data Generation**](https://doi.org/10.48550/arXiv.2303.01580),<br> by *Derek Chen, Celine Lee, Yunan Lu, Domenic Rosati and Zhou Yu*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2209.12356) [**News Summarization and Evaluation in the Era of GPT-3**](https://doi.org/10.48550/arXiv.2209.12356),<br> by *Tanya Goyal, Junyi Jessy Li and Greg Durrett*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.471) [**Fine-Grained Controllable Text Generation Using Non-Residual Prompting**](https://doi.org/10.18653/v1/2022.acl-long.471),<br> by *Fredrik Carlsson, Joey \"Ohman, Fangyu Liu, Severine Verlinden, Joakim Nivre and Magnus Sahlgren*
<br><br>
- [<img src=https://img.shields.io/badge/JKSUCIS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1016/j.jksuci.2020.04.001) [**The survey: Text generation models in deep learning**](https://doi.org/10.1016/j.jksuci.2020.04.001),<br> by *Touseef Iqbal and Shaima Qureshi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.04624) [**Factuality Enhanced Language Models for Open-Ended Text Generation**](https://doi.org/10.48550/arXiv.2206.04624),<br> by *Nayeon Lee, Wei Ping, Peng Xu, Mostofa Patwary, Mohammad Shoeybi and Bryan Catanzaro*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.491) [**FewshotQA: A simple framework for few-shot learning of question
answering tasks using pre-trained text-to-text models**](https://doi.org/10.18653/v1/2021.emnlp-main.491),<br> by *Rakesh Chada and Pradeep Natarajan*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2103.10360) [**All NLP Tasks Are Generation Tasks: A General Pretraining Framework**](https://arxiv.org/abs/2103.10360),<br> by *Zhengxiao Du, Yujie Qian, Xiao Liu, Ming Ding, Jiezhong Qiu, Zhilin Yang and Jie Tang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.57) [**Smelting Gold and Silver for Improved Multilingual AMR-to-Text Generation**](https://doi.org/10.18653/v1/2021.emnlp-main.57),<br> by *Leonardo F. R. Ribeiro, Jonas Pfeiffer, Yue Zhang and Iryna Gurevych*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-short.40) [**PRAL: A Tailored Pre-Training Model for Task-Oriented Dialog Generation**](https://doi.org/10.18653/v1/2021.acl-short.40),<br> by *Jing Gu, Qingyang Wu, Chongruo Wu, Weiyan Shi and Zhou Yu*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/17527) [**DialogBERT: Discourse-Aware Response Generation via Learning to Recover
and Rank Utterances**](https://ojs.aaai.org/index.php/AAAI/article/view/17527),<br> by *Xiaodong Gu, Kang Min Yoo and Jung-Woo Ha*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.501) [**DYPLOC: Dynamic Planning of Content Using Mixed Language Models
for Text Generation**](https://doi.org/10.18653/v1/2021.acl-long.501),<br> by *Xinyu Hua, Ashwin Sreevatsa and Lu Wang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.265) [**Latent Reasoning for Low-Resource Question Generation**](https://doi.org/10.18653/v1/2021.findings-acl.265),<br> by *Xinting Huang, Jianzhong Qi, Yu Sun and Rui Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.223) [**JointGT: Graph-Text Joint Representation Learning for Text Generation
from Knowledge Graphs**](https://doi.org/10.18653/v1/2021.findings-acl.223),<br> by *Pei Ke, Haozhe Ji, Yu Ran, Xin Cui, Liwei Wang, Linfeng Song, Xiaoyan Zhu and Minlie Huang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-demo.4) [**TextBox: A Unified, Modularized, and Extensible Framework for Text
Generation**](https://doi.org/10.18653/v1/2021.acl-demo.4),<br> by *Junyi Li, Tianyi Tang, Gaole He, Jinhao Jiang, Xiaoxuan Hu, Puzhao Xie, Zhipeng Chen, Zhuohao Yu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.136) [**Few-shot Knowledge Graph-to-Text Generation with Pretrained Language
Models**](https://doi.org/10.18653/v1/2021.findings-acl.136),<br> by *Junyi Li, Tianyi Tang, Wayne Xin Zhao, Zhicheng Wei, Nicholas Jing Yuan and Ji-Rong Wen*
<br><br>
- [<img src=https://img.shields.io/badge/SIGIR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3404835.3462865) [**Knowledge-based Review Generation by Coherence Enhanced Text Planning**](https://doi.org/10.1145/3404835.3462865),<br> by *Junyi Li, Wayne Xin Zhao, Zhicheng Wei, Nicholas Jing Yuan and Ji-Rong Wen*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.353) [**Prefix-Tuning: Optimizing Continuous Prompts for Generation**](https://doi.org/10.18653/v1/2021.acl-long.353),<br> by *Xiang Lisa Li and Percy Liang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.36) [**GLGE: A New General Language Generation Evaluation Benchmark**](https://doi.org/10.18653/v1/2021.findings-acl.36),<br> by *Dayiheng Liu, Yu Yan, Yeyun Gong, Weizhen Qi, Hang Zhang, Jian Jiao, Weizhu Chen, Jie Fu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.173) [**A Three-Stage Learning Framework for Low-Resource Knowledge-Grounded
Dialogue Generation**](https://doi.org/10.18653/v1/2021.emnlp-main.173),<br> by *Shilei Liu, Xiaofeng Zhao, Bochao Li, Feiliang Ren, Longhui Zhang and Shujuan Yin*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.308) [**VECO: Variable and Flexible Cross-lingual Pre-training for Language
Understanding and Generation**](https://doi.org/10.18653/v1/2021.acl-long.308),<br> by *Fuli Luo, Wei Wang, Jiahao Liu, Yijia Liu, Bin Bi, Songfang Huang, Fei Huang and Luo Si*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.340) [**Ask what's missing and what's useful: Improving Clarification Question
Generation using Global Knowledge**](https://doi.org/10.18653/v1/2021.naacl-main.340),<br> by *Bodhisattwa Prasad Majumder, Sudha Rao, Michel Galley and Julian J. McAuley*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.248) [**ZmBART: An Unsupervised Cross-lingual Transfer Framework for Language
Generation**](https://doi.org/10.18653/v1/2021.findings-acl.248),<br> by *Kaushal Kumar Maurya, Maunendra Sankar Desarkar, Yoshinobu Kano and Kumari Deepshikha*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.351) [**Structural Adapters in Pretrained Language Models for AMR-to-Text
Generation**](https://doi.org/10.18653/v1/2021.emnlp-main.351),<br> by *Leonardo F. R. Ribeiro, Yue Zhang and Iryna Gurevych*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.115) [**Towards Table-to-Text Generation with Numerical Reasoning**](https://doi.org/10.18653/v1/2021.acl-long.115),<br> by *Lya Hulliyyatus Suadaa, Hidetaka Kamigaito, Kotaro Funakoshi, Manabu Okumura and Hiroya Takamura*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2107.02137) [**ERNIE 3.0: Large-scale Knowledge Enhanced Pre-training for Language
Understanding and Generation**](https://arxiv.org/abs/2107.02137),<br> by *Yu Sun, Shuohuan Wang, Shikun Feng, Siyu Ding, Chao Pang, Junyuan Shang, Jiaxiang Liu, Xuyi Chen et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.341) [**Progressive Generation of Long Text with Pretrained Language Models**](https://doi.org/10.18653/v1/2021.naacl-main.341),<br> by *Bowen Tan, Zichao Yang, Maruan Al-Shedivat, Eric P. Xing and Zhiting Hu*
<br><br>
- [<img src=https://img.shields.io/badge/ECIR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-030-72113-8\_46) [**Consistency and Coherency Enhanced Story Generation**](https://doi.org/10.1007/978-3-030-72113-8\_46),<br> by *Wei Wang, Piji Li and Hai-Tao Zheng*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.200) [**Structure-Aware Pre-Training for Table-to-Text Generation**](https://doi.org/10.18653/v1/2021.findings-acl.200),<br> by *Xinyu Xing and Xiaojun Wan*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.95) [**AugNLG: Few-shot Natural Language Generation using Self-trained Data
Augmentation**](https://doi.org/10.18653/v1/2021.acl-long.95),<br> by *Xinnuo Xu, Guoyin Wang, Young-Bum Kim and Sungjin Lee*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.6) [**DeepRapper: Neural Rap Generation with Rhyme and Rhythm Modeling**](https://doi.org/10.18653/v1/2021.acl-long.6),<br> by *Lanqing Xue, Kaitao Song, Duocai Wu, Xu Tan, Nevin L. Zhang, Tao Qin, Wei-Qiang Zhang and Tie-Yan Liu*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-demo.26) [**FastSeq: Make Sequence Generation Faster**](https://doi.org/10.18653/v1/2021.acl-demo.26),<br> by *Yu Yan, Fei Hu, Jiusheng Chen, Nikhil Bhendawade, Ting Ye, Yeyun Gong, Nan Duan, Desheng Cui et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.392) [**A Simple and Efficient Multi-Task Learning Approach for Conditioned
Dialogue Generation**](https://doi.org/10.18653/v1/2021.naacl-main.392),<br> by *Yan Zeng and Jian-Yun Nie*
<br><br>
- [<img src=https://img.shields.io/badge/SIGIR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3404835.3463037) [**DSGPT: Domain-Specific Generative Pre-Training of Transformers for
Text Generation in E-commerce Title and Review Summarization**](https://doi.org/10.1145/3404835.3463037),<br> by *Xueying Zhang, Yunjiang Jiang, Yue Shang, Zhaomeng Cheng, Chi Zhang, Xiaochuan Fan, Yun Xiao and Bo Long*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) [**Language Models are Few-Shot Learners**](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html), [<img src=https://img.shields.io/badge/GPT--3-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html) <br> by *Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.9) [**PLATO: Pre-trained Dialogue Generation Model with Discrete Latent
Variable**](https://doi.org/10.18653/v1/2020.acl-main.9),<br> by *Siqi Bao, Huang He, Fan Wang, Hua Wu and Haifeng Wang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.14799) [**Evaluation of Text Generation: A Survey**](https://arxiv.org/abs/2006.14799),<br> by *Asli Celikyilmaz, Elizabeth Clark and Jianfeng Gao*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.697) [**KGPT: Knowledge-Grounded Pre-Training for Data-to-Text Generation**](https://doi.org/10.18653/v1/2020.emnlp-main.697),<br> by *Wenhu Chen, Yu Su, Xifeng Yan and William Yang Wang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.705) [**Distilling Knowledge Learned in BERT for Text Generation**](https://doi.org/10.18653/v1/2020.acl-main.705),<br> by *Yen-Chun Chen, Zhe Gan, Yu Cheng, Jingzhou Liu and Jingjing Liu*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.190) [**Logic2Text: High-Fidelity Natural Language Generation from Logical
Forms**](https://doi.org/10.18653/v1/2020.findings-emnlp.190),<br> by *Zhiyu Chen, Wenhu Chen, Hanwen Zha, Xiyou Zhou, Yunkai Zhang, Sairam Sundaresan and William Yang Wang*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/6256) [**Cross-Lingual Natural Language Generation via Pre-Training**](https://ojs.aaai.org/index.php/AAAI/article/view/6256),<br> by *Zewen Chi, Li Dong, Furu Wei, Wenhui Wang, Xian-Ling Mao and Heyan Huang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2007.15780) [**Neural Language Generation: Formulation, Methods, and Evaluation**](https://arxiv.org/abs/2007.15780),<br> by *Cristina Garbacea and Qiaozhu Mei*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.coling-main.179) [**TableGPT: Few-shot Table-to-Text Generation with Table Structure Reconstruction
and Content Matching**](https://doi.org/10.18653/v1/2020.coling-main.179),<br> by *Heng Gong, Yawei Sun, Xiaocheng Feng, Bing Qin, Wei Bi, Xiaojiang Liu and Ting Liu*
<br><br>
- [<img src=https://img.shields.io/badge/TACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1162/tacl\_a\_00302) [**A Knowledge-Enhanced Pretraining Model for Commonsense Story Generation**](https://doi.org/10.1162/tacl\_a\_00302),<br> by *Jian Guan, Fei Huang, Minlie Huang, Zhihao Zhao and Xiaoyan Zhu*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.coling-main.218) [**Have Your Text and Use It Too! End-to-End Neural Data-to-Text Generation
with Semantic Fidelity**](https://doi.org/10.18653/v1/2020.coling-main.218),<br> by *Hamza Harkous, Isabel Groves and Amir Saffari*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.55) [**Reformulating Unsupervised Style Transfer as Paraphrase Generation**](https://doi.org/10.18653/v1/2020.emnlp-main.55),<br> by *Kalpesh Krishna, John Wieting and Mohit Iyyer*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.703) [**BART: Denoising Sequence-to-Sequence Pre-training for Natural Language
Generation, Translation, and Comprehension**](https://doi.org/10.18653/v1/2020.acl-main.703),<br> by *Mike Lewis, Yinhan Liu, Naman Goyal, Marjan Ghazvininejad, Abdelrahman Mohamed, Omer Levy, Veselin Stoyanov and Luke Zettlemoyer*
<br><br>
- [<img src=https://img.shields.io/badge/CIKM-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3340531.3411893) [**Knowledge-Enhanced Personalized Review Generation with Capsule Graph
Neural Network**](https://doi.org/10.1145/3340531.3411893),<br> by *Junyi Li, Siqing Li, Wayne Xin Zhao, Gaole He, Zhicheng Wei, Nicholas Jing Yuan and Ji-Rong Wen*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.68) [**Rigid Formats Controlled Text Generation**](https://doi.org/10.18653/v1/2020.acl-main.68),<br> by *Piji Li, Haisong Zhang, Xiaojiang Liu and Shuming Shi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2002.06353) [**UniViLM: A Unified Video and Language Pre-Training Model for Multimodal
Understanding and Generation**](https://arxiv.org/abs/2002.06353),<br> by *Huaishao Luo, Lei Ji, Botian Shi, Haoyang Huang, Nan Duan, Tianrui Li, Xilin Chen and Ming Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.167) [**GPT-too: A Language-Model-First Approach for AMR-to-Text Generation**](https://doi.org/10.18653/v1/2020.acl-main.167),<br> by *Manuel Mager, Ram\'on Fernandez Astudillo, Tahira Naseem, Md. Arafat Sultan, Young-Suk Lee, Radu Florian and Salim Roukos*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.17) [**Few-shot Natural Language Generation for Task-Oriented Dialog**](https://doi.org/10.18653/v1/2020.findings-emnlp.17),<br> by *Baolin Peng, Chenguang Zhu, Chunyuan Li, Xiujun Li, Jinchao Li, Michael Zeng and Jianfeng Gao*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.349) [**PlotMachines: Outline-Conditioned Generation with Dynamic Plot State
Tracking**](https://doi.org/10.18653/v1/2020.emnlp-main.349),<br> by *Hannah Rashkin, Asli Celikyilmaz, Yejin Choi and Jianfeng Gao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2007.08426) [**Investigating Pretrained Language Models for Graph-to-Text Generation**](https://arxiv.org/abs/2007.08426),<br> by *Leonardo F. R. Ribeiro, Martin Schmitt, Hinrich Sch\"utze and Iryna Gurevych*
<br><br>
- [<img src=https://img.shields.io/badge/TACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1162/tacl\_a\_00313) [**Leveraging Pre-trained Checkpoints for Sequence Generation Tasks**](https://doi.org/10.1162/tacl\_a\_00313),<br> by *Sascha Rothe, Shashi Narayan and Aliaksei Severyn*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.495) [**T3: Tree-Autoencoder Constrained Adversarial Text Generation for
Targeted Attack**](https://doi.org/10.18653/v1/2020.emnlp-main.495),<br> by *Boxin Wang, Hengzhi Pei, Boyuan Pan, Qian Chen, Shuohang Wang and Bo Li*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.226) [**MEGATRON-CNTRL: Controllable Story Generation with External Knowledge
Using Large-Scale Language Models**](https://doi.org/10.18653/v1/2020.emnlp-main.226),<br> by *Peng Xu, Mostofa Patwary, Mohammad Shoeybi, Raul Puri, Pascale Fung, Anima Anandkumar and Bryan Catanzaro*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.140) [**StyleDGPT: Stylized Response Generation with Pre-trained Language
Models**](https://doi.org/10.18653/v1/2020.findings-emnlp.140),<br> by *Ze Yang, Wei Wu, Can Xu, Xinnian Liang, Jiaqi Bai, Liran Wang, Wei Wang and Zhoujun Li*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2010.11140) [**Generalized Conditioned Dialogue Generation Based on Pre-trained Language
Model**](https://arxiv.org/abs/2010.11140),<br> by *Yan Zeng and Jian-Yun Nie*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=SkeHuCVFDr) [**BERTScore: Evaluating Text Generation with BERT**](https://openreview.net/forum?id=SkeHuCVFDr),<br> by *Tianyi Zhang, Varsha Kishore, Felix Wu, Kilian Q. Weinberger and Yoav Artzi*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-demos.30) [**DIALOGPT : Large-Scale Generative Pre-training for Conversational
Response Generation**](https://doi.org/10.18653/v1/2020.acl-demos.30),<br> by *Yizhe Zhang, Siqi Sun, Michel Galley, Yen-Chun Chen, Chris Brockett, Xiang Gao, Jianfeng Gao, Jingjing Liu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) [**Language Models are Unsupervised Multitask Learners**](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf), [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) <br> by *Radford, Alec, Wu, Jeffrey, Child, Rewon, Luan, David, Amodei, Dario and Sutskever, Ilya*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2019/hash/c20bb2d9a50d5ac1f713f8b34d9aac5a-Abstract.html) [**Unified Language Model Pre-training for Natural Language Understanding
and Generation**](https://proceedings.neurips.cc/paper/2019/hash/c20bb2d9a50d5ac1f713f8b34d9aac5a-Abstract.html),<br> by *Li Dong, Nan Yang, Wenhui Wang, Furu Wei, Xiaodong Liu, Yu Wang, Jianfeng Gao, Ming Zhou et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/p19-1608) [**Large-Scale Transfer Learning for Natural Language Generation**](https://doi.org/10.18653/v1/p19-1608),<br> by *Sergey Golovanov, Rauf Kurbanov, Sergey I. Nikolenko, Kyryl Truskovskyi, Alexander Tselousov and Thomas Wolf*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/D19-1615) [**Improving Neural Story Generation by Targeted Common Sense Grounding**](https://doi.org/10.18653/v1/D19-1615),<br> by *Huanru Henry Mao, Bodhisattwa Prasad Majumder, Julian J. McAuley and Garrison W. Cottrell*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://proceedings.mlr.press/v97/song19d.html) [**MASS: Masked Sequence to Sequence Pre-training for Language Generation**](http://proceedings.mlr.press/v97/song19d.html),<br> by *Kaitao Song, Xu Tan, Tao Qin, Jianfeng Lu and Tie-Yan Liu*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2018-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=Hyg0vbWC-) [**Generating Wikipedia by Summarizing Long Sequences**](https://openreview.net/forum?id=Hyg0vbWC-),<br> by *Peter J. Liu, Mohammad Saleh, Etienne Pot, Ben Goodrich, Ryan Sepassi, Lukasz Kaiser and Noam Shazeer*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2018-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) [**Improving language understanding by generative pre-training**](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf), [<img src=https://img.shields.io/badge/GPT--1-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) <br> by *Radford, Alec, Narasimhan, Karthik, Salimans, Tim, Sutskever, Ilya and others*
<br><br>
#### Controllable Text Generation

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.13636) [**Quark: Controllable Text Generation with Reinforced Unlearning**](https://doi.org/10.48550/arXiv.2205.13636),<br> by *Ximing Lu, Sean Welleck, Liwei Jiang, Jack Hessel, Lianhui Qin, Peter West, Prithviraj Ammanabrolu and Yejin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.502) [**Controllable Open-ended Question Generation with A New Question
Type Ontology**](https://doi.org/10.18653/v1/2021.acl-long.502),<br> by *Shuyang Cao and Lu Wang*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=jWkw45-9AbL) [**A Distributional Approach to Controlled Text Generation**](https://openreview.net/forum?id=jWkw45-9AbL),<br> by *Muhammad Khalifa, Hady Elsahar and Marc Dymetman*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-emnlp.334) [**A Plug-and-Play Method for Controlled Text Generation**](https://doi.org/10.18653/v1/2021.findings-emnlp.334),<br> by *Damian Pascual, Beni Egressy, Clara Meister, Ryan Cotterell and Roger Wattenhofer*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=3k20LAiHYL2) [**Pre-training Text-to-Text Transformers for Concept-centric Common
Sense**](https://openreview.net/forum?id=3k20LAiHYL2),<br> by *Wangchunshu Zhou, Dong-Ho Lee, Ravi Kiran Selvam, Seyeon Lee and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.9) [**Mention Flags (MF): Constraining Transformer-based Text Generators**](https://doi.org/10.18653/v1/2021.acl-long.9),<br> by *Yufei Wang, Ian D. Wood, Stephen Wan, Mark Dras and Mark Johnson*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=H1edEyBKDS) [**Plug and Play Language Models: A Simple Approach to Controlled Text
Generation**](https://openreview.net/forum?id=H1edEyBKDS),<br> by *Sumanth Dathathri, Andrea Madotto, Janice Lan, Jane Hung, Eric Frank, Piero Molino, Jason Yosinski and Rosanne Liu*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.165) [**CommonGen: A Constrained Text Generation Challenge for Generative
Commonsense Reasoning**](https://doi.org/10.18653/v1/2020.findings-emnlp.165),<br> by *Bill Yuchen Lin, Wangchunshu Zhou, Ming Shen, Pei Zhou, Chandra Bhagavatula, Yejin Choi and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1909.05858) [**CTRL: A Conditional Transformer Language Model for Controllable
Generation**](http://arxiv.org/abs/1909.05858),<br> by *Nitish Shirish Keskar, Bryan McCann, Lav R. Varshney, Caiming Xiong and Richard Socher*
<br><br>
### Continual Learning

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.01081) [**Can BERT Refrain from Forgetting on Sequential Tasks? A Probing
Study**](https://doi.org/10.48550/arXiv.2303.01081),<br> by *Mingxu Tao, Yansong Feng and Dongyan Zhao*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/CVPR52688.2022.00024) [**Learning to Prompt for Continual Learning**](https://doi.org/10.1109/CVPR52688.2022.00024),<br> by *Zifeng Wang, Zizhao Zhang, Chen-Yu Lee, Han Zhang, Ruoxi Sun, Xiaoqi Ren, Guolong Su, Vincent Perot et al.*
<br><br>
- [<img src=https://img.shields.io/badge/T--PAMI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/TPAMI.2021.3057446) [**A Continual Learning Survey: Defying Forgetting in Classification
Tasks**](https://doi.org/10.1109/TPAMI.2021.3057446),<br> by *Matthias De Lange, Rahaf Aljundi, Marc Masana, Sarah Parisot, Xu Jia, Ales Leonardis, Gregory G. Slabaugh and Tinne Tuytelaars*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.findings-acl.220) [**ELLE: Efficient Lifelong Pre-training for Emerging Data**](https://doi.org/10.18653/v1/2022.findings-acl.220),<br> by *Yujia Qin, Jiajie Zhang, Yankai Lin, Zhiyuan Liu, Peng Li, Maosong Sun and Jie Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.351) [**Lifelong Pretraining: Continually Adapting Language Models to Emerging
Corpora**](https://doi.org/10.18653/v1/2022.naacl-main.351),<br> by *Xisen Jin, Dejiao Zhang, Henghui Zhu, Wei Xiao, Shang-Wen Li, Xiaokai Wei, Andrew O. Arnold and Xiang Ren*
<br><br>
- [<img src=https://img.shields.io/badge/JAIR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1613/jair.1.13673) [**Towards Continual Reinforcement Learning: A Review and Perspectives**](https://doi.org/10.1613/jair.1.13673),<br> by *Khimya Khetarpal, Matthew Riemer, Irina Rish and Doina Precup*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.408) [**Continual Pre-training of Language Models for Math Problem Understanding
with Syntax-Aware Memory Network**](https://doi.org/10.18653/v1/2022.acl-long.408),<br> by *Zheng Gong, Kun Zhou, Xin Zhao, Jing Sha, Shijin Wang and Ji-Rong Wen*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=HCRVf71PMF) [**LFPT5: A Unified Framework for Lifelong Few-shot Language Learning Based on Prompt Tuning of T5**](https://openreview.net/forum?id=HCRVf71PMF),<br> by *Chengwei Qin and Shafiq Joty*
<br>``
We define a challenging yet practical problem as Lifelong Few-shot Language Learning and propose a unified framework for it based on prompt tuning of T5.
``
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=vfsRB5MImo9) [**Towards Continual Knowledge Learning of Language Models**](https://openreview.net/forum?id=vfsRB5MImo9),<br> by *Joel Jang, Seonghyeon Ye, Sohee Yang, Joongbo Shin, Janghoon Han, Gyeonghun KIM, Stanley Jungkyu Choi and Minjoon Seo*
<br>``
We propose a novel continual learning formulation named Continual Knowledge Learning which allows large language models to constantly obtain new and updated knowledge while mitigating forgetting of previous learned time-invariant knowledge.
``
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=figzpGMrdD) [**Pretrained Language Model in Continual Learning: A Comparative Study**](https://openreview.net/forum?id=figzpGMrdD),<br> by *Tongtong Wu, Massimo Caccia, Zhuang Li, Yuan-Fang Li, Guilin Qi and Gholamreza Haffari*
<br>``
To explore the layer-wise property of pretrained languge models in continual learning, we thoroughly compare the continual learning performance over the combination of 5 PLMs and 4 veins of CL methods on 3 benchmarks in 2 typical incremental settings.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.418) [**TemporalWiki: A Lifelong Benchmark for Training and Evaluating Ever-Evolving
Language Models**](https://aclanthology.org/2022.emnlp-main.418),<br> by *Joel Jang, Seonghyeon Ye, Changho Lee, Sohee Yang, Joongbo Shin, Janghoon Han, Gyeonghun Kim and Minjoon Seo*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.mlr.press/v162/liska22a.html) [**StreamingQA: A Benchmark for Adaptation to New Knowledge over Time
in Question Answering Models**](https://proceedings.mlr.press/v162/liska22a.html),<br> by *Adam Liska, Tom\'as Kocisk\'y, Elena Gribovskaya, Tayfun Terzi, Eren Sezener, Devang Agrawal, Cyprien de Masson d'Autume, Tim Scholtes et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2021/hash/bcd0049c35799cdf57d06eaf2eb3cff6-Abstract.html) [**Achieving Forgetting Prevention and Knowledge Transfer in Continual
Learning**](https://proceedings.neurips.cc/paper/2021/hash/bcd0049c35799cdf57d06eaf2eb3cff6-Abstract.html),<br> by *Zixuan Ke, Bing Liu, Nianzu Ma, Hu Xu and Lei Shu*
<br>``
NeurIPS 2021, The key component of CTR is the CL-plugin inserted in BERT. A CL-plugin is a capsule network with a new transfer routing mechanism to encourage knowledge transfer among tasks and also to isolate task-specific knowledge to avoid forgetting.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.findings-emnlp.62) [**Learn Continually, Generalize Rapidly: Lifelong Knowledge Accumulation for Few-shot Learning**](https://aclanthology.org/2021.findings-emnlp.62),<br> by *Jin, Xisen , Lin, Bill Yuchen , Rostami, Mohammad  and Ren, Xiang*
<br>``
We present a new learning setup, Continual Learning of Few-Shot Learners, to address challenges of both learning settings in a unified setup, with a hyper-network for task-specific adapter generation.
``
<br><br>
- [<img src=https://img.shields.io/badge/EACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.eacl-main.95) [**Analyzing the Forgetting Problem in Pretrain-Finetuning of Open-domain
Dialogue Response Models**](https://doi.org/10.18653/v1/2021.eacl-main.95),<br> by *Tianxing He, Jun Liu, Kyunghyun Cho, Myle Ott, Bing Liu, James R. Glass and Fuchun Peng*
<br>``
Our major finding is that after standard finetuning, the model forgets some of the important language generation skills acquired during large-scale pretraining. We propose an intuitive finetuning strategy named “mix-review”: : For each finetuning epoch, we mix the target dialogue data with a random subset of the pretraining data, mix_ratio is 4, decay is 0.9.
``
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.121) [**K-Adapter: Infusing Knowledge into Pre-Trained Models with Adapters**](https://doi.org/10.18653/v1/2021.findings-acl.121),<br> by *Ruize Wang, Duyu Tang, Nan Duan, Zhongyu Wei, Xuanjing Huang, Jianshu Ji, Guihong Cao, Daxin Jiang et al.*
<br>``
We propose KADAPTER, a framework that retains the original parameters of the pre-trained model fixed
``<br>``
and supports the development of versatile
``<br>``
knowledge-infused model.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.emnlp-main.176) [**Domain-Lifelong Learning for Dialogue State Tracking via Knowledge Preservation Networks**](https://aclanthology.org/2021.emnlp-main.176),<br> by *Liu, Qingbin , Cao, Pengfei , Liu, Cao , Chen, Jiansong , Cai, Xunliang , Yang, Fan , He, Shizhu , Liu, Kang  et al.*
<br>``
This paper explores Domain-Lifelong Learning for Dialogue State Tracking, we propose Knowledge Preservation Network, which consists of multi-prototype enhanced retrospection and multi-strategy knowledge distillation, to solve the problems of expression diversity and combinatorial explosion in the DLL-DST task
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.emnlp-main.550) [**CLASSIC: Continual and Contrastive Learning of Aspect Sentiment Classification Tasks**](https://aclanthology.org/2021.emnlp-main.550),<br> by *Ke, Zixuan , Liu, Bing , Xu, Hu  and Shu, Lei*
<br>``
The key novelty is a contrastive continual learning method that enables both knowledge transfer across tasks and knowledge distillation from old tasks to the new task, which eliminates the need for task ids in testing.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.emnlp-main.233) [**Lifelong Explainer for Lifelong Learners**](https://aclanthology.org/2021.emnlp-main.233),<br> by *Situ, Xuelin , Maruf, Sameen , Zukerman, Ingrid , Paris, Cecile  and Haffari, Gholamreza*
<br>``
We propose a novel Lifelong Explanation approach that continuously trains a student explainer under the supervision of a teacher – an arbitrary explanation algorithm – on different tasks undertaken in LL. We also leverage the Experience Replay mechanism to prevent catastrophic forgetting in the student explainer.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.emnlp-main.737) [**A Unified Speaker Adaptation Approach for ASR**](https://aclanthology.org/2021.emnlp-main.737),<br> by *Yingzhu Zhao, Chongjia Ni, Cheung-Chi Leung, Shafiq R. Joty, Eng Siong Chng and Bin Ma*
<br>``
Prefix-based user identifier, Continual ASR / Architecture Search / Network Pruning.
``
<br><br>
- [<img src=https://img.shields.io/badge/SIGKDD-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3447548.3467162) [**Dynamic Language Models for Continuously Evolving Content**](https://doi.org/10.1145/3447548.3467162),<br> by *Amba Hombaiah, Spurthi, Chen, Tao, Zhang, Mingyang, Bendersky, Michael and Najork, Marc*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.acl-long.378) [**Parameter-Efficient Transfer Learning with Diff Pruning**](https://aclanthology.org/2021.acl-long.378),<br> by *Guo, Demi , Rush, Alexander  and Kim, Yoon*
<br>``
The approach learns a task-specific “diff” vector that extends the original pretrained parameters. As the number of tasks increases, diff pruning remains parameter-efficient, as it requires storing only a small diff vector for each task.
``
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.acl-long.20) [**Refining Sample Embeddings with Relation Prototypes to Enhance Continual Relation Extraction**](https://aclanthology.org/2021.acl-long.20),<br> by *Cui, Li , Yang, Deqing , Yu, Jiaxin , Hu, Chengwei , Cheng, Jiayang , Yi, Jingjie  and Xiao, Yanghua*
<br>``
To fully utilize memorized samples, in this paper, we employ relation prototype to extract useful information of each relation. 
``
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.acl-long.172) [**On the Effectiveness of Adapter-based Tuning for Pretrained Language Model Adaptation**](https://aclanthology.org/2021.acl-long.172),<br> by *He, Ruidan , Liu, Linlin , Ye, Hai , Tan, Qingyu , Ding, Bosheng , Cheng, Liying , Low, Jiawei , Bing, Lidong  et al.*
<br>``
we first show that adapter-based tuning better mitigates forgetting issues than fine-tuning since it yields representations with less deviation from those generated by the initial PrLM. Effectiveness: it tendsto outperform fine-tuning on both low-resource and cross-lingual tasks; 2 it demonstrates higher stability under different learning rates compared to fine-tuning.
``
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2021.acl-long.229) [**Rational LAMOL: A Rationale-based Lifelong Learning Framework**](https://aclanthology.org/2021.acl-long.229),<br> by *Kanwatchara, Kasidis , Horsuwan, Thanapapas , Lertvittayakumjorn, Piyawat , Kijsirikul, Boonserm  and Vateekul, Peerapon*
<br>``
Rational LAMOL enhances LAMOL, a recent LL model, by applying critical freezing guided by human rationales. When the human rationales are not available, we propose exploiting unsupervised generated rationales as substitutions.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL--HLT-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2021.naacl-main.93) [**Towards Continual Learning for Multilingual Machine Translation via Vocabulary Substitution**](https://www.aclweb.org/anthology/2021.naacl-main.93),<br> by *Garcia, Xavier , Constant, Noah , Parikh, Ankur  and Firat, Orhan*
<br>``
Introducing the catastrophic forgetting problem in incremental multi-language translation, and utilizing a vocabulary substitution manner to alleviate the above problem.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL--HLT-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2021.naacl-main.218) [**Continual Learning for Text Classification with Information Disentanglement Based Regularization**](https://www.aclweb.org/anthology/2021.naacl-main.218),<br> by *Huang, Yufan , Zhang, Yanzhe , Chen, Jiaao , Wang, Xuezhi  and Yang, Diyi*
<br>``
Proposing a regularization-based method for continual text classification, introducing the next sentence prediction and task id prediction as auxiliary tasks.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL--HLT-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2021.naacl-main.106) [**Incremental Few-shot Text Classification with Multi-round New Classes: Formulation, Dataset and System**](https://www.aclweb.org/anthology/2021.naacl-main.106),<br> by *Xia, Congying , Yin, Wenpeng , Feng, Yihao  and Yu, Philip*
<br>``
Proposing a new setting and respective benchmark for few-shot incremental text classification, modeling continual text classification with text entailment.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL--HLT-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2021.naacl-main.212) [**Hyperparameter-free Continuous Learning for Domain Classification in Natural Language Understanding**](https://www.aclweb.org/anthology/2021.naacl-main.212),<br> by *Hua, Ting , Shen, Yilin , Zhao, Changsheng , Hsu, Yen-Chang  and Jin, Hongxia*
<br>``
Inspired by EWC and proposing a hyperparameter-free (Fisher information-based) sampling method for memory replay.
``
<br><br>
- [<img src=https://img.shields.io/badge/EACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2021.eacl-main.317) [**Lifelong Knowledge-Enriched Social Event Representation Learning**](https://www.aclweb.org/anthology/2021.eacl-main.317),<br> by *Vijayaraghavan, Prashanth  and Roy, Deb*
<br>``
Proposing a rehearsal-based method, i.e.,Domain-Representative Episodic Memory Replay (DR-EMR), for lifelong event representation with embedding alignment and external social commonsense knowledge.
``
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2108.04445) [**Lifelong Intent Detection via Multi-Strategy Rebalancing**](https://arxiv.org/abs/2108.04445),<br> by *Qingbin Liu, Xiaoyan Yu, Shizhu He, Kang Liu and Jun Zhao*
<br>``
We propose the lifelong intent detection task to handle continually emerging user intents. And, we propose multistrategy rebalancing to address multiple adverse effects caused by the data imbalance problem.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.634) [**Recall and Learn: Fine-tuning Deep Pretrained Language Models with
Less Forgetting**](https://doi.org/10.18653/v1/2020.emnlp-main.634),<br> by *Sanyuan Chen, Yutai Hou, Yiming Cui, Wanxiang Che, Ting Liu and Xiangzhan Yu*
<br>``
We propose a recall and learn mechanism, which adopts the idea of multi-task learning and jointly learns pretraining tasks and downstream tasks. Specifically, we introduce a Pretraining Simulation mechanism to recall the knowledge from pretraining tasks without data, and an Objective Shifting mechanism to focus the learning on downstream tasks gradually.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.findings-emnlp.41) [**Exploring Versatile Generative Language Model Via Parameter-Efficient
Transfer Learning**](https://doi.org/10.18653/v1/2020.findings-emnlp.41),<br> by *Zhaojiang Lin, Andrea Madotto and Pascale Fung*
<br>``
Proposing an adapter-based method for continual learning in text generation. One of the insights is a frozen PLM can be well-applied in continual learning.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.emnlp-main.394) [**An Empirical Investigation Towards Efficient Multi-Domain Language Model Pre-training**](https://www.aclweb.org/anthology/2020.emnlp-main.394),<br> by *Arumae, Kristjan , Sun, Qing  and Bhatia, Parminder*
<br>``
We find that elastic weight consolidation provides best overall scores yielding only a 0.33% drop in performance across seven generic tasks while remaining competitive in bio-medical tasks.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.emnlp-main.158) [**Visually Grounded Continual Learning of Compositional Phrases**](https://www.aclweb.org/anthology/2020.emnlp-main.158),<br> by *Jin, Xisen , Du, Junyi , Sadhu, Arka , Nevatia, Ram  and Ren, Xiang*
<br>``
A novel continual learning setting and a new benchmark for continual caption generation, evaluated with exiting rehearsal-based methods
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.emnlp-main.52) [**Incremental Event Detection via Knowledge Consolidation Networks**](https://www.aclweb.org/anthology/2020.emnlp-main.52),<br> by *Cao, Pengfei , Chen, Yubo , Zhao, Jun  and Wang, Taifeng*
<br>``
Proposing a hybrid continual learning method for event detection, combining experience replay and Knowledge Distillation, focusing on (1) semantic ambiguity in NLP and (2) data imbalance between memory and current task.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.emnlp-main.565) [**A Multi-Task Incremental Learning Framework with Category Name Embedding for Aspect-Category Sentiment Analysis**](https://www.aclweb.org/anthology/2020.emnlp-main.565),<br> by *Dai, Zehui , Peng, Cheng , Chen, Huajie  and Ding, Yadong*
<br>``
Utilizing BERT for sentence and category encoding, preserving category encoding to prevent catastrophic forgetting.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.emnlp-main.39) [**Efficient Meta Lifelong-Learning with Limited Memory**](https://www.aclweb.org/anthology/2020.emnlp-main.39),<br> by *Wang, Zirui , Mehta, Sanket Vaibhav , Poczos, Barnabas  and Carbonell, Jaime*
<br>``
A meta learning-enhanced version of MbPA (NeurIPS19), sharing the continual setting as well. Figure 1 is interesting.
``
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.emnlp-main.233) [**Lifelong Language Knowledge Distillation**](https://www.aclweb.org/anthology/2020.emnlp-main.233),<br> by *Chuang, Yung-Sung , Su, Shang-Yu  and Chen, Yun-Nung*
<br>``
Proposing a Knowledge Distillation-enhanced Method LLL based on LAMOL (ICLR 2020) model for continual learning, evaluated on text generation and text classification.
``
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://www.aclweb.org/anthology/2020.coling-main.318) [**Distill and Replay for Continual Language Learning**](https://www.aclweb.org/anthology/2020.coling-main.318),<br> by *Sun, Jingyuan , Wang, Shaonan , Zhang, Jiajun  and Zong, Chengqing*
<br>``
Proposing a distill and replay method (DnR) which follows the setting of LAMOL. As a distillation-based method, DnR also shows the ability in incrementally compressing the model size while still outperforming most of the baselines.
``
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/6428) [**ERNIE 2.0: A Continual Pre-Training Framework for Language Understanding**](https://ojs.aaai.org/index.php/AAAI/article/view/6428),<br> by *Sun, Yu, Wang, Shuohuan, Li, Yukun, Feng, Shikun, Tian, Hao, Wu, Hua and Wang, Haifeng*
<br>``
In order to extract the lexical, syntactic and semantic information from training corpora, we propose a continual pre-training framework named ERNIE 2.0 which incrementally builds pre-training tasks and then learn pre-trained models on these constructed tasks via continual multi-task learning.
``
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2019/hash/f8d2e80c1458ea2501f98a2cafadb397-Abstract.html) [**Episodic Memory in Lifelong Language Learning**](https://proceedings.neurips.cc/paper/2019/hash/f8d2e80c1458ea2501f98a2cafadb397-Abstract.html),<br> by *Cyprien de Masson d'Autume, Sebastian Ruder, Lingpeng Kong and Dani Yogatama*
<br>``
MbPA++. This paper proposes the use of memory (a fixed memory network) in life-long learning to prevent catastrophic forgetting by means of  experience replay and local adaptation. 
``
<br><br>
### Prompt Engineering

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.12868) [**On Robustness of Prompt-based Semantic Parsing with Large Pre-trained
Language Model: An Empirical Study on Codex**](https://doi.org/10.48550/arXiv.2301.12868),<br> by *Terry Yue Zhuo, Zhuang Li, Yujin Huang, Yuan-Fang Li, Weiqing Wang, Gholamreza Haffari and Fatemeh Shiri*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.11382) [**A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT**](https://doi.org/10.48550/arXiv.2302.11382),<br> by *Jules White, Quchen Fu, Sam Hays, Michael Sandborn, Carlos Olea, Henry Gilbert, Ashraf Elnashar, Jesse Spencer-Smith et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/CVPR52688.2022.00024) [**Learning to Prompt for Continual Learning**](https://doi.org/10.1109/CVPR52688.2022.00024),<br> by *Zifeng Wang, Zizhao Zhang, Chen-Yu Lee, Han Zhang, Ruoxi Sun, Xiaoqi Ren, Guolong Su, Vincent Perot et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.167) [**Do Prompt-Based Models Really Understand the Meaning of Their Prompts?**](https://doi.org/10.18653/v1/2022.naacl-main.167),<br> by *Albert Webson and Ellie Pavlick*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.01910) [**Large Language Models Are Human-Level Prompt Engineers**](https://doi.org/10.48550/arXiv.2211.01910),<br> by *Yongchao Zhou, Andrei Ioan Muresanu, Ziwen Han, Keiran Paster, Silviu Pitis, Harris Chan and Jimmy Ba*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.60) [**An Information-theoretic Approach to Prompt Engineering Without Ground
Truth Labels**](https://doi.org/10.18653/v1/2022.acl-long.60),<br> by *Taylor Sorensen, Joshua Robinson, Christopher Michael Rytting, Alexander Glenn Shaw, Kyle Jeffrey Rogers, Alexia Pauline Delorey, Mahmoud Khalil, Nancy Fulda et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.04037) [**Demystifying Prompts in Language Models via Perplexity Estimation**](https://doi.org/10.48550/arXiv.2212.04037),<br> by *Hila Gonen, Srini Iyer, Terra Blevins, Noah A. Smith and Luke Zettlemoyer*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.findings-acl.222) [**Cutting Down on Prompts and Parameters: Simple Few-Shot Learning with
Language Models**](https://doi.org/10.18653/v1/2022.findings-acl.222),<br> by *Robert L. Logan IV, Ivana Balazevic, Eric Wallace, Fabio Petroni, Sameer Singh and Sebastian Riedel*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.174) [**Adversarial Soft Prompt Tuning for Cross-Domain Sentiment Analysis**](https://doi.org/10.18653/v1/2022.acl-long.174),<br> by *Hui Wu and Xiaodong Shi*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.471) [**Fine-Grained Controllable Text Generation Using Non-Residual Prompting**](https://doi.org/10.18653/v1/2022.acl-long.471),<br> by *Fredrik Carlsson, Joey \"Ohman, Fangyu Liu, Severine Verlinden, Joakim Nivre and Magnus Sahlgren*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.424) [**MSP: Multi-Stage Prompting for Making Pre-trained Language Models
Better Translators**](https://doi.org/10.18653/v1/2022.acl-long.424),<br> by *Zhixing Tan, Xiangwen Zhang, Shuo Wang and Yang Liu*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.365) [**Noisy Channel Language Model Prompting for Few-Shot Text Classification**](https://doi.org/10.18653/v1/2022.acl-long.365),<br> by *Sewon Min, Mike Lewis, Hannaneh Hajishirzi and Luke Zettlemoyer*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.346) [**SPoT: Better Frozen Model Adaptation through Soft Prompt Transfer**](https://doi.org/10.18653/v1/2022.acl-long.346),<br> by *Tu Vu, Brian Lester, Noah Constant, Rami Al-Rfou' and Daniel Cer*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2203.06904) [**Delta Tuning: A Comprehensive Study of Parameter Efficient Methods
for Pre-trained Language Models**](https://doi.org/10.48550/arXiv.2203.06904),<br> by *Ning Ding, Yujia Qin, Guang Yang, Fuchao Wei, Zonghan Yang, Yusheng Su, Shengding Hu, Yulin Chen et al.*
<br><br>
- [<img src=https://img.shields.io/badge/AutoML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.mlr.press/v188/bansal22a.html) [**Meta-Adapters: Parameter Efficient Few-shot Fine-tuning through Meta-Learning**](https://proceedings.mlr.press/v188/bansal22a.html),<br> by *Trapit Bansal, Salaheddin Alzubi, Tong Wang, Jay-Yoon Lee and Andrew McCallum*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=oOte_397Q4P) [**Sparse Structure Search for Delta Tuning**](https://openreview.net/forum?id=oOte_397Q4P),<br> by *Shengding Hu, Zhen Zhang, Ning Ding, Yadao Wang, Yasheng Wang, Zhiyuan Liu and Maosong Sun*
<br><br>
- [<img src=https://img.shields.io/badge/WWW-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3485447.3511921) [**Ontology-enhanced Prompt-tuning for Few-shot Learning**](https://doi.org/10.1145/3485447.3511921),<br> by *Hongbin Ye, Ningyu Zhang, Shumin Deng, Xiang Chen, Hui Chen, Feiyu Xiong, Xi Chen and Huajun Chen*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.06950) [**Pre-trained Language Models can be Fully Zero-Shot Learners**](https://doi.org/10.48550/arXiv.2212.06950),<br> by *Xuandong Zhao, Siqi Ouyang, Zhiguo Yu, Ming Wu and Lei Li*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2205.10625) [**Least-to-Most Prompting Enables Complex Reasoning in Large Language
Models**](https://doi.org/10.48550/arXiv.2205.10625),<br> by *Denny Zhou, Nathanael Sch\"arli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet et al.*
<br>``
(1) 两阶段的prompt，第一阶段问题分解（通过in-context learning实现，context中包含了其他问题的分解示例），对于每个问题，分解出回答该问题需要先回答什么子问题；
``<br>``
(2) 在第二阶段中，从后往前依次解决子问题，同样通过in-context learing得到，每次LLM的回答会参与组成下一个问题的prompt。
``
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://par.nsf.gov/biblio/10380030) [**The unreliability of explanations in few-shot prompting for textual reasoning**](https://par.nsf.gov/biblio/10380030),<br> by *Ye, Xi and Durrett, Greg*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.02441) [**Ask Me Anything: A simple strategy for prompting language models**](https://doi.org/10.48550/arXiv.2210.02441),<br> by *Simran Arora, Avanika Narayan, Mayee F. Chen, Laurel J. Orr, Neel Guha, Kush Bhatia, Ines Chami, Frederic Sala et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.398) [**Can Prompt Probe Pretrained Language Models? Understanding the Invisible
Risks from a Causal View**](https://doi.org/10.18653/v1/2022.acl-long.398),<br> by *Boxi Cao, Hongyu Lin, Xianpei Han, Fangchao Liu and Le Sun*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.findings-acl.50) [**Reframing Instructional Prompts to GPTk's Language**](https://doi.org/10.18653/v1/2022.findings-acl.50),<br> by *Daniel Khashabi, Chitta Baral, Yejin Choi and Hannaneh Hajishirzi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10539) [**Toward Human Readable Prompt Tuning: Kubrick's The Shining is a good
movie, and a good prompt too?**](https://doi.org/10.48550/arXiv.2212.10539),<br> by *Weijia Shi, Xiaochuang Han, Hila Gonen, Ari Holtzman, Yulia Tsvetkov and Luke Zettlemoyer*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.37) [**Towards Unified Prompt Tuning for Few-shot Text Classification**](https://aclanthology.org/2022.findings-emnlp.37),<br> by *Jianing Wang, Chengyu Wang, Fuli Luo, Chuanqi Tan, Minghui Qiu, Fei Yang, Qiuhui Shi, Songfang Huang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.12587) [**Model ensemble instead of prompt fusion: a sample-specific knowledge
transfer method for few-shot prompt tuning**](https://doi.org/10.48550/arXiv.2210.12587),<br> by *Xiangyu Peng, Chen Xing, Prafulla Kumar Choubey, Chien-Sheng Wu and Caiming Xiong*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.491) [**FewshotQA: A simple framework for few-shot learning of question
answering tasks using pre-trained text-to-text models**](https://doi.org/10.18653/v1/2021.emnlp-main.491),<br> by *Rakesh Chada and Pradeep Natarajan*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.243) [**The Power of Scale for Parameter-Efficient Prompt Tuning**](https://doi.org/10.18653/v1/2021.emnlp-main.243),<br> by *Brian Lester, Rami Al-Rfou and Noah Constant*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.353) [**Prefix-Tuning: Optimizing Continuous Prompts for Generation**](https://doi.org/10.18653/v1/2021.acl-long.353),<br> by *Xiang Lisa Li and Percy Liang*
<br><br>
- [<img src=https://img.shields.io/badge/CHI-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3411763.3451760) [**Prompt Programming for Large Language Models: Beyond the Few-Shot
Paradigm**](https://doi.org/10.1145/3411763.3451760),<br> by *Laria Reynolds and Kyle McDonell*
<br><br>
### Natural Language Understanding

- [<img src=https://img.shields.io/badge/OpenAI-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) [**GPT-4 Technical Report**](https://cdn.openai.com/papers/gpt-4.pdf), [<img src=https://img.shields.io/badge/GPT--4-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) <br> by *OpenAI*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4-system-card.pdf) [**GPT-4 System Card**](https://cdn.openai.com/papers/gpt-4-system-card.pdf), [<img src=https://img.shields.io/badge/GPT--4-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/papers/gpt-4.pdf) <br> by *OpenAI*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.207) [**Knowledge Prompting in Pre-trained Language Model for Natural Language
Understanding**](https://aclanthology.org/2022.emnlp-main.207),<br> by *Jianing Wang, Wenkang Huang, Minghui Qiu, Qiuhui Shi, Hongbin Wang, Xiang Li and Ming Gao*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.468) [**VarMAE: Pre-training of Variational Masked Autoencoder for Domain-adaptive
Language Understanding**](https://aclanthology.org/2022.findings-emnlp.468),<br> by *Dou Hu, Xiaolong Hou, Xiyang Du, Mengyuan Zhou, Lianxin Jiang, Yang Mo and Xiaofeng Shi*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2202.04538) [**Generating Training Data with Language Models: Towards Zero-Shot Language
Understanding**](https://arxiv.org/abs/2202.04538),<br> by *Yu Meng, Jiaxin Huang, Yu Zhang and Jiawei Han*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.acl-long.308) [**VECO: Variable and Flexible Cross-lingual Pre-training for Language
Understanding and Generation**](https://doi.org/10.18653/v1/2021.acl-long.308),<br> by *Fuli Luo, Wei Wang, Jiahao Liu, Yijia Liu, Bin Bi, Songfang Huang, Fei Huang and Luo Si*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2019/hash/c20bb2d9a50d5ac1f713f8b34d9aac5a-Abstract.html) [**Unified Language Model Pre-training for Natural Language Understanding
and Generation**](https://proceedings.neurips.cc/paper/2019/hash/c20bb2d9a50d5ac1f713f8b34d9aac5a-Abstract.html),<br> by *Li Dong, Nan Yang, Wenhui Wang, Furu Wei, Xiaodong Liu, Yu Wang, Jianfeng Gao, Ming Zhou et al.*
<br><br>
- [<img src=https://img.shields.io/badge/OpenAI-2018-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) [**Improving language understanding by generative pre-training**](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf), [<img src=https://img.shields.io/badge/GPT--1-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) <br> by *Radford, Alec, Narasimhan, Karthik, Salimans, Tim, Sutskever, Ilya and others*
<br><br>
### Multimodal

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.05442) [**Scaling Vision Transformers to 22 Billion Parameters**](https://doi.org/10.48550/arXiv.2302.05442),<br> by *Mostafa Dehghani, Josip Djolonga, Basil Mustafa, Piotr Padlewski, Jonathan Heek, Justin Gilmer, Andreas Steiner, Mathilde Caron et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2303.03378) [**PaLM-E: An Embodied Multimodal Language Model**](https://arxiv.org/abs/2303.03378), [<img src=https://img.shields.io/badge/PaLM--E-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2303.03378) <br> by *Driess, Danny, Xia, Fei, Sajjadi, Mehdi SM, Lynch, Corey, Chowdhery, Aakanksha, Ichter, Brian, Wahid, Ayzaan, Tompson, Jonathan et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.07094) [**Learning Customized Visual Models with Retrieval-Augmented Knowledge**](https://doi.org/10.48550/arXiv.2301.07094),<br> by *Haotian Liu, Kilho Son, Jianwei Yang, Ce Liu, Jianfeng Gao, Yong Jae Lee and Chunyuan Li*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2303.04671) [**Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**](https://arxiv.org/abs/2303.04671),<br> by *Wu, Chenfei, Yin, Shengming, Qi, Weizhen, Wang, Xiaodong, Tang, Zecheng and Duan, Nan*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.12192) [**Aligning Text-to-Image Models using Human Feedback**](https://doi.org/10.48550/arXiv.2302.12192),<br> by *Kimin Lee, Hao Liu, Moonkyung Ryu, Olivia Watkins, Yuqing Du, Craig Boutilier, Pieter Abbeel, Mohammad Ghavamzadeh et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/CVPR52688.2022.01593) [**CLIP-Event: Connecting Text and Images with Event Structures**](https://doi.org/10.1109/CVPR52688.2022.01593),<br> by *Manling Li, Ruochen Xu, Shuohang Wang, Luowei Zhou, Xudong Lin, Chenguang Zhu, Michael Zeng, Heng Ji et al.*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.coling-1.491) [**Are Visual-Linguistic Models Commonsense Knowledge Bases?**](https://aclanthology.org/2022.coling-1.491),<br> by *Hsiu-Yu Yang and Carina Silberer*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.12561) [**Retrieval-Augmented Multimodal Language Modeling**](https://doi.org/10.48550/arXiv.2211.12561),<br> by *Michihiro Yasunaga, Armen Aghajanyan, Weijia Shi, Rich James, Jure Leskovec, Percy Liang, Mike Lewis, Luke Zettlemoyer et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.08901) [**Contrastive Language-Image Pre-Training with Knowledge Graphs**](https://doi.org/10.48550/arXiv.2210.08901),<br> by *Xuran Pan, Tianzhu Ye, Dongchen Han, Shiji Song and Gao Huang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2108.04556) [**CLSEBERT: Contrastive Learning for Syntax Enhanced Code Pre-Trained
Model**](https://arxiv.org/abs/2108.04556),<br> by *Xin Wang, Yasheng Wang, Pingyi Zhou, Fei Mi, Meng Xiao, Yadao Wang, Li Li, Xiao Liu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openaccess.thecvf.com/content/CVPR2021/html/Lei_Less_Is_More_ClipBERT_for_Video-and-Language_Learning_via_Sparse_Sampling_CVPR_2021_paper.html) [**Less Is More: ClipBERT for Video-and-Language Learning via Sparse
Sampling**](https://openaccess.thecvf.com/content/CVPR2021/html/Lei_Less_Is_More_ClipBERT_for_Video-and-Language_Learning_via_Sparse_Sampling_CVPR_2021_paper.html),<br> by *Jie Lei, Linjie Li, Luowei Zhou, Zhe Gan, Tamara L. Berg, Mohit Bansal and Jingjing Liu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2102.10772) [**Transformer is All You Need: Multimodal Multitask Learning with a
Unified Transformer**](https://arxiv.org/abs/2102.10772),<br> by *Ronghang Hu and Amanpreet Singh*
<br><br>
- [<img src=https://img.shields.io/badge/MM-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3474085.3475709) [**Pre-training Graph Transformer with Multimodal Side Information for
Recommendation**](https://doi.org/10.1145/3474085.3475709),<br> by *Yong Liu, Susen Yang, Chenyi Lei, Guoxin Wang, Haihong Tang, Juyong Zhang, Aixin Sun and Chunyan Miao*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2002.06353) [**UniViLM: A Unified Video and Language Pre-Training Model for Multimodal
Understanding and Generation**](https://arxiv.org/abs/2002.06353),<br> by *Huaishao Luo, Lei Ji, Botian Shi, Haoyang Huang, Nan Duan, Tianrui Li, Xilin Chen and Ming Zhou*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/49562478de4c54fafd4ec46fdb297de5-Abstract.html) [**Large-Scale Adversarial Training for Vision-and-Language Representation
Learning**](https://proceedings.neurips.cc/paper/2020/hash/49562478de4c54fafd4ec46fdb297de5-Abstract.html),<br> by *Zhe Gan, Yen-Chun Chen, Linjie Li, Chen Zhu, Yu Cheng and Jingjing Liu*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.162) [**Vokenization: Improving Language Understanding with Contextualized,
Visual-Grounded Supervision**](https://doi.org/10.18653/v1/2020.emnlp-main.162),<br> by *Hao Tan and Mohit Bansal*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.214) [**Integrating Multimodal Information in Large Pretrained Transformers**](https://doi.org/10.18653/v1/2020.acl-main.214),<br> by *Wasifur Rahman, Md. Kamrul Hasan, Sangwu Lee, AmirAli Bagher Zadeh, Chengfeng Mao, Louis-Philippe Morency and Mohammed E. Hoque*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=SygXPaEYvH) [**VL-BERT: Pre-training of Generic Visual-Linguistic Representations**](https://openreview.net/forum?id=SygXPaEYvH),<br> by *Weijie Su, Xizhou Zhu, Yue Cao, Bin Li, Lewei Lu, Furu Wei and Jifeng Dai*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](http://arxiv.org/abs/1908.03557) [**VisualBERT: A Simple and Performant Baseline for Vision and Language**](http://arxiv.org/abs/1908.03557),<br> by *Liunian Harold Li, Mark Yatskar, Da Yin, Cho-Jui Hsieh and Kai-Wei Chang*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2019/hash/c74d97b01eae257e44aa9d5bade97baf-Abstract.html) [**ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations
for Vision-and-Language Tasks**](https://proceedings.neurips.cc/paper/2019/hash/c74d97b01eae257e44aa9d5bade97baf-Abstract.html),<br> by *Jiasen Lu, Dhruv Batra, Devi Parikh and Stefan Lee*
<br><br>
- [<img src=https://img.shields.io/badge/ICCV-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/ICCV.2019.00756) [**VideoBERT: A Joint Model for Video and Language Representation Learning**](https://doi.org/10.1109/ICCV.2019.00756),<br> by *Chen Sun, Austin Myers, Carl Vondrick, Kevin Murphy and Cordelia Schmid*
<br><br>
### Multilingual

- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.132) [**GeoMLAMA: Geo-Diverse Commonsense Probing on Multilingual Pre-Trained
Language Models**](https://aclanthology.org/2022.emnlp-main.132),<br> by *Da Yin, Hritik Bansal, Masoud Monajatipoor, Liunian Harold Li and Kai-Wei Chang*
<br><br>
### Reliability

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.12095) [**On the Robustness of ChatGPT: An Adversarial and Out-of-distribution
Perspective**](https://doi.org/10.48550/arXiv.2302.12095),<br> by *Jindong Wang, Xixu Hu, Wenxin Hou, Hao Chen, Runkai Zheng, Yidong Wang, Linyi Yang, Haojun Huang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.09150) [**Prompting GPT-3 To Be Reliable**](https://doi.org/10.48550/arXiv.2210.09150),<br> by *Chenglei Si, Zhe Gan, Zhengyuan Yang, Shuohang Wang, Jianfeng Wang, Jordan L. Boyd-Graber and Lijuan Wang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2207.07411) [**Plex: Towards Reliability using Pretrained Large Model Extensions**](https://doi.org/10.48550/arXiv.2207.07411),<br> by *Dustin Tran, Jeremiah Z. Liu, Michael W. Dusenberry, Du Phan, Mark Collier, Jie Ren, Kehang Han, Zi Wang et al.*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2021/hash/8420d359404024567b5aefda1231af24-Abstract.html) [**Revisiting the Calibration of Modern Neural Networks**](https://proceedings.neurips.cc/paper/2021/hash/8420d359404024567b5aefda1231af24-Abstract.html),<br> by *Matthias Minderer, Josip Djolonga, Rob Romijnders, Frances Hubis, Xiaohua Zhai, Neil Houlsby, Dustin Tran and Mario Lucic*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2021/hash/f8905bd3df64ace64a68e154ba72f24c-Abstract.html) [**Soft Calibration Objectives for Neural Networks**](https://proceedings.neurips.cc/paper/2021/hash/f8905bd3df64ace64a68e154ba72f24c-Abstract.html),<br> by *Archit Karandikar, Nicholas Cain, Dustin Tran, Balaji Lakshminarayanan, Jonathon Shlens, Michael C. Mozer and Becca Roelofs*
<br><br>
### Robustness

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2210.07663) [**Pretrained Transformers Do not Always Improve Robustness**](https://doi.org/10.48550/arXiv.2210.07663),<br> by *Swaroop Mishra, Bhavdeep Singh Sachdeva and Chitta Baral*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.244) [**Pretrained Transformers Improve Out-of-Distribution Robustness**](https://doi.org/10.18653/v1/2020.acl-main.244),<br> by *Dan Hendrycks, Xiaoyuan Liu, Eric Wallace, Adam Dziedzic, Rishabh Krishnan and Dawn Song*
<br><br>
### Dialogue System

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.02851) [**DiSTRICT: Dialogue State Tracking with Retriever Driven In-Context
Tuning**](https://doi.org/10.48550/arXiv.2212.02851),<br> by *Praveen Venkateswaran, Evelyn Duesterwald and Vatche Isahagian*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.coling-1.56) [**Does GPT-3 Generate Empathetic Dialogues? A Novel In-Context Example
Selection Method and Automatic Evaluation Metric for Empathetic Dialogue
Generation**](https://aclanthology.org/2022.coling-1.56),<br> by *Young-Jun Lee, Chae-Gyun Lim and Ho-Jin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/21416) [**Fusing Task-Oriented and Open-Domain Dialogues in Conversational Agents**](https://ojs.aaai.org/index.php/AAAI/article/view/21416),<br> by *Tom Young, Frank Xing, Vlad Pandelea, Jinjie Ni and Erik Cambria*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.11309) [**GODEL: Large-Scale Pre-Training for Goal-Directed Dialog**](https://doi.org/10.48550/arXiv.2206.11309),<br> by *Baolin Peng, Michel Galley, Pengcheng He, Chris Brockett, Lars Liden, Elnaz Nouri, Zhou Yu, Bill Dolan et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09252) [**Mind the Knowledge Gap: A Survey of Knowledge-enhanced Dialogue
Systems**](https://doi.org/10.48550/arXiv.2212.09252),<br> by *Sagi Shaier, Lawrence Hunter and Katharina Kann*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.404) [**Dialogue State Tracking with a Language Model using Schema-Driven
Prompting**](https://doi.org/10.18653/v1/2021.emnlp-main.404),<br> by *Chia-Hsuan Lee, Hao Cheng and Mari Ostendorf*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2110.08118) [**Few-Shot Bot: Prompt-Based Learning for Dialogue Systems**](https://arxiv.org/abs/2110.08118),<br> by *Andrea Madotto, Zhaojiang Lin, Genta Indra Winata and Pascale Fung*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.239) [**Action-Based Conversations Dataset: A Corpus for Building More In-Depth
Task-Oriented Dialogue Systems**](https://doi.org/10.18653/v1/2021.naacl-main.239),<br> by *Derek Chen, Howard Chen, Yi Yang, Alexander Lin and Zhou Yu*
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.naacl-main.122) [**Fine-grained Post-training for Improving Retrieval-based Dialogue
Systems**](https://doi.org/10.18653/v1/2021.naacl-main.122),<br> by *Janghoon Han, Taesuk Hong, Byoungjae Kim, Youngjoong Ko and Jungyun Seo*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2105.04387) [**Recent Advances in Deep Learning Based Dialogue Systems: A Systematic
Survey**](https://arxiv.org/abs/2105.04387),<br> by *Jinjie Ni, Tom Young, Vlad Pandelea, Fuzhao Xue, Vinay Adiga and Erik Cambria*
<br><br>
- [<img src=https://img.shields.io/badge/WWW-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3442381.3449939) [**Slot Self-Attentive Dialogue State Tracking**](https://doi.org/10.1145/3442381.3449939),<br> by *Fanghua Ye, Jarana Manotumruksa, Qiang Zhang, Shenghui Li and Emine Yilmaz*
<br><br>
- [<img src=https://img.shields.io/badge/TACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1162/tacl\_a\_00390) [**Pretraining the Noisy Channel Model for Task-Oriented Dialogue**](https://doi.org/10.1162/tacl\_a\_00390),<br> by *Qi Liu, Lei Yu, Laura Rimell and Phil Blunsom*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/17674) [**UBAR: Towards Fully End-to-End Task-Oriented Dialog System with
GPT-2**](https://ojs.aaai.org/index.php/AAAI/article/view/17674),<br> by *Yunyi Yang, Yunhao Li and Xiaojun Quan*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.acl-main.54) [**End-to-End Neural Pipeline for Goal-Oriented Dialogue Systems using
GPT-2**](https://doi.org/10.18653/v1/2020.acl-main.54),<br> by *DongHoon Ham, Jeong-Gwan Lee, Youngsoo Jang and Kee-Eung Kim*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/e946209592563be0f01c844ab2170f0c-Abstract.html) [**A Simple Language Model for Task-Oriented Dialogue**](https://proceedings.neurips.cc/paper/2020/hash/e946209592563be0f01c844ab2170f0c-Abstract.html),<br> by *Ehsan Hosseini-Asl, Bryan McCann, Chien-Sheng Wu, Semih Yavuz and Richard Socher*
<br><br>
### Recommender System

- [<img src=https://img.shields.io/badge/TKDE-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/TKDE.2020.3028705) [**A Survey on Knowledge Graph-Based Recommender Systems**](https://doi.org/10.1109/TKDE.2020.3028705),<br> by *Qingyu Guo, Fuzhen Zhuang, Chuan Qin, Hengshu Zhu, Xing Xie, Hui Xiong and Qing He*
<br><br>
- [<img src=https://img.shields.io/badge/SIGIR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3477495.3531937) [**Are Graph Augmentations Necessary?: Simple Graph Contrastive Learning
for Recommendation**](https://doi.org/10.1145/3477495.3531937),<br> by *Junliang Yu, Hongzhi Yin, Xin Xia, Tong Chen, Lizhen Cui and Quoc Viet Hung Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/TOIS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://dl.acm.org/doi/abs/10.1145/3572835) [**Disentangled Representations Learning for Multi-Target Cross-Domain Recommendation**](https://dl.acm.org/doi/abs/10.1145/3572835),<br> by *Guo, Xiaobo, Li, Shaoshuai, Guo, Naicheng, Cao, Jiangxia, Liu, Xiaolei, Ma, Qiongxu, Gan, Runsheng and Zhao, Yunan*
<br><br>
- [<img src=https://img.shields.io/badge/SIGIR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3477495.3531714) [**Rethinking Reinforcement Learning for Recommendation: A Prompt Perspective**](https://doi.org/10.1145/3477495.3531714),<br> by *Xin Xin, Tiago Pimentel, Alexandros Karatzoglou, Pengjie Ren, Konstantina Christakopoulou and Zhaochun Ren*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2101.09459) [**Advances and Challenges in Conversational Recommender Systems: A
Survey**](https://arxiv.org/abs/2101.09459),<br> by *Chongming Gao, Wenqiang Lei, Xiangnan He, Maarten de Rijke and Tat-Seng Chua*
<br><br>
- [<img src=https://img.shields.io/badge/MM-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3474085.3475709) [**Pre-training Graph Transformer with Multimodal Side Information for
Recommendation**](https://doi.org/10.1145/3474085.3475709),<br> by *Yong Liu, Susen Yang, Chenyi Lei, Guoxin Wang, Haihong Tang, Juyong Zhang, Aixin Sun and Chunyan Miao*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/5465) [**Towards Hands-Free Visual Dialog Interactive Recommendation**](https://ojs.aaai.org/index.php/AAAI/article/view/5465),<br> by *Tong Yu, Yilin Shen and Hongxia Jin*
<br><br>
### Event Extraction

- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.starsem-1.11) [**Word-Label Alignment for Event Detection: A New Perspective via
Optimal Transport**](https://doi.org/10.18653/v1/2022.starsem-1.11),<br> by *Amir Pouran Ben Veyseh and Thien Huu Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.634) [**Learning Cross-Task Dependencies for Joint Extraction of Entities,
Events, Event Arguments, and Relations**](https://aclanthology.org/2022.emnlp-main.634),<br> by *Minh Van Nguyen, Bonan Min, Franck Dernoncourt and Thien Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/CVPR52688.2022.01593) [**CLIP-Event: Connecting Text and Images with Event Structures**](https://doi.org/10.1109/CVPR52688.2022.01593),<br> by *Manling Li, Ruochen Xu, Shuohang Wang, Luowei Zhou, Xudong Lin, Chenguang Zhu, Michael Zeng, Heng Ji et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ECML-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-030-86523-8\_39) [**Augmenting Open-Domain Event Detection with Synthetic Data from GPT-2**](https://doi.org/10.1007/978-3-030-86523-8\_39),<br> by *Amir Pouran Ben Veyseh, Minh Van Nguyen, Bonan Min and Thien Huu Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.691) [**SeqMix: Augmenting Active Sequence Labeling via Sequence Mixup**](https://doi.org/10.18653/v1/2020.emnlp-main.691),<br> by *Rongzhi Zhang, Yue Yu and Chao Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/p19-1522) [**Exploring Pre-trained Language Models for Event Extraction and Generation**](https://doi.org/10.18653/v1/p19-1522),<br> by *Sen Yang, Dawei Feng, Linbo Qiao, Zhigang Kan and Dongsheng Li*
<br><br>
### Event Relation Extraction

- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.634) [**Learning Cross-Task Dependencies for Joint Extraction of Entities,
Events, Event Arguments, and Relations**](https://aclanthology.org/2022.emnlp-main.634),<br> by *Minh Van Nguyen, Bonan Min, Franck Dernoncourt and Thien Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/21354) [**Selecting Optimal Context Sentences for Event-Event Relation Extraction**](https://ojs.aaai.org/index.php/AAAI/article/view/21354),<br> by *Hieu Man, Nghia Trung Ngo, Linh Ngo Van and Thien Huu Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.407) [**Multilingual SubEvent Relation Extraction: A Novel Dataset and Structure
Induction Method**](https://aclanthology.org/2022.findings-emnlp.407),<br> by *Viet Dac Lai, Hieu Man, Linh Ngo Van, Franck Dernoncourt and Thien Nguyen*
<br><br>
- [<img src=https://img.shields.io/badge/COLING-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.coling-1.200) [**Event Causality Identification via Derivative Prompt Joint Learning**](https://aclanthology.org/2022.coling-1.200),<br> by *Shirong Shen, Heng Zhou, Tongtong Wu and Guilin Qi*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.emnlp-main.107) [**Salience-Aware Event Chain Modeling for Narrative Understanding**](https://doi.org/10.18653/v1/2021.emnlp-main.107),<br> by *Xiyang Zhang, Muhao Chen and Jonathan May*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.51) [**Joint Constrained Learning for Event-Event Relation Extraction**](https://doi.org/10.18653/v1/2020.emnlp-main.51),<br> by *Haoyu Wang, Muhao Chen, Hongming Zhang and Dan Roth*
<br><br>
### Data Argumentation

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.13007) [**ChatAug: Leveraging ChatGPT for Text Data Augmentation**](https://doi.org/10.48550/arXiv.2302.13007),<br> by *Haixing Dai, Zhengliang Liu, Wenxiong Liao, Xiaoke Huang, Zihao Wu, Lin Zhao, Wei Liu, Ninghao Liu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ICLR-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=g11CZSghXyY) [**Combining Ensembles and Data Augmentation Can Harm Your Calibration**](https://openreview.net/forum?id=g11CZSghXyY),<br> by *Yeming Wen, Ghassen Jerfel, Rafael Muller, Michael W. Dusenberry, Jasper Snoek, Balaji Lakshminarayanan and Dustin Tran*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-emnlp.192) [**GPT3Mix: Leveraging Large-scale Language Models for Text Augmentation**](https://doi.org/10.18653/v1/2021.findings-emnlp.192),<br> by *Kang Min Yoo, Dongju Park, Jaewook Kang, Sang-Woo Lee and Woo-Myoung Park*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.691) [**SeqMix: Augmenting Active Sequence Labeling via Sequence Mixup**](https://doi.org/10.18653/v1/2020.emnlp-main.691),<br> by *Rongzhi Zhang, Yue Yu and Chao Zhang*
<br><br>
### Data Annotation

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.10450) [**Is GPT-3 a Good Data Annotator?**](https://doi.org/10.48550/arXiv.2212.10450),<br> by *Bosheng Ding, Chengwei Qin, Linlin Liu, Lidong Bing, Shafiq R. Joty and Boyang Li*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-emnlp.354) [**Want To Reduce Labeling Cost? GPT-3 Can Help**](https://doi.org/10.18653/v1/2021.findings-emnlp.354),<br> by *Shuohang Wang, Yang Liu, Yichong Xu, Chenguang Zhu and Michael Zeng*
<br><br>
### Information Extraction

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.10205) [**Zero-Shot Information Extraction via Chatting with ChatGPT**](https://doi.org/10.48550/arXiv.2302.10205),<br> by *Xiang Wei, Xingyu Cui, Ning Cheng, Xiaobin Wang, Xin Zhang, Shen Huang, Pengjun Xie, Jinan Xu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.130) [**Large language models are few-shot clinical information extractors**](https://aclanthology.org/2022.emnlp-main.130),<br> by *Monica Agrawal, Stefan Hegselmann, Hunter Lang, Yoon Kim and David A. Sontag*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.329) [**Thinking about GPT-3 In-Context Learning for Biomedical IE? Think
Again**](https://aclanthology.org/2022.findings-emnlp.329),<br> by *Bernal Jimenez Gutierrez, Nikolas McNeal, Clayton Washington, You Chen, Lang Li, Huan Sun and Yu Su*
<br><br>
- [<img src=https://img.shields.io/badge/CIKM-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3511808.3557459) [**SPOT: Knowledge-Enhanced Language Representations for Information
Extraction**](https://doi.org/10.1145/3511808.3557459),<br> by *Jiacheng Li, Yannis Katsis, Tyler Baldwin, Ho-Cheol Kim, Andrew Bartko, Julian J. McAuley and Chun-Nan Hsu*
<br><br>
### Domain Adaptive

- [<img src=https://img.shields.io/badge/COLING-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.coling-1.85) [**A Domain Knowledge Enhanced Pre-Trained Language Model for Vertical
Search: Case Study on Medicinal Products**](https://aclanthology.org/2022.coling-1.85),<br> by *Kesong Liu, Jianhui Jiang and Feifei Lyu*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.163) [**Snapshot-Guided Domain Adaptation for ELECTRA**](https://aclanthology.org/2022.findings-emnlp.163),<br> by *Daixuan Cheng, Shaohan Huang, Jianfeng Liu, Yuefeng Zhan, Hao Sun, Furu Wei, Denvy Deng and Qi Zhang*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.468) [**VarMAE: Pre-training of Variational Masked Autoencoder for Domain-adaptive
Language Understanding**](https://aclanthology.org/2022.findings-emnlp.468),<br> by *Dou Hu, Xiaolong Hou, Xiyang Du, Mengyuan Zhou, Lianxin Jiang, Yang Mo and Xiaofeng Shi*
<br><br>
### Question Answering

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.06466) [**ChatGPT versus Traditional Question Answering for Knowledge Graphs:
Current Status and Future Directions Towards Knowledge Graph Chatbots**](https://doi.org/10.48550/arXiv.2302.06466),<br> by *Reham Omar, Omij Mangukiya, Panos Kalnis and Essam Mansour*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2303.07992) [**Evaluation of ChatGPT as a Question Answering System for Answering
Complex Questions**](https://doi.org/10.48550/arXiv.2303.07992),<br> by *Yiming Tan, Dehai Min, Yu Li, Wenbo Li, Nan Hu, Yongrui Chen and Guilin Qi*
<br><br>
- [<img src=https://img.shields.io/badge/KDD-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1145/3534678.3539472) [**Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex
Logical Queries**](https://doi.org/10.1145/3534678.3539472),<br> by *Xiao Liu, Shiyu Zhao, Kai Su, Yukuo Cen, Jiezhong Qiu, Mengdi Zhang, Wei Wu, Yuxiao Dong et al.*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.201) [**Sequence-to-Sequence Knowledge Graph Completion and Question Answering**](https://doi.org/10.18653/v1/2022.acl-long.201),<br> by *Apoorv Saxena, Adrian Kochsiek and Rainer Gemulla*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2207.13332) [**RealTime QA: What's the Answer Right Now?**](https://doi.org/10.48550/arXiv.2207.13332),<br> by *Jungo Kasai, Keisuke Sakaguchi, Yoichi Takahashi, Ronan Le Bras, Akari Asai, Xinyan Yu, Dragomir R. Radev, Noah A. Smith et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.00975) [**Relation-aware Language-Graph Transformer for Question Answering**](https://doi.org/10.48550/arXiv.2212.00975),<br> by *Jinyoung Park, Hyeong Kyu Choi, Juyeon Ko, Hyeon-Jin Park, Ji-Hoon Kim, Jisu Jeong, Kyung-Min Kim and Hyunwoo J. Kim*
<br><br>
### Application

- [<img src=https://img.shields.io/badge/PLOS_Digital_Health-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000198&trk=public_post_comment-text) [**Performance of ChatGPT on USMLE: Potential for AI-assisted medical education using large language models**](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000198&trk=public_post_comment-text),<br> by *Kung, Tiffany H, Cheatham, Morgan, Medenilla, Arielle, Sillos, Czarina, De Leon, Lorie, Elepa\~no, Camille, Madriaga, Maria, Aggabao, Rimel et al.*
<br><br>
- [<img src=https://img.shields.io/badge/PLOS_Digital_Health-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000205) [**ChatGPT passing USMLE shines a spotlight on the flaws of medical education**](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000205),<br> by *Mbakwe, Amarachi B, Lourentzou, Ismini, Celi, Leo Anthony, Mechanic, Oren J and Dagan, Alon*
<br><br>
- [<img src=https://img.shields.io/badge/EvoMUSART-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1007/978-3-031-03789-4\_9) [**Towards the Generation of Musical Explanations with GPT-3**](https://doi.org/10.1007/978-3-031-03789-4\_9),<br> by *Stephen James Krol, Maria Teresa Llano and Jon McCormack*
<br><br>
### Meta Learning

- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.53) [**Meta-learning via Language Model In-context Tuning**](https://doi.org/10.18653/v1/2022.acl-long.53), [<img src=https://img.shields.io/badge/BERT-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/N19-1423/) [<img src=https://img.shields.io/badge/DeBERTa-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2006.03654) [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) <br> by *Yanda Chen, Ruiqi Zhong, Sheng Zha, George Karypis and He He*
<br>``
This paper proposes in-context tuning, which recasts task adaptation and prediction as a simple sequence prediction problem: to form the input sequence,  concatenate the task instruction, labeled in-context examples, and the target input to predict; to meta train the model to learn from in-context examples, finetune a PLM to predict the target label given the input sequence on a collection of tasks (very similar to MetaICL). On LAMA and BinaryClfs, the proposed method outperforms MAML.
``
<br><br>
- [<img src=https://img.shields.io/badge/NAACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.naacl-main.201) [**MetaICL: Learning to Learn In Context**](https://doi.org/10.18653/v1/2022.naacl-main.201), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/facebookresearch/MetaICL) [<img src=https://img.shields.io/badge/GPT--2-yellow alt="img" style="zoom:100%; vertical-align: middle" />](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) <br> by *Sewon Min, Mike Lewis, Luke Zettlemoyer and Hannaneh Hajishirzi*
<br>``
MetaICL proposes a supervised meta-training framework to enable LMs to more effectively learn a new task in context. In MetaICL, each meta-training example includes several training examples from one task that will be presented together as a single sequence to the LM, and the prediction of the final example is used to calculate the loss.
``
<br><br>
### Generalizability

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.03154) [**Conversation Regression Testing: A Design Technique for Prototyping
Generalizable Prompt Strategies for Pre-trained Language Models**](https://doi.org/10.48550/arXiv.2302.03154),<br> by *J. D. Zamfirescu-Pereira, Bjoern Hartmann and Qian Yang*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2206.05658) [**Fine-tuning Pre-trained Language Models with Noise Stability Regularization**](https://doi.org/10.48550/arXiv.2206.05658),<br> by *Hang Hua, Xingjian Li, Dejing Dou, Cheng-Zhong Xu and Jiebo Luo*
<br><br>
- [<img src=https://img.shields.io/badge/ACL_Findings-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.322) [**Do Language Models Perform Generalizable Commonsense Inference?**](https://doi.org/10.18653/v1/2021.findings-acl.322), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://github.com/wangpf3/LM-for-CommonsenseInference)<br> by *Peifeng Wang, Filip Ilievski, Muhao Chen and Xiang Ren*
<br><br>
### Language Model as Knowledge Base

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.11293) [**Understanding Finetuning for Factual Knowledge Extraction from Language
Models**](https://doi.org/10.48550/arXiv.2301.11293),<br> by *Mehran Kazemi, Sid Mittal and Deepak Ramachandran*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP_Findings-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.findings-emnlp.147) [**Can Language Models Serve as Temporal Knowledge Bases?**](https://aclanthology.org/2022.findings-emnlp.147),<br> by *Ruilin Zhao, Feng Zhao, Guandong Xu, Sixiao Zhang and Hai Jin*
<br><br>
- [<img src=https://img.shields.io/badge/ACL-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2022.acl-long.388) [**Finding Structural Knowledge in Multimodal-BERT**](https://doi.org/10.18653/v1/2022.acl-long.388),<br> by *Victor Milewski, Miryam de Lhoneux and Marie-Francine Moens*
<br><br>
- [<img src=https://img.shields.io/badge/EACL-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.eacl-main.153) [**Language Models as Knowledge Bases: On Entity Representations, Storage
Capacity, and Paraphrased Queries**](https://doi.org/10.18653/v1/2021.eacl-main.153),<br> by *Benjamin Heinzerling and Kentaro Inui*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2020.emnlp-main.346) [**AutoPrompt: Eliciting Knowledge from Language Models with Automatically
Generated Prompts**](https://doi.org/10.18653/v1/2020.emnlp-main.346),<br> by *Taylor Shin, Yasaman Razeghi, Robert L. Logan IV, Eric Wallace and Sameer Singh*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/D19-1250) [**Language Models as Knowledge Bases?**](https://doi.org/10.18653/v1/D19-1250),<br> by *Fabio Petroni, Tim Rockt\"aschel, Sebastian Riedel, Patrick S. H. Lewis, Anton Bakhtin, Yuxiang Wu and Alexander H. Miller*
<br><br>
### Retrieval-Augmented Language Model

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.00083) [**In-Context Retrieval-Augmented Language Models**](https://doi.org/10.48550/arXiv.2302.00083),<br> by *Ori Ram, Yoav Levine, Itay Dalmedigos, Dor Muhlgay, Amnon Shashua, Kevin Leyton-Brown and Yoav Shoham*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.07094) [**Learning Customized Visual Models with Retrieval-Augmented Knowledge**](https://doi.org/10.48550/arXiv.2301.07094),<br> by *Haotian Liu, Kilho Son, Jianwei Yang, Ce Liu, Jianfeng Gao, Yong Jae Lee and Chunyuan Li*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.12652) [**REPLUG: Retrieval-Augmented Black-Box Language Models**](https://doi.org/10.48550/arXiv.2301.12652),<br> by *Weijia Shi, Sewon Min, Michihiro Yasunaga, Minjoon Seo, Rich James, Mike Lewis, Luke Zettlemoyer and Wen-tau Yih*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2302.04858) [**Re-ViLM: Retrieval-Augmented Visual Language Model for Zero and Few-Shot
Image Captioning**](https://doi.org/10.48550/arXiv.2302.04858),<br> by *Zhuolin Yang, Wei Ping, Zihan Liu, Vijay Korthikanti, Weili Nie, De-An Huang, Linxi Fan, Zhiding Yu et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2202.01110) [**A Survey on Retrieval-Augmented Text Generation**](https://arxiv.org/abs/2202.01110),<br> by *Huayang Li, Yixuan Su, Deng Cai, Yan Wang and Lemao Liu*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.12561) [**Retrieval-Augmented Multimodal Language Modeling**](https://doi.org/10.48550/arXiv.2211.12561),<br> by *Michihiro Yasunaga, Armen Aghajanyan, Weijia Shi, Rich James, Jure Leskovec, Percy Liang, Mike Lewis, Luke Zettlemoyer et al.*
<br><br>
- [<img src=https://img.shields.io/badge/arXiv_preprint_arXiv-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2208.03299) [**Atlas: Few-shot learning with retrieval augmented language models**](https://arxiv.org/abs/2208.03299),<br> by *Izacard, Gautier, Lewis, Patrick, Lomeli, Maria, Hosseini, Lucas, Petroni, Fabio, Schick, Timo, Dwivedi-Yu, Jane, Joulin, Armand et al.*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.382) [**Training Language Models with Memory Augmentation**](https://aclanthology.org/2022.emnlp-main.382),<br> by *Zexuan Zhong, Tao Lei and Danqi Chen*
<br><br>
- [<img src=https://img.shields.io/badge/ICML-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.mlr.press/v162/borgeaud22a.html) [**Improving Language Models by Retrieving from Trillions of Tokens**](https://proceedings.mlr.press/v162/borgeaud22a.html),<br> by *Sebastian Borgeaud, Arthur Mensch, Jordan Hoffmann, Trevor Cai, Eliza Rutherford, Katie Millican, George van den Driessche, Jean-Baptiste Lespiau et al.*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2002.08909) [**REALM: Retrieval-Augmented Language Model Pre-Training**](https://arxiv.org/abs/2002.08909),<br> by *Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat and Ming-Wei Chang*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://proceedings.neurips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html) [**Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks**](https://proceedings.neurips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html),<br> by *Patrick S. H. Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich K\"uttler, Mike Lewis et al.*
<br><br>
### Quality

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2211.00053) [**Generating Sequences by Learning to Self-Correct**](https://doi.org/10.48550/arXiv.2211.00053),<br> by *Sean Welleck, Ximing Lu, Peter West, Faeze Brahman, Tianxiao Shen, Daniel Khashabi and Yejin Choi*
<br><br>
### Interpretability/Explainability

- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.09095) [**Rethinking the Role of Scale for In-Context Learning: An Interpretability-based
Case Study at 66 Billion Scale**](https://doi.org/10.48550/arXiv.2212.09095),<br> by *Hritik Bansal, Karthik Gopalakrishnan, Saket Dingliwal, Sravan Bodapati, Katrin Kirchhoff and Dan Roth*
<br><br>
- [<img src=https://img.shields.io/badge/EMNLP-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.137) [**Are Hard Examples also Harder to Explain? A Study with Human and
Model-Generated Explanations**](https://aclanthology.org/2022.emnlp-main.137),<br> by *Swarnadeep Saha, Peter Hase, Nazneen Rajani and Mohit Bansal*
<br><br>
- [<img src=https://img.shields.io/badge/Findings_of_the_Association_for_Computational_Linguistics:_{ACL/IJCNLP}
2021,_Online_Event,_August_1--6,_2021-2021-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/2021.findings-acl.366) [**Prompting Contrastive Explanations for Commonsense Reasoning Tasks**](https://doi.org/10.18653/v1/2021.findings-acl.366),<br> by *Bhargavi Paranjape, Julian Michael, Marjan Ghazvininejad, Hannaneh Hajishirzi and Luke Zettlemoyer*
<br><br>
### Data Generation

- [<img src=https://img.shields.io/badge/ICLR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://openreview.net/forum?id=h5OpjGd_lo6) [**Self-Guided Noise-Free Data Generation for Efficient Zero-Shot Learning**](https://openreview.net/forum?id=h5OpjGd_lo6),<br> by *Gao, Jiahui, Pi, Renjie, Yong, LIN, Xu, Hang, Ye, Jiacheng, Wu, Zhiyong, ZHANG, WEIZHONG, Liang, Xiaodan et al.*
<br><br>
- [<img src=https://img.shields.io/badge/the_2022_Conference_on_Empirical_Methods_in_Natural
Language_Processing,_{EMNLP}_2022,_Abu_Dhabi,_United_Arab_Emirates,
December_7--11,_2022-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://aclanthology.org/2022.emnlp-main.801) [**ZeroGen: Efficient Zero-shot Learning via Dataset Generation**](https://aclanthology.org/2022.emnlp-main.801),<br> by *Jiacheng Ye, Jiahui Gao, Qintong Li, Hang Xu, Jiangtao Feng, Zhiyong Wu, Tao Yu and Lingpeng Kong*
<br><br>
- [<img src=https://img.shields.io/badge/CoRR-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://arxiv.org/abs/2202.04538) [**Generating Training Data with Language Models: Towards Zero-Shot Language
Understanding**](https://arxiv.org/abs/2202.04538),<br> by *Yu Meng, Jiaxin Huang, Yu Zhang and Jiawei Han*
<br><br>
### Others

- [<img src=https://img.shields.io/badge/CoRR-2023-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2301.05578) [**Toward General Design Principles for Generative AI Applications**](https://doi.org/10.48550/arXiv.2301.05578),<br> by *Justin D. Weisz, Michael J. Muller, Jessica He and Stephanie Houde*
<br><br>
- [<img src=https://img.shields.io/badge/NeurIPS-2022-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.48550/arXiv.2212.12990) [**Unsupervised Representation Learning from Pre-trained Diffusion Probabilistic
Models**](https://doi.org/10.48550/arXiv.2212.12990),<br> by *Zijian Zhang, Zhou Zhao and Zhijie Lin*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/6446) [**Parsing as Pretraining**](https://ojs.aaai.org/index.php/AAAI/article/view/6446),<br> by *David Vilares, Michalina Strzyz, Anders S\ogaard and Carlos G\'omez-Rodr\'\iguez*
<br><br>
- [<img src=https://img.shields.io/badge/AAAI-2020-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://ojs.aaai.org/index.php/AAAI/article/view/6757) [**Unsupervised Deep Learning via Affinity Diffusion**](https://ojs.aaai.org/index.php/AAAI/article/view/6757),<br> by *Jiabo Huang, Qi Dong, Shaogang Gong and Xiatian Zhu*
<br><br>
- [<img src=https://img.shields.io/badge/-2019-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.18653/v1/p19-1472) [**HellaSwag: Can a Machine Really Finish Your Sentence?**](https://doi.org/10.18653/v1/p19-1472), [<img src=https://img.shields.io/badge/Code-skyblue alt="img" style="zoom:100%; vertical-align: middle" />](https://rowanzellers.com/hellaswag)<br> by *Rowan Zellers, Ari Holtzman, Yonatan Bisk, Ali Farhadi and Yejin Choi*
<br><br>
- [<img src=https://img.shields.io/badge/CVPR-2009-blue alt="img" style="zoom:100%; vertical-align: middle" />](https://doi.org/10.1109/CVPR.2009.5206594) [**Learning to detect unseen object classes by between-class attribute
transfer**](https://doi.org/10.1109/CVPR.2009.5206594),<br> by *Christoph H. Lampert, Hannes Nickisch and Stefan Harmeling*
<br><br>