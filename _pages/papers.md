---
title: 
layout: single
classes: wide
permalink: /papers/
---
<br/> 

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PNS829G"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

# <center> Working Papers </center>
- - -

**Pre-test with Caution: Event-study Estimates After Testing for Parallel Trends**. 2021. *Conditionally accepted, American Economic Review: Insights*
<br/>
<small>[ <a href="#/" onclick="visib('pretest')">Abstract</a> | [Draft][pretest-draft] | [R package][pretrends-package] | [Shiny app][pretrends-shiny] | [Longer Version (old)][pretest-draft-longer]] </small>

<div id="pretest" style="display: none; text-align: justify; line-height: 1.2" ><small>
Tests for pre-existing trends ("pre-trends") are a common way of assessing the plausibility of the parallel trends assumption in difference-in-differences and related research designs. This paper highlights some important limitations of pre-trends testing. From a theoretical perspective, I analyze the distribution of conventional estimates and confidence intervals conditional on surviving a pre-test for pre-trends. I show that in non-pathological cases, the bias of conventional estimates conditional on passing a pre-test can be worse than the unconditional bias. Thus, pre-tests meant to mitigate bias and coverage issues in published work can in fact exacerbate them. I empirically investigate the practical relevance of these concerns in simulations based on a systematic review of recent papers in leading economics journals. I find that conventional pre-tests are often underpowered against plausible violations of parallel trends that produce bias of a similar magnitude as the estimated treatment effect. Distortions from pre-testing can also be substantial. Finally, I discuss alternative approaches that can improve upon the standard practice of relying on pre-trends testing.
</small><br><br/></div>

[pretest-draft]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing.pdf %}
[pretest-draft-longer]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing_longer_version.pdf %}
[pretrends-package]:https://github.com/jonathandroth/pretrends#pretrends
[pretrends-shiny]:https://github.com/jonathandroth/PretrendsPower#pretrendspower



**Efficient Estimation for Staggered Rollout Designs** (with Pedro Sant'Anna). 2021.<br/>
<small>[ <a href="#/" onclick="visib('staggeredefficient')">Abstract</a> | [Draft][staggeredefficient-arxiv] | [R package][staggeredefficient-package] | [Stata package][staggeredefficient-stata-package] ]</small>

<div id="staggeredefficient" style="display: none; text-align: justify; line-height: 1.2" ><small>
Researchers are often interested in the causal effect of treatments that are rolled out to different units at different points in time. This paper studies how to efficiently estimate a variety of causal parameters in such staggered rollout designs when treatment timing is (as-if) randomly assigned. We solve for the most efficient estimator in a class of estimators that nests two-way fixed effects models as well as several popular generalized difference-in-differences methods. The efficient estimator is not feasible in practice because it requires knowledge of the optimal weights to be placed on pre-treatment outcomes. However, the optimal weights can be estimated from the data, and in large datasets the plug-in estimator that uses the estimated weights has similar properties to the "oracle" efficient estimator. We illustrate the performance of the plug-in efficient estimator in simulations and in an application to Wood et al. (2020a)'s study of the staggered rollout of a procedural justice training program for police officers. We find that confidence intervals based on the plug-in efficient estimator have good coverage and can be as much as five times shorter than confidence intervals based on existing methods. As an empirical contribution of independent interest, our application provides the most precise estimates to date on the effectiveness of procedural justice training programs for police officers.
</small><br><br/></div>

[staggeredefficient-arxiv]: https://arxiv.org/pdf/2102.01291.pdf
[staggeredefficient-package]: https://github.com/jonathandroth/staggered
[staggeredefficient-stata-package]: https://github.com/jonathandroth/staggered_stata

**When Is Parallel Trends Sensitive to Functional Form?** (with Pedro Sant'Anna). 2021.
*Revision requested, Econometrica*
<br/>
<small>[ <a href="#/" onclick="visib('ptinvariance')">Abstract</a> | [Draft][pt-arxiv] ] </small>

<div id="ptinvariance" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper assesses when the validity of difference-in-differences and related estimators depends on functional form. We provide a novel characterization: the parallel trends assumption holds under all strictly monotonic transformations of the outcome if and only if a stronger ''parallel trends''-type condition holds for the cumulative distribution function of untreated potential outcomes. This condition is satisfied if and essentially only if the population can be partitioned into a subgroup for which treatment is effectively randomly assigned and a remaining subgroup for which the distribution of untreated potential outcomes is stable over time. We show further that it is impossible to construct any estimator that is consistent (or unbiased) for the average treatment effect on the treated (ATT) without either imposing functional form restrictions or imposing assumptions that identify the full distribution of untreated potential outcomes. Our results suggest that researchers who wish to point-identify the ATT should justify one of the following: (i) why treatment is as if randomly assigned, (ii) why the chosen functional form is correct at the exclusion of others, or (iii) a method for inferring the entire counterfactual distribution of untreated potential outcomes.
</small><br><br/></div>

[pt-arxiv]:{{ site.baseurl }}{% link assets/files/2010.04814.pdf %}


**Why Do Sectoral Employment Programs Work? Evidence from WorkAdvance** (with Lawrence F. Katz, Richard Hendra, and Kelsey Schaberg). 2020. *Revision requested, Journal of Labor Economics*
<br/>
<small>[ <a href="#/" onclick="visib('workadvance')">Abstract</a> | [Draft][workadvance-draft] ] </small>

<div id="workadvance" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper examines the evidence from randomized evaluations of sector-focused training programs that target low-wage workers and combine upfront screening, occupational and soft skills training, and wraparound services. The programs generate substantial and persistent earnings gains (11 to 40 percent) following training completion. Theoretical mechanisms for program impacts are explored for the WorkAdvance demonstration. Earnings gains are generated by getting participants into higher-wage jobs in higher-earning industries and occupations not just by raising employment. Training in transferable and certifiable skills (likely under-provided from poaching concerns) and reductions of employment barriers to high-wage sectors for non-traditional workers appear to play key roles.
</small><br><br/></div>

[workadvance-draft]:{{ site.baseurl }}{% link assets/files/workadvance-nber-wp.pdf %}



**An Honest Approach to Parallel Trends** (with Ashesh Rambachan). 2020.<br/>
<small>[ <a href="#/" onclick="visib('hpt')">Abstract</a> | [Draft][1] | [JMP Version (old)][3] | [R package][hpt-package] ] </small>

<div id="hpt" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper proposes tools for robust inference for difference-in-differences and event-study designs. Instead of requiring that the parallel trends assumption holds exactly, we impose that pre-treatment violations of parallel trends (''pre-trends'') are informative about the possible post-treatment violations of parallel trends. Such restrictions allow us to formalize the intuition behind the common practice of testing for pre-existing trends while avoiding issues related to pre-testing. The causal effect of interest is partially identified under such restrictions. We introduce two approaches that guarantee uniformly valid (''honest'') inference under the imposed restrictions, and we derive novel results showing that they have good power properties in our context. We recommend that researchers conduct sensitivity analyses to show what conclusions can be drawn under various restrictions on the possible differences in trends.
</small><br><br/></div>

[1]: {{ site.baseurl }}{% link assets/files/HonestParallelTrends_Main.pdf %}
[2]: {{ site.baseurl }}{% link assets/files/HonestParallelTrends_Supp.pdf %}
[3]: {{ site.baseurl }}{% link assets/files/roth_jmp_honestparalleltrends_main_jmp_version.pdf %}
[hpt-package]: https://github.com/asheshrambachan/HonestDiD

**Design-Based Uncertainty for Quasi-Experiments** (with Ashesh Rambachan). 2020.<br/>
<small>[ <a href="#/" onclick="visib('design-based')">Abstract</a> | [Draft][design-based-arxiv] ] </small>

<div id="design-based" style="display: none; text-align: justify; line-height: 1.2" ><small>
Social scientists are often interested in estimating causal effects in settings where all units in the population are observed (e.g. all 50 US states). Design-based approaches, which view the realization of treatment assignments as the source of randomness, may be more appealing than standard sampling-based approaches in such contexts. This paper develops a design-based theory of uncertainty suitable for quasi-experimental settings, in which the researcher estimates the treatment effect as if treatment were randomly assigned, but in reality treatment probabilities may depend in unknown ways on the potential outcomes. We first study the properties of the simple difference-in-means (SDIM) estimator. The SDIM is unbiased for a finite-population design-based analog to the average treatment effect on the treated (ATT) if treatment probabilities are uncorrelated with the potential outcomes in a finite population sense. We further derive expressions for the variance of the SDIM estimator and a central limit theorem under sequences of finite populations with growing sample size. We then show how our results can be applied to analyze the distribution and estimand of difference-in-differences (DiD) and two-stage least squares (2SLS) from a design-based perspective when treatment is not completely randomly assigned.
</small><br><br/></div>

[design-based-arxiv]: https://arxiv.org/pdf/2008.00602v2.pdf




**Inference for Linear Conditional Moment Inequalities** (with Isaiah Andrews and Ariel Pakes). 2019.
*Revision requested, Review of Economic Studies*
<br/>
<small>[ <a href="#/" onclick="visib('arp')">Abstract</a> | [Draft][arp-draft] | [Supplement][arp-supp] ] </small>

<div id="arp" style="display: none; text-align: justify; line-height: 1.2" ><small>
We consider inference based on linear conditional moment inequalities, which arise in a wide variety of economic applications, including many structural models.  We show that linear conditional structure greatly simplifies confidence set construction, allowing for computationally tractable projection inference in settings with nuisance parameters.  Next, we derive least favorable critical values that avoid conservativeness due to projection.  Finally, we introduce a conditional inference approach which ensures a strong form of insensitivity to slack moments, as well as a hybrid technique which combines the least favorable and conditional methods.  Our conditional and hybrid approaches are new even in settings without nuisance parameters.  We find good performance in simulations based on Wollmann (2018), especially for the hybrid approach.
</small><br><br/></div>

[arp-draft]:{{ site.baseurl }}{% link assets/files/arp-draft.pdf %}
[arp-supp]:{{ site.baseurl }}{% link assets/files/arp-supp.pdf %}




**Union Reform and Teacher Turnover: Evidence from Wisconsin's Act 10**. 2019.
<br/>
<small>[ <a href="#/" onclick="visib('act10')">Abstract</a> | [Draft][act10-draft] ] </small>

<div id="act10" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper studies teacher attrition in Wisconsin following Act 10, a policy change which severely weakened teachers’ unions and capped wage growth for teachers. I document a sharp short-run increase in teacher turnover after the Act was passed, driven almost entirely by teachers over the minimum retirement age of 55, whose turnover rate doubled from 17 to 35 percent. Such teachers faced strong incentives to retire before the end of pre-existing collective bargaining agreements in order to secure collectively-bargained retirement benefits (e.g. healthcare), which no longer fell under the scope of collective bargaining after the Act. I find much more modest long-run increases in teacher turnover, consistent with previous estimates of labor supply elasticities. I then attempt to evaluate the effect of the wave of retirements following Act 10 on education quality using grade-level value-added metrics. I find suggestive evidence that student academic performance increased in grades with teachers who retired following the reform, and I obtain similar results when instrumenting for retirement using the pre-existing age distribution of teachers. Differences in value-added between retirees and their replacements can potentially explain some, but not all, of the observed academic improvements.
</small><br><br/></div>

[act10-draft]:{{ site.baseurl }}{% link assets/files/roth_act10.pdf %}


# <center> Published Papers </center>
- - -

**Bias In, Bias Out? Evaluating the Folk Wisdom** (with Ashesh Rambachan). 2020. 1st Symposium on the Foundations of Responsible Computing (FORC 2020), LIPIcs, 156, Pp. 6:1-6:15.
<br/>
<small>[ <a href="#/" onclick="visib('biasinbiasout')">Abstract</a> | [Paper][biasinbiasout-draft] ] </small>

<div id="biasinbiasout" style="display: none; text-align: justify; line-height: 1.2" ><small>
We evaluate the folk wisdom that algorithmic decision rules trained on data produced by biased human decision-makers necessarily reflect this bias. We consider a setting where training labels are only generated if a biased decision-maker takes a particular action, and so "biased" training data arise due to discriminatory selection into the training data. In our baseline model, the more biased the decision-maker is against a group, the more the algorithmic decision rule favors that group. We refer to this phenomenon as bias reversal. We then clarify the conditions that give rise to bias reversal. Whether a prediction algorithm reverses or inherits bias depends critically on how the decision-maker affects the training data as well as the label used in training. We illustrate our main theoretical results in a simulation study applied to the New York City Stop, Question and Frisk dataset.
</small><br><br/></div>

[biasinbiasout-draft]:https://drops.dagstuhl.de/opus/volltexte/2020/12022/pdf/LIPIcs-FORC-2020-6.pdf


# <center> Comments </center>
- - -
**Comments and Revised Findings for "Procedural justice training reduces police use of force and complaints against officers"** (with Pedro Sant'Anna, George Wood, Andrew Papachristos, and Tom Tyler). 2020.
<br/>
<small>[ <a href="#/" onclick="visib('woodetal')">Abstract</a> | [Initial Letter][woodetal-letter] | [Reanalysis][woodetal-reanalysis] ] </small>

<div id="woodetal" style="display: none; text-align: justify; line-height: 1.2" ><small>
Pedro Sant'Anna and I discovered a statistical error in a recent PNAS paper by Wood, Papachristos, and Tyler that led to spuriously large estimates of the effect of a procedural justice training for police officers. Below are links to our initial letter to the authors detailing the problem and to a re-analysis co-authored with the original authors that corrects the statistical error.
</small><br><br/></div>

[woodetal-letter]:{{ site.baseurl }}{% link assets/files/Wood-et-al-comment-20200714.pdf %}
[woodetal-reanalysis]:{{ site.baseurl }}{% link assets/files/wood-et-al-revisited.pdf %}


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
