---
layout: meeting
title: Workshop on Probabilistic Numerics
event: Neural Information Processing Systems (NeurIPS)
location: Lake Tahoe, NV, United States
date: 2012-12-03
date_end: 2012-12-08

link: https://nips.cc/Conferences/2012

organizers: [["Philipp", "Hennig"], ["John P.", "Cunningham"], ["Michael", "Osborne"]]

summary: The first international workshop on probabilistic numerics took place on Saturday, 8 December 2012 at Lake Tahoe, Nevada, in co-location with Neural Information Processing Systems.

url_code:
url_pdf:
url_slides:
url_video:
---

## Overview

The traditional remit of machine learning is problems of inference on complex data. At the computational bottlenecks of our algorithms, we typically find a numerical problem: optimization, integration, sampling. These inner routines are often treated as a black box, but many of these tasks in numerics can be viewed as learning problems:

- How can optimizers learn about the objective function, and how should they update their search direction? [^1]
- How should a quadrature method estimate an integral given observations of the integrand, and where should these methods put their evaluation nodes? [^2][^3][^4]
- How should MCMC samplers adapt their proposal distributions given past evaluations of the unnormalised density? [^5]
- Can approximate inference techniques be applied to numerical problems? [^6]?

Many of these problems can be seen as special cases of decision theory, active learning, or reinforcement learning. Work along these lines was pioneered twenty years ago by Diaconis [^7] and O'Hagan [^2]. But modern desiderata for a numerical algorithm differ markedly from those common elsewhere in machine learning: Numerical methods are "inner-loop" algorithms, used as black boxes by large groups of users on wildly different problems. As such, robustness, computation and memory costs are more important here than raw prediction power or convergence speed. Availability of good implementations also matters. These kind of challenges can be well addressed by machine learning researchers, once the relevant community is brought together to discuss these topics.

Some of the algorithms we use for numerical problems were developed generations ago. They have aged well, showing impressively good performance over a broad spectrum of problems. Of course, they also have a variety of shortcomings, which can be addressed by modern probabilistic models (see some of the work cited above). In the other direction, the numerical mathematics community, a much wider field than machine learning, is bringing experience, theoretical rigour and a focus on computational performance to the table. So there is great potential for cross-fertilization to both the machine learning and numerical mathematics community. The main goals of this workshop are

- to bring numerical mathematicians and machine learning researchers into contact to discuss possible contributions of machine learning to numerical methods.
- to present recent developments in probabilistic numerical methods.
- to discuss future directions, performance measures, test problems, and code publishing standards for this young community.

[^1]: D.R. Jones, M. Schonlau, and W.J. Welch. Efficient global optimization of expensive black-box functions. Journal of Global Optimization, 13 (4): 455--492, 1998.
[^2]: Anthony O'Hagan. Some Bayesian Numerical Analysis. Bayesian Statistics, volume 4, pp. 345--363, 1992.
[^3]: C.E. Rasmussen and Z. Ghahramani. Bayesian Monte Carlo. In Advances in Neural Information Processing Systems, volume 15, pp. 489--496, 2003.
[^4]: T. P. Minka. Deriving quadrature rules from Gaussian processes. Technical report, Statistics Department, Carnegie Mellon University, 2000.
[^5]: H. Haario, E. Saksman, and J. Tamminen. An Adaptive Metropolis Algorithm. Bernoulli, volume 7, number 2, pp. 223--242, 2001.
[^6]: J.P. Cunningham, P. Hennig, and S. Lacoste-Julien. Gaussian probabilities and expectation propagation. arXiv:1111.6832 [stat.ML], November 2011.
[^7]: Bayesian numerical analysis. In S. Gupta J. Berger, editors, Statistical Decision Theory and Related Topics IV, volume 1, pages 163--175. Springer-Verlag, New York, 1988.


## Schedule

The workshop will consist of invited talks, a poster session and a panel discussion.

<hr>
<table>
	<tr><td width="50">07:30</td><td width="700">Introduction by
	  the Organizers</td></tr>
	<tr><td width="50">07:40</td><td width="700">Invited Talk:
	<a href="http://lapmal.epfl.ch/"> Matthias
       Seeger</a></td></tr>
	<tr><td width="50">08:10</td><td width="700">Invited Talk:
	  <a href="http://www.maths.ed.ac.uk/~gondzio/">Jacek Gondzio
       </a></td></tr>
	<tr><td width="50">08:50</td><td width="700">Coffee Break</td></tr>
	<tr><td width="50">09:30</td><td width="700">Talk by <a href="http://mlg.eng.cam.ac.uk/duvenaud/">David
	Duvenaud</a></td></tr>
	<tr><td width="50">10:00</td><td width="700">Spotlights of
	Poster Presentations</td></tr>
	<tr><td width="50">10:10</td><td width="700">Poster Session and
	Open Discussion</td></tr>
	<tr><td width="50">10:30</td><td width="700">End of Morning
	Session</td></tr>
</table>
<hr>
<table>
	<tr><td width="50">16:00</td><td width="700">Invited Talk:
	<a href="http://www-stat.stanford.edu/~cgates/PERSI/">Persi
       Diaconis</a></td></tr>
	<tr><td width="50">16:45</td><td width="700">Invited Talk:
	<a href="http://www.ucl.ac.uk/statistics/people/bencalderhead">Ben
       Calderhead</a></td></tr>
	<tr><td width="50">17:15</td><td width="700">Coffee Break
	</td></tr>
	<tr><td width="50">18:00</td><td width="700">Talk by <a href="http://www.is.tuebingen.mpg.de/nc/employee/details/phennig.html#=0">Philipp Hennig</a>
	</td></tr>
	<tr><td width="50">18:30</td><td width="700">Panel Discussion
	and Concluding Remarks, hosted by <a href="http://cunningham.wustl.edu">John Cunningham</a>
	</td></tr>
	<tr><td width="50">19:00</td><td width="700">Workshop Ends
	</td></tr>
</table>
<hr>
