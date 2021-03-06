
# Fraud Detection
Papers and resources about data mining and machine learning for fraud detection in some areas, such as online advertising(e.g. click fraud) and social media(e.g. fake fans).

Contributed by Jinlong Hu, Yi Zhuang, Lang Chen and Tenghui Li.

##### Table of Contents  

1. [Survey](#survey)
2. [Deep learning](#deep-learning)
3. [Graph algorithms](#Graph-algorithms)
4. [Other algorithms](#Other-algorithms)
5. Application-1: [Online advertising](#advertising)
6. Application-2: [Social media](#social-media)  
7. Application-others: [Anomaly-detection](#Anomaly-Detection), [Credit-card-fraud](#Credit-Card-Fraud)
8. [Related resources](#related-resources)

## Survey
1. **Data analysis techniques for fraud detection**
   - [wiki](https://en.wikipedia.org/wiki/Data_analysis_techniques_for_fraud_detection)

1. **A Comprehensive Survey of Data Mining-based Fraud Detection Research**
   - *Clifton Phua, Vincent Lee, Kate Smith, Ross Gayler* 2010.
   - [paper](https://arxiv.org/abs/1009.6119)

1. **Intelligent financial fraud detection: A comprehensive review**
   - *Jarrod West, Maumita Bhattacharya* 2016.
   - [paper](https://www.sciencedirect.com/science/article/pii/S0167404815001261)
   
1. **Fraud detection system: A survey**
   - *Aisha Abdallah, et al.* 2016.
   - [paper](https://www.sciencedirect.com/science/article/pii/S1084804516300571)
   
1. **The application of data mining techniques in financial fraud detection: A classification framework and an academic review of literature**
   - *E.W.T.Nga, et al.* 2011.
   - [paper](https://www.sciencedirect.com/science/article/pii/S0167923610001302)
   
1. **Survey of Clustering based Financial Fraud Detection Research**
   - *Andrei Sorin SABAU* 2012.
   - [paper](https://www.researchgate.net/profile/Andrei_Sabau/publication/267686837_Survey_of_Clustering_based_Financial_Fraud_Detection_Research/links/57597dd308ae9a9c954eff50/Survey-of-Clustering-based-Financial-Fraud-Detection-Research.pdf)
   

## Deep learning
1. **Detecting Fraudulent Behavior Using Recurrent Neural Networks** 
   - *Yoshihiro Ando et al. Computer Security Symposium* 2016. 
   - [Paper](http://lab.iisec.ac.jp/~tanaka_lab/images/pdf/kennkyukai/kennkyukai-2016-10.pdf)

1. **Session-Based Fraud Detection in Online E-Commerce Transactions Using Recurrent Neural Networks** 
   - *Shuhao Wang et al. PKDD* 2017. 
   - [Paper](http://iiis.tsinghua.edu.cn/~weixu/files/SWang_ECMLPKDD_2017.pdf)    [Slides](http://iiis.tsinghua.edu.cn/~weixu/files/SWang_ECMLPKDD_2017_Slides.pdf)

1. **AnoGen: Deep Anomaly Generator** 
   - *Nikolay Laptev* 2018.
   
1. **Generative adversarial network based telecom fraud detection at the receiving bank**
   - *Yu-Jun Zheng, Xiao-Han Zhou, etc.* Neural Networks, 2018.
   
1. **Distributed Deep Forest and its Application to Automatic Detection of Cash-out Fraud**
   - *Ya-Lin Zhang, Jun Zhou, Wenhao Zheng, Ji Feng, Longfei Li, Ziqi Liu, Ming Li, Zhiqiang Zhang, Chaochao Chen, Xiaolong Li, Zhi-Hua Zhou* 2018.
   - [paper](https://arxiv.org/abs/1805.04234)
   - 周志华团队和蚂蚁金服合作：用分布式深度森林算法检测套现欺诈 [中文介绍](https://cloud.tencent.com/developer/article/1161616)
   

## Graph algorithms
#### (1) Survey
1. **Graph-based Anomaly Detection and Description: A Survey**
   - *Leman Akoglu, Hanghang Tong, Danai Koutra* 2014.

1. **Anomaly Detection in Dynamic Networks: A Survey**
   - *Stephen Ranshous, Shitian Shen, Danai Koutra, etc.* 2014.
   
1. **A Survey on Social Media Anomaly Detection**
   - *Rose Yu, Huida Qiu, Zhen Wen, etc.* 2016.

1. **A Survey on Different Graph Based Anomaly Detection Techniques**
   - *Debajit Sensarma, Samar Sen Sarma* 2015.
   
1. **A survey of data mining and social network analysis based anomaly detection techniques**
   - *Ravneet Kaur , Sarbjeet Singh* 2015.
   
1. **Modeling Data With Networks + Network Embedding: Problems, Methodologies and Frontiers**
   - Instructors: Ivan Brugere (University of Illinois at Chicago), Bryan Perozzi (Google), Peng Cui (Tsinghua University), Wenwu Zhu (Tsinghua University), Jian Pei (Simon Fraser University), Tanya Berger-Wolf (University of Illinois at Chicago)
   - *KDD 2018 Tutorial* 
   - [ppt](https://ivanbrugere.github.io/kdd2018/)   
   
1. **A Comprehensive Survey on Graph Neural Networks**
   - *Zonghan Wu* 2019.
   - [paper](https://arxiv.org/pdf/1901.00596.pdf)
   - [中文解读](https://mp.weixin.qq.com/s/0rs8Wur7Iv6jSpFz5C-KNg)
   
1. **Graph Neural Networks: A Review of Methods and Applications**
   - *Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun*  2018
   - [paper](https://arxiv.org/abs/1812.08434)
   - [中文解读](https://www.jiqizhixin.com/articles/2018-12-28-21)
  
   
1. **Deep Learning on Graphs: A Survey**
   - *Ziwei Zhang, Peng Cui, Wenwu Zhu* 2018
   - [paper](https://arxiv.org/abs/1812.04202)
   - [中文解读](https://www.jiqizhixin.com/articles/122304)
   
1. More graph neural networks (GNN) papers, see [GNN-paper-list](https://github.com/largeapp/GNNPapers)

#### (2) Network Embedding
1. **FraudNE: a Joint Embedding Approach for Fraud Detection**
   - *Mengyu Zheng, Chuan Zhou, Jia Wu, etc.* 2018.
   
1. **NetWalk: A Flexible Deep Embedding Approach for Anomaly Detection in Dynamic Networks**
   - *Wenchao Yu, et al.* KDD 2018.
   - [paper](https://www.kdd.org/kdd2018/accepted-papers/view/netwalk-a-flexible-deep-embedding-approach-for-anomaly-detection-in-dynamic)
   - 网络嵌入：随机游走+自编码器；动态：蓄水池；异常检测：密度聚类，假设初始网络正常
   - discussed in lab meeting (L Chen).
   
1. **Inductive Representation Learning on Large Graphs.**
   - *William L. Hamilton, Rex Ying, Jure Leskovec.* NIPS 2017.
   - [paper](https://arxiv.org/pdf/1706.02216.pdf) 
   - [code](https://github.com/williamleif/GraphSAGE)
   - discussed in lab meeting (TH Li).
   
1. **Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning**
   - *Qimai Li, Zhichao Han, and Xiao-Ming Wu* 2018.
   - [paper](https://arxiv.org/pdf/1801.07606)
   - discussed in lab meeting (TH Li).
   
1. **Learning Structural Node Embeddings via Diffusion Wavelets.**
   - *Claire Donnat, Marinka Zitnik, David Hallac, Jure Leskovec.* KDD 2018. 
   - [中文解读](http://www.sohu.com/a/252384389_164987)
   - [paper](https://arxiv.org/pdf/1710.10321.pdf)
   - [code](https://github.com/snap-stanford/graphwave)
   
1. **Embedding Learning with Events in Heterogeneous Information Networks**
   - *Huan Gui ; Jialu Liu ; Fangbo Tao ; Meng Jiang ; Brandon Norick ; Lance Kaplan ; Jiawei Han* 2017.
   - [paper](https://ieeexplore.ieee.org/abstract/document/7997782)
   - [中文解读](https://blog.csdn.net/hy_jz/article/details/79007448)
   - 异质信息网络，超图，超边：事件
 
1. **Graph Embedding Techniques, Applications, and Performance: A Survey**
   - [paper](https://arxiv.org/abs/1705.02801)
   - *GEM: A Python package for graph embedding methods* 
   - [code](https://github.com/palash1992/GEM)
   - 实现了多种静态图嵌入方法
   
 
1. **DynamicGEM: A Library for Dynamic Graph Embedding Methods**
   - *Goyal, P., Chhetri, S. R., Mehrabi, N., Ferrara, E., & Canedo, A.*  2018.
   - [paper](https://arxiv.org/abs/1811.10734)
   - [code](https://github.com/palash1992/DynamicGEM)
   - 实现了多种动态图嵌入方法
   
1. More network embedding papers, see [NE-paper-list](https://github.com/largeapp/NRLPapers)
 
#### (3) Dynamic Algorithms
   
1. **Fraud Detection using Graph Topology and Temporal Spikes**
   - *Shenghua Liu, Bryan Hooi, Christos Faloutsos* 

1. **GOTCHA! Network-based Fraud Detection for Social Security Fraud**
   - *Veronique Van Vlasselaer, etc.* 2014.
   
1. **Realtime Constrained Cycle Detection in Large Dynamic Graphs**
   - *Xiafei Qiu, Wubin Cen, Zhengping Qian, etc.* 2018.
   - Alibaba
 
1. **An Ensemble Approach for Event Detection and Characterization in Dynamic Graphs** 
   - *Shebuti Rayana, Leman Akoglu* 2014.

1. **Detecting node propensity changes in the dynamic degree correctedstochastic block model**
   - *Lisha Yu, William H. Woodall, Kwok-Leung Tsuia* 2018.
   
1. **DGRMiner: Anomaly Detection and Explanation in Dynamic Graphs**
   - *Karel Vaculik and Lubos Popellınsky* 2016.
   
 
   
1. **Localizing Temporal Anomalies in Large Evolving Graphs**
   - *Teng Wang, etc.*   
   
1. **Triaging Anomalies in Dynamic Graphs: Towards Reducing False Positives**
   - *Teng Wang, et al.* 2015.
1. **Fraud Detection in Dynamic Interaction Network** 
   - *Hao Lin, et al.* 2019.
   
#### (4) Others Graph Algorithms
1. **Behavior Language Processing with Graph based Feature Generation for Fraud Detection in Online Lending**
   - *Wei Min, etc.* 2018.
   
1. **FairPlay: Fraud and Malware Detection in Google Play**
   - *Mahmudur Rahman, etc.*
   
1. **FRAUDAR: Bounding Graph Fraud in the Face of Camouflage**
   - *Bryan Hooi, Hyun Ah Song, Alex Beutel, Neil Shah, Kijung Shin, Christos Faloutsos* 2016.
  
1. **Heterogeneous anomaly detection in social diffusion with discriminative feature discovery**
   - *Siyuan Liu, etc.* Information Sciences 2018.

1. **REV2: Fraudulent User Prediction in Rating Platforms**
   - *Srijan Kumar, etc.* 2018.
   
1. **Stateless Puzzles for Real Time Online Fraud Preemption**
   - *Mizanur Rahman, etc.* 2017.

1. **iBGP: A Bipartite Graph Propagation Approach for Mobile Advertising Fraud Detection** 
   - *Jinlong Hu, Junjie Liang, and Shoubin Dong. Mobile Information Systems* 2017. 
   - [Paper](https://www.hindawi.com/journals/misy/2017/6412521/) 

## Other algorithms
1. **Online E-Commerce Fraud: A Large-scale Detection and Analysis** 
   - *Haiqin Weng, Zhao Li, Shouling Ji, etc.*
   - [paper](https://nesa.zju.edu.cn/download/Online%20E-Commerce%20Fraud%20A%20Large-scale%20Detection%20and%20Analysis.pdf)
   -  Alibaba

1. **Next Generation Trustworthy Fraud Detection** 
   - *Sihong Xie, Philip S. Yuy* 2018.

1. **Incorporating Privileged Information to Unsupervised Anomaly Detection** 
   - *Shubhranshu Shekhar, Leman Akoglu* 2018.

1. **Feedback-Guided Anomaly Discovery via Online Optimization** 
   - *Md Amran Siddiqui，Alan Fern，Thomas G. Dietterich, etc.* 2018.
   - "active learning"

1. **Unorganized Malicious Attacks Detection**  
   - *Ming Pang, Wei Gao, Min Tao, Zhi-Hua Zhou* 2018.
   - [Paper](https://arxiv.org/pdf/1610.04086.pdf)
   - "shilling attacks"

1. **Fraud detection with machine learning** project with some new papers
   - [link](https://www.researchgate.net/project/Fraud-detection-with-machine-learning)


## Advertising

#### Bluff Ads
1. [Fighting Online Click-Fraud Using Bluff Ads](https://arxiv.org/pdf/1002.2353.pdf) by Hamed Haddadi. ACM Computer Communication Review 2010.
1. [Measuring and Fingerprinting Click-Spam in Ad Networks](http://www.cs.utexas.edu/users/yzhang/papers/clickspam-sigc12.pdf) by Vacha Dave et al. ACM SIGCOMM Conference on Data Communication 2012.

#### Mobile Apps
1. [DECAF: Detecting and Characterizing Ad Fraud in Mobile Apps](/papers/10.1.1.704.3668.pdf) by Bin Liu et al. Proc. 11th USENIX Conf. Netw. Syst. Des. Implementation 2014.
1. [MAdFraud: Investigating Ad Fraud in Android Applications](https://pdfs.semanticscholar.org/f4b7/7a7f3c868b48a44c3480843aff22dc67df70.pdf) by Jonathan Crussell et al. Proc. 12th International Conference on Mobile Systems Applications and Services (MobiSys'14) 2014.

#### Duplicate Detection
* [Detecting Click Fraud in Pay-Per-Click Streams of Online Advertising Networks](https://www.researchgate.net/profile/Linfeng_Zhang4/publication/4365107_Detecting_Click_Fraud_in_Pay-Per-Click_Streams_of_Online_Advertising_Networks/links/56f12ac908ae9a58a829435f.pdf) by Linfeng Zhang et al. ICDCS 2008.

#### Association Rule
* [Using Association Rules for Fraud Detection in Web Advertising Networks](https://p2p.cs.ucsb.edu/research/tech_reports/reports/2005-13.pdf) by Ahmed Metwally et al. VLDB 2005.

#### FDMA 2012 Competition
1. [Detecting Click Fraud in Online Advertising: A Data Mining Approach](http://www.jmlr.org/papers/volume15/oentaryo14a/oentaryo14a.pdf) by Richard Oentaryo et al. JMLR 2014.
1. [Feature Engineering for Click Fraud Detection](http://research.larc.smu.edu.sg/fdma2012/doc/FirstWinner-Starrystarrynight-Paper.pdf) by Clifton Phua et al. International Workshop on Fraud Detection in Mobile Advertising (FDMA) 2012.
1. [A Novel Approach Based on Ensemble Learning for Fraud Detection in Mobile Advertising](http://research.larc.smu.edu.sg/fdma2012/doc/SecondWinner-TeamMasdar-Paper.pdf) by Kasun S. Perera et al. International Workshop on Fraud Detection in Mobile Advertising (FDMA) 2012.
1. [Hybrid Models for Click Fraud Detection in Mobile Advertising](http://research.larc.smu.edu.sg/fdma2012/doc/ThirdWinner-DB2-Paper.pdf) by Chen Wei et al. International Workshop on Fraud Detection in Mobile Advertising (FDMA) 2012.
1. [Random Forests for the Detection of Click Fraud in Online Mobile Advertising](http://research.larc.smu.edu.sg/fdma2012/doc/FirstRunnerUp-Tea-Paper.pdf) by Daniel Berrar et al. International Workshop on Fraud Detection in Mobile Advertising (FDMA) 2012.
1. [Hierarchical Committee Machines for Fraud Detection in Mobile Advertising](http://research.larc.smu.edu.sg/fdma2012/doc/SecondRunnerUp-Kites-Paper.pdf) by S. Shivashankar et al. International Workshop on Fraud Detection in Mobile Advertising (FDMA) 2012.

#### Dateset
* [FDMA 2012 Competition Dataset](https://docs.google.com/file/d/0B77LA4oEl-AQTGRHSVNMczJhVTg) by BuzzCity Pte. Ltd. FDMA 2012.

#### Report and White Paper
1. [The Lane’s Gifts v. Google Report](/papers/Alexandr_Tuzhilin_Report.pdf) by Alexander Tuzhilin. 2006. 
1. [Click Fraud Detection: Adversarial Pattern Recognition over 5 Years at Microsoft](http://www.appliedaisystems.com/papers/ClickQualitySystems54_LNCSFormat_clean.pdf) by Brendan Kitts et al. Real World Data Mining Applications 2015.
1. [2017广告反欺诈白皮书](https://3gimg.qq.com/mig_op/beacon/download/baipishu.pdf) by 腾讯灯塔, 秒针, AdMaster. 2017.
1. [The State of Mobile Fraud Q1 2018](https://hub.appsflyer.com/hubfs/State%20of%20Mobile%20Fraud%20Q1%202018%20AppsFlyer.pdf) by Appsflyer. 2018.

## Social Media
#### Fake fans and zombie fans

1. **Íntegro: Leveraging victim prediction for robust fake account detection in large scale OSNs**
   - *Boshmaf, Yazan, et al.* Computers & Security 2016.

1.  **Using Bi-level Penalized Logistic Classifier to Detect Zombie Accounts in Online Social Networks**
    - *Jing Deng, et al.*  2016.

1. **Micro-blog spammer detection based on characteristics of social behaviors**
   - *Jianbo Wang, et al.*  2017.

1. **Discrimination of zombie fans on weibo based on features extraction and business-driven analysis**
   - *Hongxun Jiang, et al.* 2015.

1. 一种降低微博僵尸粉影响的方法
   - 现代图书情报技术，2012.

1. **FRAUDAR: Bounding Graph Fraud in the Face of Camouflage**
   - *Bryan Hooi et al.* KDD 2016.
   - [paper](https://www.andrew.cmu.edu/user/bhooi/projects/fraudar/index.html) 

1. **Distance-based customer detection in fake follower markets** 
   - *Jang, Boyeon, Sihyun Jeong, and Chong-kwon Kim*  2018.
   - [paper](https://www.sciencedirect.com/science/article/abs/pii/S030643791830214X?via%3Dihub)
   - [data](https://data.mendeley.com/datasets/xvm2yxsxx4/1)
   
#### Social media rumors
   
1. **中文社交媒体谣言统计语义分析**
   - *刘知远，et al.* 2015.
   - *CED: Credible Early Detection of Social Media Rumors*, 2018. [new paper](https://arxiv.org/abs/1811.04175)
   - [数据](https://github.com/largeapp/Chinese_Rumor_Dataset)

## Other Applications

### Anomaly Detection

- **Survey**
1. [Anomaly Detection: A Survey](https://www.cs.umn.edu/sites/cs.umn.edu/files/tech_reports/07-017.pdf) by Varun Chandola et al. ACM Computing Surveys, Vol. 41, No. 3, 15, 01.07.2009.

- **Open Source Toolkit**
1. [Scikit-learn Novelty and Outlier Detection](http://scikit-learn.org/stable/modules/outlier_detection.html)
1. [Python Outlier Detection (PyOD)](http://pyod.readthedocs.io)
1. [ELKI: Environment for Developing KDD-Applications Supported by Index-Structures](https://elki-project.github.io)

### Credit Card Fraud
1. **Credit Card Fraud Detection in e-Commerce: An Outlier Detection Approach**
   - *Utkarsh Porwal, Smruthi Mukund* eBay, 2018.
   - [paper](https://arxiv.org/abs/1811.02196)
   - [中文介绍](https://cloud.tencent.com/developer/article/1369815)
   - Data: UCI and [kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

1. [Learned lessons in credit card fraud detection from a practitioner perspective](http://www.ulb.ac.be/di/map/adalpozz/pdf/FraudDetectionPaper_8.pdf) by A Dal Pozzolo et al. Expert Systems with Applications, 41(10):4915–4928, 2014.
1. [APATE: A Novel Approach for Automated Credit Card Transaction Fraud Detection using Network-Based Extensions](https://lirias.kuleuven.be/bitstream/123456789/496406/1/APATE.pdf) by Veronique Van Vlasselaer et al. Decision Support Systems, 2015.


## Related Resources

### Report and White Paper
<!-- * [2017电子商务生态安全白皮书](http://hchdownload.oss-cn-hangzhou.aliyuncs.com/%E4%BC%9A%E8%AE%AE%E6%96%87%E6%A1%A3/2017%E7%94%B5%E5%AD%90%E5%95%86%E5%8A%A1%E7%94%9F%E6%80%81%E5%AE%89%E5%85%A8%E7%99%BD%E7%9A%AE%E4%B9%A6.pdf) by 电子商务生态安全联盟. 2017.-->

* [Facebook Immune System](https://css.csail.mit.edu/6.858/2012/readings/facebook-immune.pdf) by Tao Stein et al. Proceedings of the 4th Workshop on Social Network Systems, SNS, 2011.

<!-- ### 经验汇总
 * [收集汇总不同行业不同公司，网络上公开的风控或安全的架构、方案、算法](https://github.com/csearch/risky-company-project)
 * [收录风控领域相关算法Paper](https://github.com/csearch/risky-algorithm-research)-->

### Reference links
* Paper list of network embedding [link](https://github.com/largeapp/NRLPapers)
* Paper list of knowledge representation learning [link](https://github.com/thunlp/KRLPapers)
* [Fraud Detection papers](https://github.com/IPL/fraud-detection-papers) by Xinyu Wang


