本项目主要实现了四个模块：  
- markov.py  
介绍：马尔科夫链又称**离散时间马尔科夫链**，是指满足马尔科夫性质的随机过程。马尔科夫链描述了在状态空间中从一个状态转移到另一个状态的随机过程，并且这个随机过程具有如下特点：  
1.下一个状态的概率分布只取决于前面有限个状态  
2.在时间序列中，下一个状态和有限个状态之前的事件均无关  
本模块实现一个简单的小例子  

- hmm_forward.py， hmm_backward.py  
本模块实现隐马尔科夫的前向算法和后向算法  

- hmm_viterbi.py  
本模块实现维特比算法  

- crf.py  
本模块实现基于sklearn的条件随机场算法  
