---
layout: page
permalink: /readinggroup/
title: Reading Group
description:
nav: true
nav_order: 2
---

<p style="margin-bottom: 3mm">We are holding an online reading group focusing on <strong>modern adaptive experimental design and active learning in the real world</strong>. All interested participants are welcome to join!</p>
<p style="margin-bottom: 3mm">The reading group will be held on <strong>Thursdays</strong> at <strong>10am PST/California</strong>, <strong>6pm GMT/UK</strong>, <strong>7pm CET/Zurich</strong> time. To add this to your calendar, <a href="https://calendar.google.com/calendar/u/0?cid=Mzg1OTc3M2I0MmJjNDIyNGQxZjE2MDA0ZWQ3OGUzNzlhOGViNzdlM2JiMmQ1NmFlYmZkZTU5M2RkOTVhYTEwN0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t">click here</a>. To receive information via email, <a href="https://forms.gle/Ex1ut4YfL8E3qt7W6">subscribe to our mailing list</a>.</p>
<p style="margin-bottom: 7mm">To join, please use the following <strong>Zoom link:</strong> <a href="https://ethz.zoom.us/j/67585775251">https://ethz.zoom.us/j/67585775251</a> <img src="../assets/img/zoompass.png" alt="" width="25%"></p>

### Speaker Schedule

1. &nbsp;**January 12, 2023** &emsp;&nbsp;&nbsp;&nbsp; [Kelly W. Zhang](https://kellywzhang.github.io/)
    &emsp;&emsp;&emsp;&emsp;<img src="../assets/img/speaker-circles/kelly.png" alt="" width="7%">
2. &nbsp;**January 19, 2023** &emsp;&nbsp;&nbsp;&nbsp; [Kevin Jamieson](https://homes.cs.washington.edu/~jamieson/)
    &emsp;&emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/kevin_j.png" alt="" width="7%">
3. &nbsp;**January 26, 2023** &emsp;&nbsp;&nbsp;&nbsp; [Raul Astudillo](https://raulastudillo.netlify.app/)
    &emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/raul.png" alt="" width="7%">
4. &nbsp;**February 2, 2023** &emsp;&nbsp;&nbsp;&nbsp;&nbsp; [Emmanuel Bengio](https://folinoid.com/)
    &emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/emmanuel.png" alt="" width="7%">
5. &nbsp;**February 23, 2023** &emsp;&nbsp; [Haitham Bou Ammar](http://bouammar.com/)
    &emsp;&nbsp;<img src="../assets/img/speaker-circles/haitham.png" alt="" width="7%">
6. &nbsp;**March 2, 2023** &emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp; [Kevin Tran](https://ktran9891.github.io/)
    &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/kevin_t.png" alt="" width="7%">
7. &nbsp;**March 9, 2023** &emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp; [Zi Wang](https://ziw.mit.edu/)
    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;<img src="../assets/img/speaker-circles/zi.png" alt="" width="7%">
8. &nbsp;**March 16, 2023** &emsp;&emsp;&nbsp;&nbsp; [Viraj Mehta](https://virajm.com/)
    &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/viraj.png" alt="" width="7%">
9. &nbsp;**March 23, 2023** &emsp;&emsp;&nbsp;&nbsp; [Johannes Kirschner](https://johannes-kirschner.de/)
    &emsp;&ensp;&nbsp;<img src="../assets/img/speaker-circles/johannes.png" alt="" width="7%">

<div style="margin-bottom: 7mm;"></div>
### Next Talk
<div style="margin-bottom: 5mm;"></div>

<img src="../assets/img/speaker-circles/kevin_j.png" alt="" width="15%"> &emsp;
[Kevin Jamieson](https://homes.cs.washington.edu/~jamieson/), &nbsp; **January 19, 2023**

**Title:** Lessons learned in deploying bandit algorithms

**Abstract:** Bandit algorithms, and adaptive experimentation more generally, promise the same statistically significant guarantees as, say, non-adaptive A/B testing, but require far fewer trials which results in a savings in time and money. However, such promises hold only under assumptions that rarely hold in practice, and for algorithms that may require unrealistic data interaction patterns. This talk explores this tension through two case studies in deploying state of the art algorithms to a large online experimentation platform and a robotics application in an industrial setting. Problems will be discussed, sensible solutions will be proposed, and opinions will be offered.

**Relevant Papers:**
- [Instance-optimal PAC Algorithms for Contextual Bandits](https://arxiv.org/abs/2207.02357)
- [A Bandit Approach to Multiple Testing with False Discovery Control](https://arxiv.org/abs/1809.02235)

**Bio:** Kevin Jamieson is an Assistant Professor in the <a href="http://cs.washington.edu/">Paul G. Allen School of Computer Science & Engineering</a> at the University of Washington and is the Guestrin Endowed Professor in Artificial Intelligence and Machine Learning. He received his B.S. from the University of Washington, his M.S. from Columbia University, and his Ph.D. In 2015 from the University of Wisconsin - Madison under the advisement of <a href="http://nowak.ece.wisc.edu/">Robert Nowak</a>, all in electrical engineering. He returned to the University of Washington as faculty in 2017 after a postdoc in the <a href="https://amplab.cs.berkeley.edu/">AMP lab</a> at the University of California, Berkeley working with <a href="https://people.eecs.berkeley.edu/~brecht/">Benjamin Recht</a>. Jamieson's work has been recognized by an NSF CAREER award and Amazon Faculty Research award. Jamieson’s research explores how to leverage already-collected data to inform what future measurements to make next, in a closed loop.

<div style="margin-bottom: 7mm;"></div>
### Past Talks
<div style="margin-bottom: 5mm;"></div>

<img src="../assets/img/speaker-circles/kelly.png" alt="" width="15%"> &emsp;
[Kelly W. Zhang](https://kellywzhang.github.io/), &nbsp; **January 12, 2023**

**Title:** Inference after Adaptive Sampling for Longitudinal Data

**Abstract:** Online algorithms that learn to optimize treatments over time are increasingly used in a variety of digital intervention problems. These algorithms repeatedly update parameter estimates as data accrues; these parameter estimates are used to inform treatment decisions. These algorithms are called “adaptive sampling” algorithms and the resulting data is considered “adaptively collected.” In this work, we focus on data collected by a large class of adaptive sampling algorithms that are designed to optimize treatment decisions online using accruing data from multiple users. Combining or “pooling” data across users allows adaptive sampling algorithms to potentially learn faster. However, by pooling, these algorithms induce dependence between the collected user data trajectories; this makes statistical inference on this data-type especially challenging. We provide methods to perform a variety of statistical analyses on such adaptively collected data, including Z-estimation, off-policy analyses, and inferring excursion effects. This work is motivated by our work in designing experiments in which online reinforcement learning algorithms pool data across users to learn to optimize treatment decisions, yet reliable statistical inference is essential for conducting a variety of statistical analyses after the experiment is over.

**Bio:** Kelly W. Zhang is a final-year Ph.D. candidate in computer science at Harvard University advised by Susan Murphy and Lucas Janson. Her research focuses on addressing challenges faced when applying reinforcement learning algorithms to real-world problems. She has developed methods for statistical inference for data collected by bandit and reinforcement learning algorithms, i.e., adaptively collected data. She also works on developing the reinforcement learning algorithm to be used in Oralytics, a mobile health app aimed to help users develop healthy oral hygiene habits, in collaboration with Oral-B and researchers at UCLA and UMichigan. She is supported by an NSF Graduate Research Fellowship.



<!--1. &nbsp;**January 12, 2023** &emsp;&nbsp;&nbsp;&nbsp; [Kelly W. Zhang](https://kellywzhang.github.io/), Harvard University-->
<!--    &emsp;&emsp;&emsp;&emsp;<img src="../assets/img/speaker-circles/kelly.png" alt="" width="5%">-->
<!--2. &nbsp;**January 19, 2023** &emsp;&nbsp;&nbsp;&nbsp; [Kevin Jamieson](https://homes.cs.washington.edu/~jamieson/), University of Washington-->
<!--    &emsp;&emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/kevin_j.png" alt="" width="5%">-->
<!--3. &nbsp;**January 26, 2023** &emsp;&nbsp;&nbsp;&nbsp; [Raul Astudillo](https://raulastudillo.netlify.app/), Caltech-->
<!--    &emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/raul.png" alt="" width="5%">-->
<!--4. &nbsp;**February 2, 2023** &emsp;&nbsp;&nbsp;&nbsp;&nbsp; [Emmanuel Bengio](https://folinoid.com/), Recursion-->
<!--    &emsp;&emsp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/emmanuel.png" alt="" width="5%">-->
<!--5. &nbsp;**February 9, 2023** &emsp;&nbsp;&nbsp;&nbsp;&nbsp; [Zi Wang](https://ziw.mit.edu/), Google Brain-->
<!--    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;<img src="../assets/img/speaker-circles/zi.png" alt="" width="5%">-->
<!--6. &nbsp;**February 16, 2023** &emsp;&nbsp; [Johannes Kirschner](https://johannes-kirschner.de/), University of Alberta-->
<!--    &emsp;&ensp;&nbsp;<img src="../assets/img/speaker-circles/johannes.png" alt="" width="5%">-->
<!--7. &nbsp;**February 23, 2023** &emsp;&nbsp; [Haitham Bou Ammar](http://bouammar.com/), UCL and Huawei London-->
<!--    &emsp;&nbsp;<img src="../assets/img/speaker-circles/haitham.png" alt="" width="5%">-->
<!--8. &nbsp;**March 2, 2023** &emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp; [Kevin Tran](https://ktran9891.github.io/), Toyota Research Institute-->
<!--    &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;&nbsp;<img src="../assets/img/speaker-circles/kevin_t.png" alt="" width="5%">-->

<!--<br/>-->
<!--<img src="../assets/img/speaker-circles/kelly.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/kevin_j.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/raul.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/emmanuel.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/zi.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/johannes.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/haitham.png" alt="" width="10%"> &nbsp;-->
<!--<img src="../assets/img/speaker-circles/kevin_t.png" alt="" width="10%"> &nbsp;-->
