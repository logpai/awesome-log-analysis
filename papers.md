# Papers

+ [Surveys & Tutorials](#Surveys--Tutorials)
+ [Anomaly Detection](#anomaly-detection)
+ [Failure Prediction](#Failure-Prediction)
+ [Failure Diagnosis/ Debugging](#failure-diagnosis-debugging)
+ [Performance Issues](#performance-issues)
+ [Energy Issues](#Energy-Issues)
+ [Security Issues](#Security-Issues)
+ [Issue Categorization](#issue-categorization)
+ [Duplicate Issues Identification](#duplicate-issues-identification)
+ [Software Testing](#software-testing)
+ [Bug Finding](#Bug-Finding)
+ [Logging Practices](#logging-practices)
+ [Tracing Practices](#tracing-practices)
+ [Log Parsing](#log-parsing)
+ [Log Compression](#log-compression)
+ [Empirical Studies](#empirical-studies)
+ [Industrial Talks](#Industrial-Talks)

### Surveys & Tutorials
1. [**Theis**] [Log Engineering: Towards Systematic Log Mining to Support the Development of Ultra-large Scale Systems](https://users.encs.concordia.ca/~shang/pubs/2014_LogEngineering_TowardsSystematicLogMiningToSupportTheDevelopmentOfUltra-largeScaleSystems.pdf), by Weiyi Shang.
1. [**Book'14**] [I Heart Logs](https://www.oreilly.com/library/view/i-heart-logs/9781491909379/), by by Jay Kreps.
1. [**Book'12**] [Logging and Log Management: The Authoritative Guide to Understanding the Concepts Surrounding Logging and Log Management](http://mirror.thelifeofkenneth.com/sites/qt.vidyagam.es/library/Forensics/Logging%20and%20Log%20Management_%20The%20Authoritats%20Surrounding%20Logging%20and%20Log%20Management/Logging%20and%20Log%20Management_%20The%20Authoritative%20Guide%20to%20Undeanagement%20-%20Anton%20Chuvakin%20&%20Kevin%20Schmidt%20&%20Chris%20Phillips.pdf), by Anton A. Chuvakin, Kevin J. Schmidt, Christopher Phillips.

### Anomaly Detection
1. [**BigData'18**] [Evaluation of Distributed Machine Learning Algorithms for Anomaly Detection from Large-Scale System Logs: A Case Study](https://ieeexplore.ieee.org/document/8621967), by Merve Astekin, Harun Zengin, Hasan Sözer.
1. [**OSDI'18**] [Capturing and Enhancing In Situ System Observability for Failure Detection](https://www.usenix.org/conference/osdi18/presentation/huang), by Peng Huang, Chuanxiong Guo, Jacob R. Lorch, Lidong Zhou, Yingnong Dang. [**ByteDance, Microsoft**]
1. [**IEEE Access'18**] [An Integrated Method for Anomaly Detection From Massive System Logs](https://ieeexplore.ieee.org/document/8371223), by Zhaoli Liu, Tao Qin, Xiaohong Guan, Hezhi Jiang, Chenxu Wang.
1. [**NOMS'18**] [An Unsupervised Framework for Detecting Anomalous Messages from Syslog Log Files](https://ccdcoe.org/uploads/2018/11/Tech-Reserach-Paper-on-Log-Anomaly_oct-2018_Bernhards-Blumbergs-Kont.pdf), by Risto Vaarandi, Bernhards Blumbergs, Markus Kont.
1. [**ISSRE'17**] [Experience Report: Log Mining using Natural Language Processing and Application to Anomaly Detection](https://hal.laas.fr/hal-01576291/document), by Christophe Bertero, Matthieu Roy, Carla Sauvanaud and Gilles Tredan.
1. [**ISSRE'16**] [Experience Report: System Log Analysis for Anomaly Detection](https://jiemingzhu.github.io/pub/slhe_issre2016.pdf), by Shilin He, Jieming Zhu, Pinjia He, Michael R. Lyu. 

### Failure Prediction

### Diagnosis/ Debugging / Root Cause Analysis
1. [**OSDI'18**] [REPT: Reverse Debugging of Failures in Deployed Software](https://www.usenix.org/conference/osdi18/presentation/weidong), by Weidong Cui, Xinyang Ge, Baris Kasikci, Ben Niu, Upamanyu Sharma, Ruoyu Wang, Insu Yun. [**Microsoft**]
1. [**Ebook'17**] [The Complete Guide to Automated Root Cause Analysis](https://user-assets-unbounce-com.s3.amazonaws.com/b93ede49-06e1-44dc-9caf-8ca7fe04896f/e3de36aa-27d3-4298-94e8-4bfa39c3094b/complete-guide-to-automated-root-cause-analysis.original.pdf?x-amz-security-token=AgoJb3JpZ2luX2VjELn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDmFwLXNvdXRoZWFzdC0xIkYwRAIgRTR5pUWub9t9Ztk9IxEendfJ0cLHPBxhuNqR4EKAN%2B8CIFBkVapD0NJ50o1pfBq3kmTCcV7J0r8dQs7RLph4nL4JKu0DCIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMMDAyNjgyODE5OTMzIgyY3%2BkRc%2FbBvrLEnQYqwQNxkS1vUhjgDa3kp9p%2Bq1gDu3AEen7kgg2evhLRm1gHuZ3G7dp7555eK0%2BQ9pph%2FOG9zhkCms1%2F%2Brc%2BTPkdIgsAxOLEz3g%2BWZwbjbCzt%2Bjea2ktFzuC2VKyXTzsk9vaB6qI70sZ5r6Xv7NnuKPvAWT1cpt6q752yiP5Qy89KvHY9hAh8irwzcMfRqT8LvmY9W8%2FiPuyjBKhQBQrl1S%2BLKq0Qoy80WDlfqLKyhqI4L58c3JYebZeKc%2Bs4IwHU8rLZKPhjxU93YzALjxXwkZethCImCaE%2F8HhTlpNkO0fVKjCUS8o6I4HUvr9IhVh8HbXFlbf9OrBTDVZCwtU6X6%2FViDrYe7BpPDJb4uviaUQ93ij39QuAPl4TqBZ7AYBapdZ8UH4RiHUlQaDHSyrZxLd07rdBdovHSttC7k8eXR9SsbN5SP6Sdwjmgrw4Ln6Mdl5byJ%2BxQ9BKY4tCH%2BKpuRGfwL6mbpPhjSFAP8yJTW%2BW9A4uYm%2Bygrikx765hlgjmSJcrykHY9x4ohW%2FjrEcYPkJi2kZ2CvgY0WUEzBoRAkfo7gFDfXtA5NmvQsx13L9YmC4JTR10xzhqy%2BwbVDBl6MfyXhBDDBq7rlBTq1Ac02Lcx%2FJ5pZ4DmTK6HrfiXhWQ05VOPusCyRennmN1Tct3ZOPy9dJscWHdM1tVWdOK5ilkfRupgEzdohXF7ezRrMnv%2BjaMcrx%2BQS51eWerZgdAcHwtPJJ6w42Tc9ubpq0uZXCwhPd6PUew9B5yPfq4gkiZ1B3FsTCHef4l%2FhSMcsTcXFqNGUHdRHwBd0MNH2pzfHAOqVQMKQJU9Me5KGDlUe3%2BidObCWYoVa6teSoy%2Bk%2Bl5sZlk%3D&AWSAccessKeyId=ASIAQBH7ISVO3DBFXSYX&Expires=1554948093&Signature=uNk%2FEbzw8oHYtW8xBGEabVNP0ew%3D), by Tali Soroker. [**OverOps**]
1. [**ICSE'13**] [Assisting Developers of Big Data Analytics Applications When Deploying on Hadoop Clouds](http://www.cse.yorku.ca/~zmjiang/publications/ICSE2013_Shang.pdf), by Weiyi Shang, Zhen Ming Jiang, Hadi Hemmati, Bram Adams, Ahmed E. Hassan and Patrick Marin. [**ACM SIGSOFT Distinguished Paper Award**] 
1. [**ASPLOS'10**] [SherLog: Error Diagnosis by Connecting Clues from Run-time Logs ](http://opera.ucsd.edu/paper/asplos10-sherlog.pdf), by Ding Yuan, Haohui Mai, Weiwei Xiong, Lin Tan, Yuanyuan Zhou and Shankar Pasupathy. 

### Failure Reproduction
1. [**SOSP'17**] [Pensieve: Non-Intrusive Failure Reproduction for Distributed Systems using the Event Chaining Approach](http://www.eecg.toronto.edu/~yuan/papers/pensieve-sosp17.pdf), by Yongle Zhang, Serguei Makarov, Xiang Ren, David Lion, Ding Yuan.

### Performance Issues
1. [**SOSP'17**] [Non-intrusive Performance Profiling of Entire Software Stacks based on the Flow Reconstruction Principle ](http://www.eecg.toronto.edu/~yuan/papers/zhao_stitch.pdf), by Xu Zhao, Kirk Rodrigues, Yu Luo, Ding Yuan, and Michael Stumm.
1. [**SOSP'17**] [lprof: A Non-intrusive Request Flow Profiler for Distributed Systems](http://www.eecg.toronto.edu/~yuan/papers/lprof_osdi14.pdf), by Xu Zhao, Yongle Zhang, David Lion, Muhammad FaizanUllah, Yu Luo, Ding Yuan, and Michael Stumm.

### Energy Issues
### Security Issues

### Issue Categorization
1. [**IWQoS'18**] [Device-Agnostic Log Anomaly Classification with Partial Labels](https://aiops.org/wp-content/uploads/2018/06/Device_Agnostic_Log_Anomaly_Classification.pdf), by Weibin Meng, Ying Liu, Shenglin Zhang, Dan Pei, Hui Dong, Lei Song, Xulong Luo. [**Baidu**]
1. [**BigData'17**] [WEAC: Word Embeddings for Anomaly Classification from Event Logs](https://ieeexplore.ieee.org/document/8258034), by Amit Pande, Vishal Ahuja. [**Target Corporation**]

### Duplicate Issues Identification
1. [**TSE'18**] [Revisiting the Performance Evaluation of Automated Approaches for the Retrieval of Duplicate Issue Reports](https://sail.cs.queensu.ca/Downloads/TSE2017_RevisitingThePerformanceEvaluationOfAutomatedApproachesForTheRetrievalOfDuplicateIssueReports.pdf), by 	Mohamed Sami Rakha, Cor-Paul Bezemer, Ahmed E. Hassan.
1. [**DSN'14**] [Mining Historical Issue Repositories to Heal Large-Scale Online Service Systems](https://ieeexplore.ieee.org/abstract/document/6903589), by Rui Ding, Qiang Fu, Jian-Guang Lou, Qingwei Lin, Dongmei Zhang, Tao Xie. [**Microsoft**] 
1. [**ICDM'14**] [Identifying Recurrent and Unknown Performance Issues](https://ieeexplore.ieee.org/document/7023349), by Meng-Hui Lim, Jian-Guang Lou, Hongyu Zhang, Qiang Fu, Andrew Beng Jin Teoh, Qingwei Lin, Rui Ding, Dongmei Zhang. [**Microsoft**]

### Software Testing

1. [**ASE'18**] [An Automated Approach to Estimating Code Coverage Measures via Execution Logs](http://www.cse.yorku.ca/~zmjiang/publications/ase2018_chen.pdf), by Boyuan Chen, Jian Song, Peng Xu, Xing Hu, Zhen Ming (Jack) Jiang.

### Bug Finding
1. [**OSDI'18**] [Finding Crash-Consistency Bugs with Bounded Black-Box Crash Testing](https://www.usenix.org/conference/osdi18/presentation/mohan), by Jayashree Mohan, Ashlie Martinez, Soujanya Ponnapalli, Pandian Raju, Vijay Chidambaram. [**VMware**]

### Logging Practices
1. [**ICSE'19**] [DLFinder: Characterizing and Detecting Duplicate Logging Code Smells](https://users.encs.concordia.ca/~shang/pubs/icse2019_zhenhao.pdf), by Zhenhao Li, Tse-Hsun Chen, Jinqiu Yang and Weiyi Shang.
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
1. [**ICSE'19**] [Tools and Benchmarks for Automated Log Parsing](https://arxiv.org/pdf/1811.03509.pdf), by Jieming Zhu, Shilin He, Jinyang Liu, Pinjia He, Qi Xie, Zibin Zheng, Michael R. Lyu. 
1. [**ICPC'18**] [A Search-based Approach for Accurate Identification of Log Message Formats](http://publications.uni.lu/bitstream/10993/35286/1/ICPC-2018.pdf), by Salma Messaoudi, Annibale Panichella, Domenico Bianculli, Lionel Briand, Raimondas Sasnauskas.
1. [**TDSC'18**] [Towards Automated Log Parsing for Large-Scale Log Data Analysis](https://jiemingzhu.github.io/pub/pjhe_tdsc2017.pdf), by Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. 
1. [**CIKM'16**] [LogMine: Fast Pattern Recognition for Log Analytics](http://www.cs.unm.edu/~mueen/Papers/LogMine.pdf), by Hossein Hamooni, Biplob Debnath, Jianwu Xu, Hui Zhang, Geoff Jiang, Adbullah Mueen. [**NEC**]
1. [**ICDM'16**] [Spell: Streaming Parsing of System Event Logs](https://www.cs.utah.edu/~lifeifei/papers/spell.pdf), by Min Du, Feifei Li. 
1. [**ICWS'17**] [Drain: An Online Log Parsing Approach with Fixed Depth Tree](https://jiemingzhu.github.io/pub/pjhe_icws2017.pdf), by Pinjia He, Jieming Zhu, Zibin Zheng, Michael R. Lyu.
1. [**DSN'16**] [An Evaluation Study on Log Parsing and Its Use in Log Mining](https://jiemingzhu.github.io/pub/pjhe_dsn2016.pdf), by Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu.
1. [**TKDE'12**] [A Lightweight Algorithm for Message Type Extraction in System Application Logs](http://ieeexplore.ieee.org/abstract/document/5936060/), by Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios.
1. [**CIKM'11**] [LogSig: Generating System Events from Raw Textual Logs](https://users.cs.fiu.edu/~taoli/pub/liang-cikm2011.pdf), by Liang Tang, Tao Li, Chang-Shing Perng.
1. [**KDD'09**] [Clustering Event Logs Using Iterative Partitioning](https://web.cs.dal.ca/~makanju/publications/paper/kdd09.pdf), by Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios.
1. [**ICDM'09**] [Execution Anomaly Detection in Distributed Systems through Unstructured Log Analysis](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/DM790-CR.pdf), by Qiang Fu, Jian-Guang Lou, Yi Wang, Jiang Li. [**Microsoft**]

### Log Compression
1. [**CCGrid'15**] [Cowic: A Column-Wise Independent Compression for Log Stream Analysis](https://ieeexplore.ieee.org/document/7152468), by Hao Lin, Jingyu Zhou, Bin Yao, Minyi Guo, Jie Li.
1. [**MILCOM'14**] [Lightweight Packing of Log Files for Improved Compression in Mobile Tactical Networks](https://ws680.nist.gov/publication/get_pdf.cfm?pub_id=915734), by Peter Mell, Richard E. Harang.
1. [**SIGMOD'13**] [Adaptive Log Compression for Massive Log Data](https://www.cs.utah.edu/~lifeifei/papers/compresslog.pdf), by Robert Christensen and Feifei Li. [[Code](https://pubweb.eng.utah.edu/~robertc/archiver.html#code)]
1. [**DCC'04**] [High Density Compression of Log Files](https://ieeexplore.ieee.org/document/1281533/), by Balázs Rácz, András Lukács. 


### Empirical Studies
1. [**DSN'07**] [What Supercomputers Say: A Study of Five System Logs](http://ieeexplore.ieee.org/document/4273008/), by Adam J. Oliner, Jon Stearley.

### Industrial Talks
