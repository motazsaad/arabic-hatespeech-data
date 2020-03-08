# OffensEval 2020: Arabic!

Dataset and detailed task description available at: https://sites.google.com/site/offensevalsharedtask/home
 
This is the competition site for the development set of the second edition of OffensEval organized at SemEval 2020 (Task 12). SemEval 2020 will take place on September 13 and 13, 2020 co-located with COLING in Barcelona, Spain. http://alt.qcri.org/semeval2020/ 
 
This year OffensEval's title is Multilingual Offensive Language Identification in Social Media.
 
The first OffensEval was organized at SemEval 2019 http://alt.qcri.org/semeval2019/ . OffensEval 2019 used the Offensive Language Identification dataset (OLID) a dataset containing English tweets annotated using a hierarchical three-level annotation model described in this paper https://www.aclweb.org/anthology/papers/N/N19/N19-1144/ . Nearly 800 teams signed up to participate in OffensEval 2019. The competition received more than 100 submissions across three sub-tasks.The findings are described in the OffensEval 2019 report https://www.aclweb.org/anthology/papers/S/S19/S19-2010/. The response received in 2019 by far exceeded our expectations and motivated us to organize OffensEval 2020. 

## Evaluation Criteria
Submissions will be evaluated for macro F1-score under subtask A. The labels are binary, OFF or NOT, for offensive and not offensive. The classes are imbalanced, hence use of F1.

## Terms and Conditions
The data in this competition, OffensEval 2020 - Arabic, is licensed under a Creative Commons Attribution licence (CC-BY).

**Description**

This is the website of the second edition of OffensEval organized at [SemEval 2020][2] (Task 12). SemEval 2020 will take place on September 13 and 13, 2020 co-located with COLING in Barcelona, Spain. 

This year OffensEval's title is **Multilingual Offensive Language Identification in Social Media**.

The first OffensEval was organized at [SemEval 2019][3]. [OffensEval 2019][4] used the [Offensive Language Identification dataset (OLID)][5] a dataset containing English tweets annotated using a hierarchical three-level annotation model described in [this paper][6]. Nearly 800 teams signed up to participate in OffensEval 2019. The competition received more than 100 submissions across three sub-tasks.The findings are described in the [OffensEval 2019 report][7]. The response received in 2019 by far exceeded our expectations and motivated us to organize OffensEval 2020. 

**Motivation**

Offensive language is pervasive in social media. Individuals frequently take advantage of the perceived anonymity of computer-mediated communication, using this to engage in behavior that many of them would not consider in real life. Online communities, social media platforms, and technology companies have been investing heavily in ways to cope with offensive language to prevent abusive behavior in social media. One of the most effective strategies for tackling this problem is to use computational methods to identify offense, aggression, and hate speech in user-generated content (e.g. posts, comments, microblogs, etc.). 

This topic has attracted significant attention in recent years as evidenced in recent publications (Waseem et al. 2017; Davidson et al., 2017, Malmasi and Zampieri, 2018, Kumar et al. 2018) and workshops such as [AWL][8] and [TRAC][9] and competitions such as [HatEval 2019][10] (Basile et al. 2019), [HASOC 2019][11], and [OffensEval 2019][4] (Zampieri et al. 2019).

**Data**

OffensEval 2020 features a multilingual dataset with five languages. The languages included in OffensEval 2020 are:

* Arabic
* Danish
* English
* Greek
* Turkish

The annotation follows the hierarchical tagset proposed in the [Offensive Language Identification Dataset (OLID)][5] and used in OffensEval 2019. In this taxonomy we break down offensive content into the following three sub-tasks taking the **type** and **target** of offensive content into account. The following sub-tasks will be organized:

* Sub-task A - Offensive language identification;
* Sub-task B - Automatic categorization of offense types;
* Sub-task C - Offense target identification.

For English we will run sub-tasks A, B, and C. For the other 4 languages (Arabic, Danish, Greek, and Turkish), we will run sub-task A. 

* **Trial data**: **available [here][4].**
* **Training and development data**: The link and password was shared with registered participants**.** If you haven't received it, please contact: marcos.zampieri@rit.edu
* **Test data: **available on CodaLab. Links below. 

**CodaLab**

The test sets (except English) will be made available on February 20 at 00:01 (GMT) on the respective CodaLab. 

The English test set will be available on February 28 at 00:01 (GMT) on CodaLab. 

  
IMPORTANT: You are required to register your team in the competition using the form below before you register your username on CodaLab. We reserve the right to exclude entries to the competition that don't not follow the correct registration procedure. 

**Registration**

Please fill out [**this form**][12] to register your team receive the training sets. 

**Important Dates**

* **Trial data ready:** July 31, 2019 (available [here][4])
* **Training and development data:** January 6, 2020 (the link and password was shared with registered participants). If you registered and haven't received it, please contact: marcos.zampieri@rit.edu
* **Test data available/E****valuation starts:** Feb 20, 2020
    * **Sub-task A:** February 20 - March 4 (Arabic, Danish, Greek, and Turkish) **(extended deadline)**
    * **Sub-task A:** February 28 - March 11 (English only) **(extended deadline)**
    * **S****ub-task B:** February 28 - March 4 (English only)
    * **Sub-task C:** March 6 - March 11 (English only)
* **Evaluation ends:** March 11, 2020
* **Paper submission deadline: **April 17, 2020
* **Notification to authors:** June 10, 2020
* **Camera-ready due:** July 1, 2020
* **SemEval workshop: **September 13 and 13, 2020

**Organizers**

Marcos Zampieri - Rochester Institute of Technology, USA  
Preslav Nakov - Qatar Computing Research Institute, Qatar

Sara Rosenthal - IBM Research, USA

Pepa Atanasova - University of Copenhagen, Denmark

Georgi Karadzhov - University of Cambridge, UK

Hamdy Mubarak - Qatar Computing Research Institute, Qatar

Leon Derczynski - IT University Copenhagen, Denmark

Zeses Pitenis - University of Wolverhampton, UK

Çağrı Çöltekin - University of Tübingen, Germany

**Contact**

For language specific questions please contact the respective organizer:

* Arabic: hmubarak@hbku.edu.qa
* Danish: leod@itu.dk
* English: pepa.k.gencheva@gmail.com
* Greek: z.pitenis@wlv.ac.uk
* Turkish: ccoltekin@sfs.uni-tuebingen.de

For general questions please contact: marcos.zampieri@rit.edu

Two mailing lists available:

Organizers: semeval-2020-task-12-organizers@googlegroups.com

All participants: semeval-2020-task-12-all@googlegroups.com

**References**

Basile, V., Bosco, C., Fersini, E., Nozza, D., Patti, V., Pardo, F.M.R., Rosso, P. and Sanguinetti, M., (2019) Semeval-2019 task 5: Multilingual detection of hate speech against immigrants and women in twitter. In Proceedings of the 13th International Workshop on Semantic Evaluation (pp. 54-63).

Davidson, T., Warmsley, D., Macy, M. and Weber, I. (2017) Automated Hate Speech Detection and the Problem of Offensive Language. Proceedings of ICWSM.

Kumar, R., Ojha, A.K., Malmasi, S. and Zampieri, M. (2018) Benchmarking Aggression Identification in Social Media. In Proceedings of the First Workshop on Trolling, Aggression and Cyberbullying (TRAC). pp. 1-11.

Malmasi, S., Zampieri, M. (2018) Challenges in Discriminating Profanity from Hate Speech. Journal of Experimental & Theoretical Artificial Intelligence. Volume 30, Issue 2, pp. 187-202. Taylor & Francis. 

Waseem, Z., Davidson, T., Warmsley, D. and Weber, I. (2017) Understanding Abuse: A Typology of Abusive Language Detection Subtasks. Proceedings of the Abusive Language Online Workshop.

**Previous OffensEval**

**REPORT**

Zampieri, M., Malmasi, S., Nakov, P., Rosenthal, S., Farra, N. and Kumar, R. (2019) SemEval-2019 Task 6: Identifying and Categorizing Offensive Language in Social Media (OffensEval). In Proceedings of the 13th International Workshop on Semantic Evaluation. pp. 75-86.

**DATASET**

Zampieri, M., Malmasi, S., Nakov, P., Rosenthal, S., Farra, N. and Kumar, R. (2019) Predicting the Type and Target of Offensive Posts in Social Media. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers). pp. 1415-1420.


[1]: https://sites.google.com/site/offensevalsharedtask/_/rsrc/1564906056436/home/logo.png?height=200&width=200
[2]: http://alt.qcri.org/semeval2020/
[3]: http://alt.qcri.org/semeval2019/
[4]: https://sites.google.com/site/offensevalsharedtask/offenseval2019
[5]: https://sites.google.com/site/offensevalsharedtask/olid
[6]: https://www.aclweb.org/anthology/papers/N/N19/N19-1144/
[7]: https://www.aclweb.org/anthology/papers/S/S19/S19-2010/
[8]: https://sites.google.com/view/alw3/
[9]: https://sites.google.com/view/trac1/home
[10]: https://competitions.codalab.org/competitions/19935
[11]: https://hasoc2019.github.io/
[12]: https://forms.gle/y5ZRWkJFJ87R6Luz8

---

# OLID - OffensEval Shared Task

The Offensive Language Identification Dataset (OLID) contains a collection of 14,200 annotated English tweets using an annotation model that encompasses following three levels:

 

* A: Offensive Language Detection
* B: Categorization of Offensive Language
* C: Offensive Language Target Identification

 

OLID has been in students projects in different universities. To the best of our knowledge, so far it has been used by students at The University of Arizona (USA), Imperial College London (UK), and University of Leeds (UK) Some of the student system papers are available [here][1].

 

**Download OLID**

The complete dataset OLID v1.0 dataset (train, test, and gold labels) is available in the link below.

 

 

If you used OLID, please refer to this paper:

 

@inproceedings{zampierietal2019, 

    title={{Predicting the Type and Target of Offensive Posts in Social Media}}, 

    author={Zampieri, Marcos and Malmasi, Shervin and Nakov, Preslav and Rosenthal, Sara and Farra, Noura and Kumar, Ritesh}, 

    booktitle={Proceedings of NAACL}, 

    year={2019}

} 

[1]: https://scholar.harvard.edu/malmasi/offenseval-student-systems

  

  
