---
layout: meeting

title: Integrating Inference with Integration
event: MCMSki
location: Conference Center Lenzerheide, Switzerland
organizers: [["Michael", "Osborne"], ["Chris", "Oates"], ["François-Xavier", "Briol"]]

date: 2016-01-04
date_end: 2016-01-07

summary: 

link: http://www.pages.drexel.edu/~mwl25/mcmskiV/index.html
img: /assets/img/meetings/2016_MCMSki.jpg
img_caption: Lenzerheide by Adrian Michael (CC-BY-3.0)

url_code:
url_pdf:
url_slides:
url_video:
---

This session will be hosted by [MCMSki](http://www.pages.drexel.edu/~mwl25/mcmskiV/index.html), the joint  meeting of the [Institute of Mathematical Statistics](http://www.imstat.org/) and the [International Society for Bayesian Analysis](http://www.bayesian.org/).

## Schedule

The workshop will be held on Thursday, 7th January 2016; the room will be the Activityraum.

* 09:40-10:10: [Simo Särkkä](http://users.aalto.fi/~ssarkka)
* 10:10-10:40: [François-Xavier Briol](http://www2.warwick.ac.uk/fac/sci/statistics/staff/research_students/briol/)
* 10:40-11:10: [Roman Garnett](http://cse.wustl.edu/people/Pages/faculty-bio.aspx?faculty=109)

## Session Theme

Numerical algorithms, such as methods for the numerical solution of integrals, as well as optimization algorithms, can be interpreted as estimation rules. They estimate the value of a latent, intractable quantity – the value of an integral, the solution of a differential equation, the location of an extremum – given the result of tractable computations (“observations”, such as function values of the integrand, evaluations of the differential equation, function values of the gradient of an objective). So these methods perform inference, and are accessible to the formal frameworks of probability theory. They are learning machines.

Taking this observation seriously, a probabilistic numerical method is a numerical algorithm that takes in a probability distribution over its inputs, and returns a probability distribution over its output. Recent research shows that it is in fact possible to directly identify existing numerical methods, including some real classics, with specific probabilistic models.

Interpreting numerical methods as learning algorithms offers various benefits. It can offer insight into the algebraic assumptions inherent in existing methods. As a joint framework for methods developed in separate communities, it allows transfer of knowledge among these areas. But the probabilistic formulation also explicitly provides a richer output than simple convergence bounds. If the probability measure returned by a probabilistic method is well-calibrated, it can be used to monitor, propagate and control the quality of computations.
