# Paper collection Work

## Conference & Journal Information
- The conference & journals that we include
- [ICSE](https://dblp.org/db/conf/icse/)
- [FSE](https://dblp.org/db/conf/sigsoft/)
- [ASE](https://dblp.org/db/conf/kbse/)
- [PLDI](https://dblp.org/db/conf/pldi/)
- [POPL](https://dblp.org/db/conf/popl/)
- [ISSTA](https://dblp.org/db/conf/issta/)
- [TOSEM](https://dblp.org/db/journals/tosem/)
- [TSE](https://dblp.org/db/journals/tse/)
- [CCS](https://dblp.org/db/conf/ccs/)
- [S&P](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8013)
- 计算机学报
- 软件学报

## Taxonomy
1. Present in a chronological order 以年代为主序
2. In three seperate class: bug detection; bug classification; bug remedation 用Tags标签来区分
3. In every year, classified by Confereces & Journal 以不同会议名称为辅序

## Tags
- `security`
- `detect`
- - `classification`
- `fix`
- `predict`
- `recommendation`
- `automatic`
- :blush: // GOOD article
- yet to explore~~

## Directory
1. [2020](#2020)
2. [2019](#2019)
3. [2018](#2018)
4. [2017](#2017)
5. [2016](#2016)
6. [2015](#2015)

### 2020 

### 2019
#### ICSE
- H. Wang, Y. Li, S. W. Lin, L. Ma, and Y. Liu,[ “VULTRON: Catching vulnerable smart contracts once and for all” ](/bug_fixing_paper_collection/icse2019_bonus.pdf)
  - Tags: 
- S. Saha, R. K. Saha, and M. R. Prasad, [“Harnessing Evolution for Multi-Hunk Program Repair”](/bug_fixing_paper_collection/icse2019_2.pdf) 
  - Tags: `fix`
- D. X. B. Le, L. Bao, D. Lo, X. Xia, S. Li, and C. Pasareanu [“On Reliability of Patch Correctness Assessment”](/bug_fixing_paper_collection/icse2019_4.pdf)
  - Tags: `fix`
- M. Tufano, J. Pantiuchina, C. Wson, G. Bavota, and D. Poshyvanyk [“On Learning Meaningful Code Changes Via Neural Machine Translation” ](/bug_fixing_paper_collection/icse2019_3.pdf)

#### FSE
- A. Koyuncu et al., “[IFixR: Bug report driven program repair](/bug_fixing_paper_collection/fse2019_1.pdf),” ESEC/FSE 2019 - Proc. 2019 27th ACM Jt. Meet. Eur. Softw. Eng. Conf. Symp. Found. Softw. Eng., no. 1, pp. 314–325, 2019.
  - Tags: `fix`
- M. Bicocca and D. Ginelli, “[Failure-Driven Program Repair](/bug_fixing_paper_collection/fse2019_4.pdf),” ESEC/FSE 2019 - Proc. 2019 27th ACM Jt. Meet. Eur. Softw. Eng. Conf. Symp. Found. Softw. Eng., pp. 1156–1159, 2019.
  - Tags: `fix`
-	T. Sonnekalb, “[Machine-learning supported vulnerability detection in source code](/bug_fixing_paper_collection/fse2019_bonus.pdf),” ESEC/FSE 2019 - Proc. 2019 27th ACM Jt. Meet. Eur. Softw. Eng. Conf. Symp. Found. Softw. Eng., pp. 1180–1183, 2019.
- - Tags: `detect`
-	A. Shi, W. Lam, R. Oei, T. Xie, and D. Marinov, “[IFixFlakies: A framework for automatically fixing order-dependent flaky tests](/bug_fixing_paper_collection/fse2019_2.pdf),” ESEC/FSE 2019 - Proc. 2019 27th ACM Jt. Meet. Eur. Softw. Eng. Conf. Symp. Found. Softw. Eng., pp. 545–555, 2019.
  
#### ASE
- Cashin, C. Martinez, W. Weimer, and S. Forrest, “[Understanding automatically-generated patches through symbolic invariant differences](/bug_fixing_paper_collection/ase2019_3.pdf)” Proc. - 2019 34th IEEE/ACM Int. Conf. Autom. Softw. Eng. ASE 2019, pp. 411–414, 2019.
  - Tags: `fix`
- V. Sharma, “[Automatically repairing binary programs using adapter synthesis](/bug_fixing_paper_collection/ase2019_5.pdf),” Proc. - 2019 34th IEEE/ACM Int. Conf. Autom. Softw. Eng. ASE 2019, pp. 1238–1241, 2019.
  - Tags: `fix` `binary programs`
- M. Soto, “[Improving patch quality by enhancing key components of automatic program repair](/bug_fixing_paper_collection/ase2019_4.pdf),” Proc. - 2019 34th IEEE/ACM Int. Conf. Autom. Softw. Eng. ASE 2019, pp. 1230–1233, 2019.
  - Tags: `fix`

#### ISSTA
- A. Ghanbari, S. Benton, and L. Zhang, “[Practical program repair via bytecode mutation](/bug_fixing_paper_collection/issta2019_2.pdf),” ISSTA 2019 - Proc. 28th ACM SIGSOFT Int. Symp. Softw. Test. Anal., pp. 19–30, 2019.
  - Tags: `fix`
- K. Liu, A. Koyuncu, D. Kim, and T. F. Bissyandé, “[TBAR: Revisiting template-based automated program repair](/bug_fixing_paper_collection/issta2019_3.pdf),” ISSTA 2019 - Proc. 28th ACM SIGSOFT Int. Symp. Softw. Test. Anal., pp. 43–54, 2019.
  - Tags: `fix`
- X. Gao, S. Mechtaev, and A. Roychoudhury, “[Crash-avoiding program repair](/bug_fixing_paper_collection/issta2019_1.pdf),” ISSTA 2019 - Proc. 28th ACM SIGSOFT Int. Symp. Softw. Test. Anal., pp. 8–18, 2019.
  - Tags: `fix`

#### TSE
- L. Gazzola, D. Micucci, and L. Mariani, “[Automatic Software Repair: A Survey](/bug_fixing_paper_collection/tse2019_1.pdf),” IEEE Trans. Softw. Eng., vol. 45, no. 1, pp. 34–67, 2019.
  - Tags: `fix` `survey`

### 2018
#### ICSE
- Sergey Mechtaev, Manh-Dung Nguyen, Yannic Noller, Lars Grunske, and Abhik Roychoudhury. 2018. [Semantic Program Repair Using a Reference Implementation](/bug_fixing_paper_collection/icse2018_5.pdf)
  - Tags: `fix`
- Rijnard van Tonder and Claire Le Goues. 2018. [Static Automated Program Repair for Heap Properties.](/bug_fixing_paper_collection/icse2018_6.pdf)
  - Tags: `fix`
- Ming Wen, Junjie Chen, Rongxin Wu, Dan Hao, Shing-Chi Cheung. 2018. [Context-Aware Patch Generation for Better Automated Program Repair.](/bug_fixing_paper_collection/icse2018_1.pdf)
  - Tags: `fix`
- Jinru Hua, Mengshi Zhang, Kaiyuan Wang and Sarfraz Khurshid. 2018. [Towards Practical Program Repair with On-Demand Candidate Generation.](/bug_fixing_paper_collection/icse2018_2.pdf)
  - Tags: `fix`
  
#### FSE
- Andrea Stocco, Rahulkrishna Yandrapally, and Ali Mesbah. 2018. [Visual Web Test Repair](/bug_fixing_paper_collection/fse2018_4.pdf).
  - Tags: `fix` `visual`

#### ASE
- Martin White, and Denys Poshyvanyk. 2018. [An Empirical Investigation into Learning Bug-Fixing Patches in the Wild via Neural Machine Translation.] (/bug_fixing_paper_collection/tosem2019_ase.pdf)
  - Tags: `fix` 
 
#### ISSTA
- Jiajun Jiang, Yingfei Xiong, Hongyu Zhang, Qing Gao, and Xiangqun Chen. 2018. [Shaping Program Repair Space with Existing Patches and Similar Code.](/bug_fixing_paper_collection/issta2018_1.pdf)
  - Tags: `fix` `automatic`
  
#### TOSEM
- Klaas-Jan Stol and Brian Fitzgerald. 2018. [The ABC of Software Engineering Research.](/bug_fixing_paper_collection/tosem2018_ABC.pdf)
  - Tags: :blush: `ABC`
- Sergey Mechtaev, Xiang Gao, Shin Hwei Tan, and Abhik [Roychoudhury. 2018. Test-Equivalence Analysis for Automatic Patch Generation](/bug_fixing_paper_collection/tosem2018_1.pdf).
  - Tags: `fix`

#### TSE
- Mayy Habayeb  Syed Shariyar Murtaza, Andriy Miranskyy[On the Use of Hidden Markov Model to Predict the Time to Fix Bugs](/bug_fixing_paper_collection/tse2018_1.pdf).
  - Tags: `fix`  

#### 软件学报
- 周风顺,王林章,李宣东.[C/C++程序缺陷自动修复与确认方法](/bug_fixing_Chinese_conf/程序缺陷自动修复与确认方法_周风顺.pdf)
  - Tags: `automatic` `fix`
- 李斌,贺也平,马恒太.[程序自动修复:关键问题及技术](/bug_fixing_Chinese_conf/程序自动修复_关键问题及技术_李斌.pdf)
  - Tags: `automatic` `fix`
- 朱子骁,邹艳珍,华晨彦,沈琦,赵俊峰.[基于StackOverflow 数据的软件功能特征挖掘组织方法](/bug_fixing_Chinese_conf/基于StackOverflow数据的软件功能特征挖掘组织方法_朱子骁.pdf)
  - Tags: `detect`
#### 计算机学报
- 刘旭亮，钟浩．[一种基于StackOverflow 分析的程序自动修复方法](/bug_fixing_Chinese_conf/一种基于StackOverflow分析的程序自动修复方法_刘旭亮.pdf)
  - Tags: `automatic` `fix`
- 王赞 [自动程序修复方法研究述评](/bug_fixing_Chinese_conf/自动程序修复方法研究述评_王赞.pdf)
  - Tags: `综述` `fix`
### 2017
#### ICSE
- Yingfei Xiong, Jie Wang, Runfa Yan, Jiachen Zhang, Shi Han§, Gang Huang, Lu Zhang [Precise Condition Synthesis for Program Repair](/bug_fixing_paper_collection/icse2017_2.pdf)
  - Tags: `fix`

#### FSE
- Fan Long, Peter Amidon, and Martin Rinard. 2017. [Automatic Inference of Code Transforms for Patch Generation](/bug_fixing_paper_collection/fse2017_4.pdf).
  - Tags: `fix` `java`
- Yuchi Tian, Baishakhi Ray. 2017. [Automatically Diagnosing and Repairing Error Handling Bugs in C](/bug_fixing_paper_collection/fse2017_3.pdf).
  - Tags: `fix` `C`
- Marcel Böhme, Ezekiel O. Soremekun, Sudipta Chattopadhyay, Emamurho Ugherughe, and Andreas Zeller. 2017. [Where Is the Bug and How Is It Fixed? An Experiment with Practitioners.](/bug_fixing_paper_collection/fse2017_1.pdf)
  - Tags: `fix`
- Sahil Verma and Subhajit Roy. 2017. [Synergistic Debug-Repair of Heap Manipulations.](/bug_fixing_paper_collection/fse2017_2.pdf)
  - Tags: `fix`
  
#### ASE
#### PLDI
#### POPL
#### ISSTA
#### TOSEM
#### TSE


### 2016
#### ICSE
#### FSE
#### ASE
#### PLDI
#### POPL
#### ISSTA
#### TOSEM
#### TSE

#### 软件学报
- 玄跻峰,任志磊,王子元,谢晓园,江贺.[自动程序修复方法研究进展](/bug_fixing_Chinese_conf/自动程序修复方法研究进展_玄跻峰.pdf)
  - Tags: `综述` `fix`
### 2015
#### ICSE
#### FSE
#### ASE
#### PLDI
#### POPL
#### ISSTA
#### TOSEM
#### TSE

