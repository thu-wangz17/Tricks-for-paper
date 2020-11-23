## 画图

* 设置子图：
```python
fig , ax = plt.subplots(nrows=3, ncols=5)
```

<img src=".\figure\v2-725ed5a26cc23afb6d39c01d242e416c_720w.jpg" alt="1" style="zoom:50%;" />

* 紧凑布局(Tight Layout)：

  上图横轴与纵轴的tick会有重叠，因此使用```tight_layout```

  ```python
  fig, ax = plt.subplots(tight_layout=True)
  ```

  ![2](.\figure\v2-69c6bfde4c05847870b057fd3c5f9d56_720w.jpg)

* 图中图(Inset)：

  ```python
  ax.plot(x, y)
  inset = plt.axes((.5, .5, .3, .3), facecolor='lightblue')
  inset.plot(x, y, color='r')
  ```

  <img src=".\figure\v2-cb707d77a7d0503fdbc6fe20140c2497_720w.jpg" alt="3" style="zoom:50%;" />

* 设定轴的缩放(Scale)：

  可选参数包括```linear```(default),```log```,```symlog```,```logit```

  ```python
  ax.set_yscale('log')
  ```

  <img src=".\figure\v2-d40633a32c8c039d656bd92442dbe868_720w.jpg" alt="4" style="zoom:67%;" />

  如图，如果不设置缩放，左图纵轴为线性，缩放后为右图。

以上内容参考https://zhuanlan.zhihu.com/p/118020086

* 改变字体：
  ```python
  plt.rc('font',family='Times New Roman', size=15)
  ```

* 保存图片：
  ```python
  plt.savefig('./test.png', dpi=500, bbox_inches='tight')
  ```
  ```bbox_inches='tight'```保证了保存的图片显示完整。

## 常用句式

* individuals, characters, folks 替换 people , persons.

* positive, favorable, rosy, promising, perfect, pleasurable, excellent, outstanding, superior 替换 good.

* dreadful, unfavorable, poor, adverse, ill 替换 bad(如果bad做表语，可以有be less impressive替换。)

* an army of, an ocean of, a sea of, a multitude of, a host of, if not most 替换 many.

* a slice of, quiet a few 替换 some.

* harbor the idea that, take the attitude that, hold the view that, it is  widely shared that, it is universally acknowledged that 替换 think。

* affair, business, matter 替换 thing.

* shared 替换 common .

* reap huge fruits 替换 get many benefits.

* for my part ,from my own perspective 替换 in my opinion.

* Increasing(ly), growing 替换 more and more(注意没有growingly这种形式。所以当修饰名词时用increasing/growing修饰形容词，副词用increasingly.)

* little if anything或little or nothing 替换 hardly.

* beneficial, rewarding 替换 helpful.

* shopper, client, consumer, purchaser 替换 customer.

* overwhelmingly, exceedingly, extremely, intensely 替换 very.

* hardly necessary, hardly inevitable…替换 unnecessary, avoidable.

* indispensable 替换 necessary.

* sth appeals to sb, sth exerts a tremendous fascination on sb 替换sb take interest in / sb. be interested in.

* capture one’s attention 替换 attract one’s attention.

* facet, demension, sphere 替换 aspet.

* be indicative of, be suggestive of, be fearful of 替换 indicate,suggest, fear.

* give rise to, lead to, result in, trigger 替换 cause.

* There are several reasons behind sth 替换…reasons for sth.

* desire 替换 want.

* pour attention into 替换 pay attention to.

* bear in mind that 替换 remember.

* enjoy, possess 替换 have(注意process是过程的意思)。

* interaction 替换 communication.

* frown on sth 替换 be against , disagree with sth .

* as an example 替换 for example, for instance.

* next to / virtually impossible 替换 nearly / almost impossible.

* regarding / concerning 替换 about.

* crucial /paramount 替换 important.

* 第一(in the first place/the first and foremost);第二(there is one more  point, I should touch on, that…);第三(the last but not the least).

*  assiduous 替换 hard-working.

* arduous 替换 difficult.

* underdeveloped / financially-challenged 替换poor(因为poor通常含有贬义).

* demonstrate / manifest 替换 show.

* invariably 替换 always.

* perilous / hazardous替换 dangerous.

* formidable 替换 difficult.

* quintessential 替换 typical(举例时常用，例如：a quintessential example should be cited that=for example; for instance).

* distinguished 替换 famous.

* feasible 替换 possible.

* consequently, accordingly替换 so.

* 通常，由数据推断出一定的结论，用Results indicate, infer, suggest, imply that……

* 最常见的引述别人观点的词汇:

  * Much of the research in sexual selection in the last two decades has  examined how a female’s preference that does not influence her immediate reproductive success can still evolve if it is genetically correlated  with another character under direct  selection.(不要每次写到研究时总用study，可以用些其它的词汇，比如examine，work。)
  * Two hypotheses for female preference evolution—runaway sexual selection  and good genes selection—state that preferences evolve indirectly  because they are genetically correlated with male traits that are under  direct selection; that is, the preferences themselves are not under  direct selection.(在引述别人的观点时，如果不能完全同意，使用state 比show更加中立些。)
  * Studies of receiver biases suggest that such analogies might not be broadly applicable.(suggest,又一种较为客观的引述观点的表达方法。)
  * Burley argued that the preference for red beaks is adaptive because it  indicates male health, and this preference is then transferred to  leg-band color.(argue,引用别人观点的又一表述。)
  * According to the anti-monotony hypothesis, habituation plays an  important role in the evolution of complex vocalizations in songbirds:  Increased song complexity reduces habituation of neighboring males and  courting females.(根据…)
  * Previous studies of acoustic and bioluminescent interactions had  emphasized potential advantages to group-signaling organization, such as minimizing predation, preserving species-specific signal characters, or increasing the attractiveness of the group.(带有小小的强调)

* 常见的连接词有，However, also, in addition, consequently, afterwards,  moreover, Furthermore, further, although, unlike, in contrast,  Similarly, Unfortunately, alternatively, parallel results, In order to,  despite, For example, Compared with, other results, thus,  therefore……用好连接词能使文章层次清楚，意思明确。比如，叙述有时间顺序的事件或文献，最早的文献可用AA advocated it  for the first time.接下来可用Then BB further demonstrated that.  再接下来，可用Afterwards, CC……如果还有，可用More recent studies by DD……

* **Abstract**

  * A basic problem in the design of xx is presented by the choice of a xx rate for the measurement of experimental variables.
  * This paper examines a new measure of xx in xx based on fuzzy  mathematics which overcomes the difficulties found in other xx measures.
  * This paper describes a system for the analysis of the xx.
  * The method involves the construction of xx from fuzzy relations.
  * The procedure is useful in analyzing how groups reach a decision.
  * The technique used is to employ a newly developed and versatile xx algorithm.
  * The usefulness of xx is also considered.
  * A brief methodology used in xx is discussed.
  * The analysis is useful in xx and xx problem.
  * A model is developed for a xx analysis using fuzzy matrices.
  * Algorithms to combine these estimates and produce a xx are presented and justified.
  * The use of the method is discussed and an example is given.
  * Results of an experimental applications of this xx analysis procedure are given to illustrate the proposed technique.
  * This paper analyses problems in
  * This paper outlines the functions carried out by …
  * This paper includes an illustration of the …
  * This paper provides an overview and information useful for approaching
  * Emphasis is placed on the construction of a criterion function by  which the xx in achieving a hierarchical system of objectives are  evaluated.
  * The main emphasis is placed on the problem of xx
  * Our proposed model is verified through experimental study.
  * The experimental results reveal interesting examples of fuzzy phases of: xx, xx
  * The compatibility of a project in terms of cost, and xx are likewise represented by linguistic variables.
  * A didactic example is included to illustrate the computational procedure

* **Beginning**

  * In this paper, we focus on the need for
  * This paper proceeds as follow.
  * The structure of the paper is as follows.
  * In this paper, we shall first briefly introduce fuzzy sets and related concepts
  * To begin with we will provide a brief background on the

* **Introduction**

  * This will be followed by a description of the fuzzy nature of the  problem and a detailed presentation of how the required membership  functions are defined.
  * Details on xx and xx are discussed in later sections.
  * In the next section, after a statement of the basic problem, various  situations involving possibility knowledge are investigated: first, an  entirely possibility model is proposed; then the cases of a fuzzy  service time with stochastic arrivals and non fuzzy service rule is  studied; lastly, fuzzy service rule are considered.

* **Review**

  * This review is followed by an introduction.
  * A brief summary of some of the relevant concepts in xxx and xxx is presented in Section 2.
  * In the next section, a brief review of the …. is given.
  * In the next section, a short review of … is given with special regard to …
  * Section 2 reviews relevant research related to xx.
  * Section 1.1 briefly surveys the motivation for a methodology of action,  while 1.2 looks at the difficulties posed by the complexity of systems  and outlines the need for development of possibility methods.

* **Body**

  * Section 1 defines the notion of robustness, and argues for its importance.
  * Section 1 devoted to the basic aspects of the FLC decision making logic.
  * Section 2 gives the background of the problem which includes xxx
  * Section 2 discusses some problems with and approaches to, natural language understanding.
  * Section 2 explains how flexibility which often … can be expressed in terms of fuzzy time window
  * Section 3 discusses the aspects of fuzzy set theory that are used in the …
  * Section 3 describes the system itself in a general way, including the ….. and also discusses how to evaluate system performance.
  * Section 3 describes a new measure of xx.
  * Section 3 demonstrates the use of fuzzy possibility theory in the analysis of xx.
  * Section 3 is a fine description of fuzzy formulation of human decision.
  * Section 3, is developed to the modeling and processing of fuzzy decision rules
  * The main idea of the FLC is described in Section 3 while Section 4 describes the xx strategies.
  * Section 3 and 4 show experimental studies for verifying the proposed model.
  * Section 4 discusses a previous fuzzy set based approach to cost variance investigation.
  * Section 4 gives a specific example of xxx.
  * Section 4 is the experimental study to make a fuzzy model of memory process.
  * Section 4 contains a discussion of the implication of the results of Section 2 and 3.
  * Section 4 applies this fuzzy measure to the analysis of xx and illustrate its use on experimental data.
  * Section 5 presents the primary results of the paper: a fuzzy set model ..
  * Section 5 contains some conclusions plus some ideas for further work.
  * Section 6 illustrates the model with an example.
  * Various ways of justification and the reasons for their choice are discussed very briefly in Section 2.
  * In Section 2 are presented the block diagram expression of a whole model of human DM system
  * In Section 2 we shall list a collection of basic assumptions which a … scheme must satisfy.
  * In Section 2 of this paper, we present representation and uniqueness  theorems for the fundamental measurement of fuzziness when the domain of discourse is order dense.
  * In Section 3, we describe the preliminary results of an empirical study  currently in progress to verify the measurement model and to construct  membership functions.
  * In Section 5 is analyzed the inference process through the two kinds of inference experiments…

* **This Section**

  * In this section, the characteristics and environment under which MRP is designed are described.
  * We will provide in this section basic terminologies and notations which  are necessary for the understanding of subsequent results.Next Section
  * The next section describes the mathematics that goes into the computer implementation of such fuzzy logic statements.
  * However, it is cumbersome for this purpose and in practical  applications the formulae were rearranged and simplified as discussed in the next section.
  * The three components will be described in the next two section, and an example of xx analysis of a computer information system will then  illustrate their use.
  * We can interpret the results of Experiments I and II as in the following sections.
  * The next section summarizes the method in a from that is useful for arguments based on xx

* **Summary**

  * This paper concludes with a discussion of future research consideration in section 5.
  * Section 5 summarizes the results of this investigation.
  * Section 5 gives the conclusions and future directions of research.
  * Section 7 provides a summary and a discussion of some extensions of the paper.
  * Finally, conclusions and future work are summarized
  * The basic questions posed above are then discussed and conclusions are drawn.
  * Section 7 is the conclusion of the paper.

* **Time**

  * Over the course of the past 30 years, .. has emerged form intuitive
  * Technological revolutions have recently hit the industrial world
  * The advent of … systems for has had a significant impact on the
  * The development of … is explored
  * During the past decade, the theory of fuzzy sets has developed in a variety of directions
  * The concept of xx was investigated quite intensively in recent years
  * There has been a turning point in … methodology in accordance with the advent of …
  * A major concern in … today is to continue to improve…
  * A xx is a latecomer in the part representation arena.
  * At the time of this writing, there is still no standard way of xx
  * Although a lot of effort is being spent on improving these  weaknesses, the efficient and effective method has yet to be developed.
  * The pioneer work can be traced to xx [1965].
  * To date, none of the methods developed is perfect and all are far from ready to be used in commercial systems.

* **Objective / Goal / Purpose**

  * The purpose of the inference engine can be outlined as follows:
  * The ultimate goal of the xx system is to allow the non experts to  utilize the existing knowledge in the area of manual handling of loads,  and to provide intelligent, computer aided instruction for xxx.
  * The paper concerns the development of a xx
  * The scope of this research lies in
  * The main theme of the paper is the application of rule based decision making.
  *  These objectives are to be met with such thoroughness and confidence as to permit …
  * The objectives of the … operations study are as follows:
  * The primary purpose/consideration/objective of
  * The ultimate goal of this concept is to provide
  * The main objective of such a … system is to
  * The aim of this paper is to provide methods to construct such probability distribution.
  * In order to achieve these objectives, an xx must meet the following requirements:
  * In order to take advantage of their similarity
  * more research is still required before final goal of … can be completed
  * In this trial, the objective is to generate…
  * for the sake of concentrating on … research issues
  * A major goal of this report is to extend the utilization of a recently developed procedure for the xx.
  * For an illustrative purpose, four well known OR problems are studied in presence of fuzzy data: xx.
  * A major thrust of the paper is to discuss approaches and strategies for structuring ..methods
  * This illustration points out the need to specify
  * The ultimate goal is both descriptive and prescriptive.
  * A wealth of information is to be found in the statistics literature, for example, regarding xx
  * A considerable amount of research has been done .. during the last decade
  * A great number of studies report on the treatment of uncertainties associated with xx.
  * There is considerable amount of literature on planning
  * However, these studies do not provide much attention to uncertainty in xx.
  * Since then, the subject has been extensively explored and it is still under investigation as well in methodological aspects as in concrete applications.
  * Many research studies have been carried out on this topic.
  * Problem of xx draws recently more and more attention of system analysis.
  * Attempts to resolve this dilemma have resulted in the development of
  * Many complex processes unfortunately, do not yield to this design procedure and have, therefore, not yet been automated.
  * Most of the methods developed so far are deterministic and /or probabilistic in nature.
  * The central issue in all these studies is to
  * The problem of xx has been studied by other investigators,  however, these studies have been based upon classical statistical  approaches.
  * Applied … techniques to
  * Characterized the … system as
  * Developed an algorithm to
  * Developed a system called … which
  * Uses an iterative algorithm to deduce
  * Emphasized the need to
  * Identifies six key issues surrounding high technology
  * A comprehensive study of the… has been undertaken
  * Much work has been reported recently in these filed
  * Proposed / Presented / State that / Described / Illustrated / Indicated / Has shown / showed / Address / Highlights
  * Point out that the problem of
  * A study on …was done / developed by []
  * Previous work, such as [] and [], deal only with
  * The approach taken by [] is
  * The system developed by [] consists
  * A paper relevant to this research was published by []
  * []’s model requires consideration of…
  * []’ model draws attention to evolution in human development
  * []’s model focuses on…
  * Little research has been conducted in applying … to
  * The published information that is relevant to this research…
  * This study further shows that
  * Their work is based on the principle of
  * More history of … can be found in xx et al. [1979].
  * Studies have been completed to established
  * The …studies indicated that
  * Though application of xx in the filed of xx has proliferated in  recent years, effort in analyzing xx, especially xx, is lacking.

* Problem / Issue / Question

  * Unfortunately, real-world engineering problems such as  manufacturing planning do not fit well with this narrowly defined model. They tend to span broad activities and require consideration of  multiple aspects.
  * Remedy / solve / alleviate these problems
  * … is a difficult problem, yet to be adequately resolved
  * Two major problems have yet to be addressed
  * An unanswered question
  * This problem in essence involves using x to obtain a solution.
  * An additional research issue to be tackled is ….
  * Some important issues in developing a … system are discussed
  * The three prime issues can be summarized:
  * The situation leads to the problem of how to determine the …
  * There have been many attempts to
  * It is expected to be serious barrier to
  * It offers a simple solution in a limited domain for a complex

  以上内容参考https://blog.csdn.net/qq_29796317/article/details/73658038

* http://www.phrasebank.manchester.ac.uk/