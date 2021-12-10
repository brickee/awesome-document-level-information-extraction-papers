# awesome-document-level-information-extraction-papers
Papers about document-level information extraction: including named entity recognition, relation extraction, event extraction, opinion mining etc.


## Named Entity Recognition (NER)

1. [ACL 2021] **Explicitly Capturing Relations between Entity Mentions via Graph Neural Networks for Domain-specific Named Entity Recognition** [[paper]](https://aclanthology.org/2021.acl-short.93)[[code]](https://github.com/brickee/EnRel-G)

## Relation Extraction (RE)


## Event Extraction (EE)

### Doc-Level EE

* NAACL2021: **Document-level Event Extraction with Efficient End-to-end Learning of Cross-Event Dependencies**
    * Authors: Kung-Hsiang Huang, Nanyun Peng
    * url: [https://www.aclweb.org/anthology/2021.nuse-1.4/](https://www.aclweb.org/anthology/2021.nuse-1.4/)

* Arxiv: Giveme5W1H: A Universal System for Extracting Main Events from News Articles
    * Authors: Felix Hamborg, Corinna Breitinger, Bela Gipp
    * url: [https://arxiv.org/ftp/arxiv/papers/1909/1909.02766.pdf](https://arxiv.org/ftp/arxiv/papers/1909/1909.02766.pdf)

### MUC4-dataset-based

* AACL2021: **Reconstructing Event Regions for Event Extraction via Graph Attention Networks**
    * Authors: Pei Chen, Hang Yang, Kang Liu, Ruihong Huang, Yubo Chen, Taifeng Wang, Jun Zhao
    * url: [https://aclanthology.org/2020.aacl-main.81/](https://aclanthology.org/2020.aacl-main.81/)

* ACL2020: **Document-Level Event Role Filler Extraction using Multi-Granularity Contextualized Encoding**
    * Authors: Xinya Du, Claire Cardie
    * url: [https://www.aclweb.org/anthology/2020.acl-main.714.pdf](https://www.aclweb.org/anthology/2020.acl-main.714.pdf)
    * code: [https://github.com/xinyadu/doc_event_role](https://github.com/xinyadu/doc_event_role)

* EACL2021: **Document-level Event-based Extraction Using Generative Template-filling Transformers**
    * Authors: Xinya Du, Alexander Rush, Claire Cardie
    * url: [https://arxiv.org/abs/2008.09249](https://arxiv.org/abs/2008.09249)


* NAACL2021: Template Filling with Generative Transformers
    * Authors: Xinya Du, Alexander Rush, Claire Cardie
    * url: [https://aclanthology.org/2021.naacl-main.70/](https://aclanthology.org/2021.naacl-main.70/)

### ChFinAnn-dataset-based

* ACL2018: **DCFFE: A Document-level Chinese Financial Event Extraction System based on Automatically Labelled Training Data**
    * Author: Yang, Hang  and Chen, Yubo  and Liu, Kang  and Xiao, Yang  and Zhao, Jun
    * url: [https://www.aclweb.org/anthology/P18-4009](https://www.aclweb.org/anthology/P18-4009)
    * code: [https://github.com/yanghang111/DCFEE](https://github.com/yanghang111/DCFEE)
    * Keywords: Automatically Labelled, Chinese Financial EE

* EMNLP2019: **Doc2EDAG: An End-to-End Document-level Framework for Chinese Financial Event Extraction**
    * Author: Shun Zheng, Wei Cao, Wei Xu, Jiang Bian
    * url: [https://www.aclweb.org/anthology/D19-1032/](https://www.aclweb.org/anthology/D19-1032/)
    * code: [https://github.com/dolphin-zs/Doc2EDAG/tree/master/dee](https://github.com/dolphin-zs/Doc2EDAG/tree/master/dee)

* ACL2021: **Document-level Event Extraction via Heterogeneous Graph-based Interaction Model with a Tracker**
    * Authors: Runxin Xu, Tianyu Liu, Lei Li and Baobao Chang
    * url: [https://aclanthology.org/2021.acl-long.274/](https://aclanthology.org/2021.acl-long.274/)


* ACL2021: **Document-level Event Extraction via Parallel Prediction Networks**
    * Authors: Hang Yang, Dianbo Sui, Yubo Chen, Kang Liu, Jun Zhao and Taifeng Wang
    * url: [https://aclanthology.org/2021.acl-long.492/](https://aclanthology.org/2021.acl-long.492/)
    * code: [https://github.com/HangYang-NLP/DE-PPN](https://github.com/HangYang-NLP/DE-PPN)

* EMNLP2021: Exploring Sentence Community for Document-Level Event Extraction
    * Authors: Yusheng Huang, Weijia Jia
    * url: [https://aclanthology.org/2021.findings-emnlp.32.pdf](https://aclanthology.org/2021.findings-emnlp.32.pdf)
    * code: [https://nlp.jhu.edu/rams/](https://nlp.jhu.edu/rams/)

### RAMS-dataset-based

* ACL2020: **A Two-Step Approach for Implicit Event Argument Detection**
    * Authors: Zhisong Zhang, Xiang Kong, Zhengzhong Liu, Xuezhe Ma and Eduard Hovy
    * url: [https://www.aclweb.org/anthology/2020.acl-main.667/](https://www.aclweb.org/anthology/2020.acl-main.667/)
    * code: [https://github.com/zzsfornlp/zmsp](https://github.com/zzsfornlp/zmsp)
    
* ACL2020: Multi-Sentence Argument Linking
    * Authors: Seth Ebner, Patrick Xia, Ryan Culkin, Kyle Rawlins, Benjamin Van DurmeA
    * url: [https://www.aclweb.org/anthology/2020.acl-main.718/](https://www.aclweb.org/anthology/2020.acl-main.718/)
    * code: [https://nlp.jhu.edu/rams/](https://nlp.jhu.edu/rams/)

* CIKM2021: Multi-Sentence Argument Linking via An Event-Aware Hierarchical Encoder
    * Authors: Hang Yang, Yubo Chen, Kang Liu, Jun Zhao, Taifeng Wang
    * Links: [https://dl.acm.org/doi/pdf/10.1145/3459637.3482148](https://dl.acm.org/doi/pdf/10.1145/3459637.3482148)

* EMNLP2021: Machine Reading Comprehension as Data Augmentation: A Case Study on Implicit Event Argument Extraction
    * Authors: Jian Liu, Yufeng Chen, Jinan Xu
    * url: [https://aclanthology.org/2021.emnlp-main.214.pdf](https://aclanthology.org/2021.emnlp-main.214.pdf)

* ACL2021: Trigger is Not Sufficient: Exploiting Frame-aware Knowledge for Implicit Event Argument Extraction
    * Authors: Kaiwen Wei, Xian Sun, Zequn Zhang, Jingyuan Zhang, Guo Zhi, Li Jin
    * url: [https://aclanthology.org/2021.acl-long.360/](https://aclanthology.org/2021.acl-long.360/)

### WIKIEVENTS-dataset-based

* NAACL2021: **Document-Level Event Argument Extraction by Conditional Generation**
    * Authors: Sha Li, Heng Ji, Jiawei Han
    * url: [https://www.aclweb.org/anthology/2021.naacl-main.69/](https://www.aclweb.org/anthology/2021.naacl-main.69/)




## Opinion Mining (OM)
