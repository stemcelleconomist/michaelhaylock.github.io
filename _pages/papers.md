---
title: 
layout: single
classes: wide
permalink: /research/
---
<br/> 


# <center> Working Papers </center>
- - -

**An Honest Approach to Parallel Trends**. 2020. (With Ashesh Rambachan) <br/>
<small>[ <a href="#" onclick="visib('polariz')">Abstract</a> | [Draft][1] ] </small>

<div id="polariz" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper proposes robust inference methods for difference-in-differences and event-study designs that do not require that the parallel trends assumption holds exactly. Instead, the researcher must only impose restrictions on the possible differences in trends between the treated and control groups. Several common intuitions expressed in applied work can be captured by such restrictions, including the notion that pre-treatment differences in trends are informative about counterfactual post-treatment differences in trends. Our methodology then guarantees uniformly valid ("honest'') inference when the imposed restrictions are satisfied. We first show that fixed length confidence intervals have near-optimal expected length for a practically-relevant class of restrictions. We next introduce a novel inference procedure that accommodates a wider range of restrictions, which is based on the observation that inference in our setting is equivalent to testing a system of moment inequalities with a large number of linear nuisance parameters. The resulting confidence sets are consistent, and have optimal local asymptotic power for many parameter configurations. We recommend researchers conduct sensitivity analyses to show what conclusions can be drawn under various restrictions on the possible differences in trends. 
</small><br><br/></div>

[1]: {{ site.baseurl }}{% link assets/files/Martinez_DynPol.pdf %}



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
