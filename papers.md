# Papers

+ [Surveys & Tutorials](#Surveys--Tutorials)
+ [Anomaly Detection](#anomaly-detection)
+ [Failure Prediction](#Failure-Prediction)
+ [Diagnosis/ Debugging/ Root Cause Analysis](#diagnosis-debugging-root-cause-analysis)
+ [Performance Issues](#performance-issues)
+ [Energy Issues](#Energy-Issues)
+ [Security Issues](#Security-Issues)
+ [Issue Categorization](#issue-categorization)
+ [Duplicate Issues Identification](#duplicate-issues-identification)
+ [Software Testing](#software-testing)
+ [Bug Finding](#Bug-Finding)
+ [Workflow Mining](#Workflow-Mining)
+ [Logging Practices](#logging-practices)
+ [Tracing Practices](#tracing-practices)
+ [Log Parsing](#log-parsing)
+ [Log Compression](#log-compression)
+ [Empirical Studies](#empirical-studies)
+ [Industrial Talks](#Industrial-Talks)

### Surveys & Tutorials & Magazines
1. [**Blog**] [What is AIOps? Artificial Intelligence for IT Operations Explained](http://www.bmc.com/blogs/what-is-aiops/), by Seth Paskin. [**BMC Software**]
1. [**Book'14**] [I Heart Logs](https://www.oreilly.com/library/view/i-heart-logs/9781491909379/), by Jay Kreps.
1. [**Book'12**] [Logging and Log Management: The Authoritative Guide to Understanding the Concepts Surrounding Logging and Log Management](http://mirror.thelifeofkenneth.com/sites/qt.vidyagam.es/library/Forensics/Logging%20and%20Log%20Management_%20The%20Authoritats%20Surrounding%20Logging%20and%20Log%20Management/Logging%20and%20Log%20Management_%20The%20Authoritative%20Guide%20to%20Undeanagement%20-%20Anton%20Chuvakin%20&%20Kevin%20Schmidt%20&%20Chris%20Phillips.pdf), by Anton A. Chuvakin, Kevin J. Schmidt, Christopher Phillips.
1. [**Thesis**] [Log Engineering: Towards Systematic Log Mining to Support the Development of Ultra-large Scale Systems](https://users.encs.concordia.ca/~shang/pubs/2014_LogEngineering_TowardsSystematicLogMiningToSupportTheDevelopmentOfUltra-largeScaleSystems.pdf), by Weiyi Shang.
1. [**IST'20**] [A Systematic Literature Review on Automated Log Abstraction Techniques](https://www.sciencedirect.com/science/article/pii/S0950584920300264), by Diana El-Masri, Fabio Petrillo, Yann-Gael Guéhéneuc, Abdelwahab Hamou-Lhadj, Anas Bouzianea.
1. [**IEEE Software'16**] [Operational-Log Analysis for Big Data Systems: Challenges and Solutions](https://www.computer.org/csdl/magazine/so/2016/02/mso2016020052/13rRUzp02mr), by Andriy V. Miranskyy, Abdelwahab Hamou-Lhadj, Enzo Cialini, Alf Larsson [**IBM, Ericsson**].


### Anomaly Detection
1. [**ICDM'20**] [Self-Attentive Classification-Based Anomaly Detection in Unstructured Logs](https://arxiv.org/pdf/2008.09340.pdf), by Sasho Nedelkoski, Jasmin Bogatinovski, Alexander Acker, Jorge Cardoso, Odej Kao.
1. [**IJCAI'19**] [LogAnomaly: Unsupervised Detection of Sequential and Quantitative Anomalies in Unstructured Logs](https://www.ijcai.org/proceedings/2019/0658.pdf), by Weibin Meng, Ying Liu, Yichen Zhu, Shenglin Zhang, Dan Pei, Yuqing Liu, Yihao Chen, Ruizhi Zhang, Shimin Tao, Pei Sun, Rong Zhou. [**Huawei**]
1. [**FSE'19**] [Robust Log-based Anomaly Detection on Unstable Log Data](https://dl.acm.org/citation.cfm?id=3338931), by Xu Zhang, Yong Xu, Qingwei Lin, Bo Qiao, Hongyu Zhang, Yingnong Dang, Chunyu Xie, Xinsheng Yang, Qian Cheng, Ze Li, Junjie Chen, Xiaoting He, Randolph Yao, Jian-Guang Lou, Murali Chintalapati, Furao Shen, and Dongmei Zhang. [**Microsoft**]
1. [**ICSE'19**] [Energy-Based Anomaly Detection A New Perspective for Predicting Software Failures](https://dl.acm.org/citation.cfm?id=3339163), by Cristina Monni, Mauro Pezzè.
1. [**DSN'19**] [Robust Anomaly Detection on Unreliable Data](https://hal.archives-ouvertes.fr/hal-02056558), by Zilong Zhao, Sophie Cerf, Robert Birke, Bogdan Robu, Sara Bouchenak, Sonia Ben Mokhtar, Lydia Y. Chen. [**ABB Research**]
1. [**BigData'18**] [Evaluation of Distributed Machine Learning Algorithms for Anomaly Detection from Large-Scale System Logs: A Case Study](https://ieeexplore.ieee.org/document/8621967), by Merve Astekin, Harun Zengin, Hasan Sözer.
1. [**OSDI'18**] [Capturing and Enhancing In Situ System Observability for Failure Detection](https://www.usenix.org/conference/osdi18/presentation/huang), by Peng Huang, Chuanxiong Guo, Jacob R. Lorch, Lidong Zhou, Yingnong Dang. [**ByteDance, Microsoft**]
1. [**IEEE Access'18**] [An Integrated Method for Anomaly Detection From Massive System Logs](https://ieeexplore.ieee.org/document/8371223), by Zhaoli Liu, Tao Qin, Xiaohong Guan, Hezhi Jiang, Chenxu Wang.
1. [**NOMS'18**] [An Unsupervised Framework for Detecting Anomalous Messages from Syslog Log Files](https://ccdcoe.org/uploads/2018/11/Tech-Reserach-Paper-on-Log-Anomaly_oct-2018_Bernhards-Blumbergs-Kont.pdf), by Risto Vaarandi, Bernhards Blumbergs, Markus Kont.
1. [**CCS'17**] [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://www.cs.utah.edu/~lifeifei/papers/deeplog.pdf), by Min Du, Feifei Li, Guineng Zheng, Vivek Srikumar.
1. [**ISSRE'17**] [Experience Report: Log Mining using Natural Language Processing and Application to Anomaly Detection](https://hal.laas.fr/hal-01576291/document), by Christophe Bertero, Matthieu Roy, Carla Sauvanaud and Gilles Tredan.
1. [**ISSRE'16**] [Experience Report: System Log Analysis for Anomaly Detection](https://jiemingzhu.github.io/pub/slhe_issre2016.pdf), by Shilin He, Jieming Zhu, Pinjia He, Michael R. Lyu. 
1. [**ICDM'09**] [Execution Anomaly Detection in Distributed Systems through Unstructured Log Analysis](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/DM790-CR.pdf), by Qiang Fu, Jian-Guang Lou, Yi Wang, Jiang Li. [**Microsoft**]

### Failure Prediction

### Diagnosis/ Debugging/ Root Cause Analysis
1. [**CLOUD'19**] [An Approach to Cloud Execution Failure Diagnosis Based on Exception Logs in OpenStack](https://ieeexplore.ieee.org/abstract/document/8814553), by Yue Yuan, Wenchang Shi, Bin Liang, Bo Qin.
1. [**SOSP'19**] [The Prefix Inflection Theorem: A Principled Debugging Approach for Locating Root Cause], by Yongle Zhang, Kirk Rodrigues, Yu Luo, Michael Stumm, Ding Yuan.
1. [**FSE'19**] [Latent Error Prediction and Fault Localization for Microservice Applications by Learning from System Trace Logs](http://taoxie.cs.illinois.edu/publications/esecfse19-microservice.pdf), by Xiang Zhou, Xin Peng, Tao Xie, Jun Sun, Chao Ji, Dewei Liu, Qilin Xiang, and Chuan He.
1. [**ICSE'19**] [An Empirical Study On Leveraging Logs For Debugging Production Failures](https://dl.acm.org/citation.cfm?id=3339663.3339723), by An Ran Chen.
1. [**OSDI'18**] [REPT: Reverse Debugging of Failures in Deployed Software](https://www.usenix.org/conference/osdi18/presentation/weidong), by Weidong Cui, Xinyang Ge, Baris Kasikci, Ben Niu, Upamanyu Sharma, Ruoyu Wang, Insu Yun. [**Microsoft**]
1. [**Ebook'17**] [The Complete Guide to Automated Root Cause Analysis](https://land.overops.com/automated-root-cause-analysis-ebook/), by Tali Soroker. [**OverOps**]
1. [**ICSE'13**] [Assisting Developers of Big Data Analytics Applications When Deploying on Hadoop Clouds](http://www.cse.yorku.ca/~zmjiang/publications/ICSE2013_Shang.pdf), by Weiyi Shang, Zhen Ming Jiang, Hadi Hemmati, Bram Adams, Ahmed E. Hassan and Patrick Marin. [**ACM SIGSOFT Distinguished Paper Award**] 
1. [**ICSM**] [Mining Telecom System Logs to Facilitate Debugging Tasks](https://ieeexplore.ieee.org/document/6676951), by Alf Larsson, Abdelwahab Hamou-Lhadj. [**Ericsson**]
1. [**ASPLOS'10**] [SherLog: Error Diagnosis by Connecting Clues from Run-time Logs ](http://opera.ucsd.edu/paper/asplos10-sherlog.pdf), by Ding Yuan, Haohui Mai, Weiwei Xiong, Lin Tan, Yuanyuan Zhou and Shankar Pasupathy. 

### Failure Reproduction
1. [**SOSP'17**] [Pensieve: Non-Intrusive Failure Reproduction for Distributed Systems using the Event Chaining Approach](http://www.eecg.toronto.edu/~yuan/papers/pensieve-sosp17.pdf), by Yongle Zhang, Serguei Makarov, Xiang Ren, David Lion, Ding Yuan.

### Performance Issues
1. [**SOSP'17**] [Non-intrusive Performance Profiling of Entire Software Stacks based on the Flow Reconstruction Principle ](http://www.eecg.toronto.edu/~yuan/papers/zhao_stitch.pdf), by Xu Zhao, Kirk Rodrigues, Yu Luo, Ding Yuan, and Michael Stumm.
1. [**SOSP'17**] [lprof: A Non-intrusive Request Flow Profiler for Distributed Systems](http://www.eecg.toronto.edu/~yuan/papers/lprof_osdi14.pdf), by Xu Zhao, Yongle Zhang, David Lion, Muhammad FaizanUllah, Yu Luo, Ding Yuan, and Michael Stumm.

### Energy Issues
### Security Issues


### Issue Categorization
1. [**FSE'18**] [Identifying Impactful Service System Problems via Log Analysis](https://github.com/logpai/Log3C), by Shilin He, Qingwei Lin, Jian-Guang Lou, Hongyu Zhang, Michael R. Lyu, Dongmei Zhang. [**Microsoft**]
1. [**IWQoS'18**] [Device-Agnostic Log Anomaly Classification with Partial Labels](https://aiops.org/wp-content/uploads/2018/06/Device_Agnostic_Log_Anomaly_Classification.pdf), by Weibin Meng, Ying Liu, Shenglin Zhang, Dan Pei, Hui Dong, Lei Song, Xulong Luo. [**Baidu**]
1. [**BigData'17**] [WEAC: Word Embeddings for Anomaly Classification from Event Logs](https://ieeexplore.ieee.org/document/8258034), by Amit Pande, Vishal Ahuja. [**Target Corporation**]

### Duplicate Issues Identification
1. [**TSE'18**] [Revisiting the Performance Evaluation of Automated Approaches for the Retrieval of Duplicate Issue Reports](https://sail.cs.queensu.ca/Downloads/TSE2017_RevisitingThePerformanceEvaluationOfAutomatedApproachesForTheRetrievalOfDuplicateIssueReports.pdf), by 	Mohamed Sami Rakha, Cor-Paul Bezemer, Ahmed E. Hassan.
1. [**DSN'14**] [Mining Historical Issue Repositories to Heal Large-Scale Online Service Systems](https://ieeexplore.ieee.org/abstract/document/6903589), by Rui Ding, Qiang Fu, Jian-Guang Lou, Qingwei Lin, Dongmei Zhang, Tao Xie. [**Microsoft**] 
1. [**ICDM'14**] [Identifying Recurrent and Unknown Performance Issues](https://ieeexplore.ieee.org/document/7023349), by Meng-Hui Lim, Jian-Guang Lou, Hongyu Zhang, Qiang Fu, Andrew Beng Jin Teoh, Qingwei Lin, Rui Ding, Dongmei Zhang. [**Microsoft**]


### Software Testing
1. [**ICSE'19**] [Mining Historical Test Logs to Predict Bugs and Localize Faults in the Test Logs](https://dl.acm.org/citation.cfm?id=3339525), by Anunay Amar, Peter Rigby.
1. [**ASE'18**] [An Automated Approach to Estimating Code Coverage Measures via Execution Logs](http://www.cse.yorku.ca/~zmjiang/publications/ase2018_chen.pdf), by Boyuan Chen, Jian Song, Peng Xu, Xing Hu, Zhen Ming (Jack) Jiang.

### Bug Finding
1. [**OSDI'18**] [Finding Crash-Consistency Bugs with Bounded Black-Box Crash Testing](https://www.usenix.org/conference/osdi18/presentation/mohan), by Jayashree Mohan, Ashlie Martinez, Soujanya Ponnapalli, Pandian Raju, Vijay Chidambaram. [**VMware**]
1. [**FSE'18**] [CloudRaid: Hunting Concurrency Bugs in the Cloud via Log-Mining](), by Jie Lu, Feng Li, Lian Li, Xiaobing Feng.

### Workflow Mining
1. [**ASE'19**] [Statistical Log Differencing](http://www.mysmu.edu/faculty/davidlo/papers/ase19-sld.pdf), by Lingfeng Bao, Nimrod Busany, David Lo, Shahar Maoz.
1. [**ICSE'18**] [Inferring Hierarchical Motifs from Execution Traces](http://blogs.ubc.ca/karthik/files/2018/02/Saba-ICSE18.pdf), by Saba Alimadadi, Ali Mesbah, Karthik Pattabiraman.
1. [**FSE'18**] [Using Finite-State Models for Log Differencing](https://www.cs.tau.ac.il/~maozs/papers/log-diff-fse18.pdf), by Hen Amar, Lingfeng Bao, Nimrod Busany, David Lo, Shahar Maoz.

### Logging Practices
1. [**SANER'20**] [MobiLogLeak: A Preliminary Study on Data Leakage Caused by Poor Logging Practices](https://users.encs.concordia.ca/~abdelw/papers/saner20_mobilogloeak_preprint.pdf), by Rui Zhou, Mohammad Hamdaqa, Haipeng Cai, and Abdelwahab Hamou-Lhadj.
1. [**TSE'19**] [Which Variables Should I Log?](https://xin-xia.github.io/publication/tse197.pdf), by Zhongxin Liu, Xin Xia, David Lo, Zhenchang Xing, Ahmed E. Hassan, Shanping Li.
1. [**ICSE'19**] [DLFinder: Characterizing and Detecting Duplicate Logging Code Smells](https://users.encs.concordia.ca/~shang/pubs/icse2019_zhenhao.pdf), by Zhenhao Li, Tse-Hsun Chen, Jinqiu Yang and Weiyi Shang.
1. [**MSR'19**] [Tracing Back Log Data to its Log Statement: From Research to Practice](https://pure.tudelft.nl/portal/files/52060635/paper.pdf), by Daan Schipper, Mauricio Aniche, Arie van Deursen.
1. [**ASE'18**] [Characterizing the Natural Language Descriptions in Software. Logging Statements](https://pinjiahe.github.io/papers/ASE18.pdf), by Pinjia He, Zhuangbin Chen, Shilin He, Michael R. Lyu.
1. [**SOSP'17**] [Log20: Fully Automated Optimal Placement of Log Printing Statements under Specified Overhead Threshold](http://log20.dsrg.utoronto.ca/log20_sosp17_paper.pdf), by Xu Zhao, Kirk Rodrigues, Yu Luo, Michael Stumm, Ding Yuan, Yuanyuan Zhou. 
1. [**ICSE'17**] [Characterizing and Detecting Anti-patterns in the Logging Code](http://www.cse.yorku.ca/~zmjiang/publications/icse2017_chen.pdf), by Boyuan Chen and Zhen Ming (Jack) Jiang. 
1. [**Ebook'17**] [The Complete Guide to Java Logging in Production](https://user-assets-unbounce-com.s3.amazonaws.com/b93ede49-06e1-44dc-9caf-8ca7fe04896f/7af016fa-abc4-42e1-bfd9-be9b6b26b0ad/the-complete-guide-to-logging.original.pdf?x-amz-security-token=AgoJb3JpZ2luX2VjEKr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDmFwLXNvdXRoZWFzdC0xIkgwRgIhAKCp2NuGOQHgmAW8X%2FZ0LrYeBthhJwHVSaS7TErRt1MKAiEAhNr%2BfrrAe9KVMavGhqUeVIcB%2B8T5vv8MHk2hMGqX%2BlIq5AMIcxAAGgwwMDI2ODI4MTk5MzMiDK14rEtsh3W5EyDbpirBA%2FMmJjE0y4Tu%2FHvfAF3QGuccVbzhNTIo6tO2r0bmvcx6TJwAtCbfRZpnCksqioeUPumKd9HVoh2ZkuAFQNFE2%2B9MLM9M1p5W8FOQOmw%2FYmk0V%2B3cCWs3I%2BGH7xiSeNM7dOQAuHNsp62S4WDJ6xgp%2BPl2j4AqAu3EBDiXXCkn%2BvKqOOdtIa2jAeEBxaYh7b52CT6HAiv8v5l86gGRASOx4aHjUIzF%2FxnRZ0Z1VuV3%2BmTwyGUnYmSIjfbGNf0r0JlctUKXyn84LI0TRmUqRh%2B16XCXeOhE7%2BfKZKuMNEssSra7XuV6t32bF3wYvD5vEHfYze1jqpkLZQMi%2BIvjc99iqBXk8UQEr39fctSUtkjfxaLib6UWLjievXPZnz3YmhhaYmQa14ozi%2FqkTdUMeZgWn8scjRRLIGUeun6F1xxqIUJXnnjSNDRTtcFRizPH3keATtNhwAbudsYOCgAx9KBuNkFn1W6VUjqG0PkrTuNnJNZ1DgOG2a4lEF2h2Qk%2BjvZ64rpLyZfDqEYABvpZejTRvjxDtHozhIWQ3epqb3cj3tV34VIlt75HtYtQk4eOqbTd%2BFGndTfZqchwo9jtXUkXX2twMPX%2FtuUFOrMBEe2rMiJ%2BCus%2FS0YOIFp2F2JJfRkFvUP%2B3u2yFIHj04Ahaa6G8BW%2F1II%2BjnrZbvZKBmxe2oINZriybKzztY%2BYFiScWrUgGy9QVavKRJpaZ7OsCSIKp%2Bl7TLp1M0%2BRcvu%2B7MAhV%2BuGTTEMpBlV1StKhhHb8pNnGaeiiQ76%2BuYxjLz7Z9Uo7FJAza64l1tvNtrCBww37DFB5cUsXD6D0j90td6jRcC65Whs3Uk%2Fabd0cZYDNks%3D&AWSAccessKeyId=ASIAQBH7ISVOZV6MYNNT&Expires=1554893957&Signature=aWBeSqDU2rfYJNRoRuQRlO1Zbqc%3D), by Henn Idan. [**OverOps**]
1. [**ATC'15**] [Log2: A Cost-Aware Logging Mechanism for Performance Diagnosis](https://www.usenix.org/node/190487), by Rui Ding, Hucheng Zhou, Jian-Guang Lou, Hongyu Zhang, Qingwei Lin, Qiang Fu, Dongmei Zhang, Tao Xie. [**Microsoft**]
1. [**OSDI'12**] [Be Conservative: Enhancing Failure Diagnosis with Proactive Logging](http://www.eecg.toronto.edu/~yuan/papers/osdi12-errlog.pdf), by Ding Yuan, Soyeon Park, Peng Huang, Yang Liu, Michael M. Lee, Xiaoming Tang, Yuanyuan Zhou, and Stefan Savage. 
1. [**ICSE'12**] [Characterising Logging Practices in Open-Source Software](http://opera.ucsd.edu/paper/log_icse12.pdf), by Ding Yuan, Soyeon Park and Yuanyuan Zhou. 
1. [**ICSE'12**] [Bridging the Divide between Software Developers and Operators using Logs](https://users.encs.concordia.ca/~shang/pubs/icse2012_Shang.pdf), by Weiyi Shang.
1. [**TOCS'12**][**ASPLOS'11**] [Improving Software Diagnosability via Log Enhancement](http://opera.ucsd.edu/paper/asplos11-logenhancer.pdf), by Ding Yuan, Jing Zheng, Soyeon Park, Yuanyuan Zhou, and Stefan Savage. 

### Tracing Practices

### Log Parsing
1. [**TSE'20**] [Logram: Efficient Log Parsing Using n-Gram Dictionaries](https://arxiv.org/pdf/2001.03038.pdf), by Hetong Dai, Heng Li, Che-Shao Chen, Weiyi Shang, Tse-Hsun Chen.
1. [**ECML-PKDD'20**] [Self-Supervised Log Parsing](https://arxiv.org/pdf/2003.07905.pdf), by Sasho Nedelkoski, Jasmin Bogatinovski, Alexander Acker, Jorge Cardoso, Odej Kao.
1. [**ICSE'19**] [Tools and Benchmarks for Automated Log Parsing](https://arxiv.org/pdf/1811.03509.pdf), by Jieming Zhu, Shilin He, Jinyang Liu, Pinjia He, Qi Xie, Zibin Zheng, Michael R. Lyu. [**Huawei**]
1. [**ICPC'18**] [A Search-based Approach for Accurate Identification of Log Message Formats](http://publications.uni.lu/bitstream/10993/35286/1/ICPC-2018.pdf), by Salma Messaoudi, Annibale Panichella, Domenico Bianculli, Lionel Briand, Raimondas Sasnauskas.
1. [**TDSC'18**] [Towards Automated Log Parsing for Large-Scale Log Data Analysis](https://jiemingzhu.github.io/pub/pjhe_tdsc2017.pdf), by Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. 
1. [**CIKM'16**] [LogMine: Fast Pattern Recognition for Log Analytics](http://www.cs.unm.edu/~mueen/Papers/LogMine.pdf), by Hossein Hamooni, Biplob Debnath, Jianwu Xu, Hui Zhang, Geoff Jiang, Adbullah Mueen. [**NEC**]
1. [**ICWS'17**] [Drain: An Online Log Parsing Approach with Fixed Depth Tree](https://jiemingzhu.github.io/pub/pjhe_icws2017.pdf), by Pinjia He, Jieming Zhu, Zibin Zheng, Michael R. Lyu.
1. [**ICDM'16**] [Spell: Streaming Parsing of System Event Logs](https://www.cs.utah.edu/~lifeifei/papers/spell.pdf), by Min Du, Feifei Li. 
1. [**DSN'16**] [An Evaluation Study on Log Parsing and Its Use in Log Mining](https://jiemingzhu.github.io/pub/pjhe_dsn2016.pdf), by Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu.
1. [**TKDE'12**] [A Lightweight Algorithm for Message Type Extraction in System Application Logs](http://ieeexplore.ieee.org/abstract/document/5936060/), by Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios.
1. [**CIKM'11**] [LogSig: Generating System Events from Raw Textual Logs](https://users.cs.fiu.edu/~taoli/pub/liang-cikm2011.pdf), by Liang Tang, Tao Li, Chang-Shing Perng.
1. [**KDD'09**] [Clustering Event Logs Using Iterative Partitioning](https://web.cs.dal.ca/~makanju/publications/paper/kdd09.pdf), by Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios.


### Log Compression
1. [**ASE'19**] [Logzip: Extracting Hidden Structures via Iterative Clustering for Log Compression], by Jinyang Liu, Jieming Zhu, Shilin He, Pinjia He, Zibin Zheng, Michael R. Lyu. [**Huawei**]
1. [**CCGrid'15**] [Cowic: A Column-Wise Independent Compression for Log Stream Analysis](https://ieeexplore.ieee.org/document/7152468), by Hao Lin, Jingyu Zhou, Bin Yao, Minyi Guo, Jie Li.
1. [**MILCOM'14**] [Lightweight Packing of Log Files for Improved Compression in Mobile Tactical Networks](https://ws680.nist.gov/publication/get_pdf.cfm?pub_id=915734), by Peter Mell, Richard E. Harang.
1. [**SIGMOD'13**] [Adaptive Log Compression for Massive Log Data](https://www.cs.utah.edu/~lifeifei/papers/compresslog.pdf), by Robert Christensen and Feifei Li. [[Code](https://pubweb.eng.utah.edu/~robertc/archiver.html#code)]
1. [**DCC'04**] [High Density Compression of Log Files](https://ieeexplore.ieee.org/document/1281533/), by Balázs Rácz, András Lukács. 


### Empirical Studies
1. [**FSE'19**] [How Bad Can a Bug Get? An Empirical Analysis of Software Failures in the OpenStack Cloud Computing Platform](https://arxiv.org/abs/1907.04055), by Domenico Cotroneo, Luigi De Simone, Pietro Liguori, Roberto Natella, and Nematollah Bidokhti. [**Futurewei Technologies**]
1. [**DSN'19**] [Characterizing and Understanding HPC Job Failures over The 2K-day Life of IBM BlueGene/Q System](http://icl.utk.edu/jlesc9/files/STM3.2/jlesc9_sheng_mira.pdf), by Sheng Di, Hanqi Guo, Eric R. Pershey, Marc Snir, Franck Cappello.
1. [**DSN'07**] [What Supercomputers Say: A Study of Five System Logs](http://ieeexplore.ieee.org/document/4273008/), by Adam J. Oliner, Jon Stearley.

### Industrial Talks
