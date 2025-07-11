---
title: bayes’ rule
draft: false
tags:
  - philosophy
  - logic
  - rationality
first published: 2025-07-08
last updated:
---
Bayes’ rule governs how to revise your probabilistic beliefs when you learn new things.
It’s about updating your beliefs when new information is discovered.

”Bayes’ theorem converts the results from your test into the real probability of the event” - [better explained](http://betterexplained.com/articles/an-intuitive-and-short-explanation-of-bayes-theorem/)

## Odds Form
A from of Bayes’ rule thinking in relative odds. 
An excerpt from LessWrong sums this up nicely: “Suppose we’re trying to solve a mysterious murder, and we start out thinking the odds of Prof. Plum vs. Miss Scarlet committing the murder are 1:2, that is, Scarlet is twice as likely as Plum to have committed the murder. We then observe that the victim was bludgeoned with a lead pipe, and that Scarlet, if she commits a murder, would be around 6% likely to use a lead pipe, this implies [[relative likelihoods]] of 10:1 for Plum vs. Scarlet using the pipe.

The [[posterior probability]] after observing the victim to have been murdered by a pipe are (1:2) X (10:1) = (10:2) = (5:1). Now we think Plum is around 5x as likely as Scarlet to have committed the murder.

## Proportional Form
Similar to odds form but just using fractions. If we think Plum is 2x as likely to have committed the murder as Scarlet, but then we discover the victim was poisoned, and Plum is 1/4 as likely to use poison as Scarlet. Then our Bayesian update would look like this: 2 x 1/4 =1/2.
Plum is around half as likely to have committed the murder as Scarlet.

## Implications
- Update by inches
- Belief revision as probability elimination: update your beliefs by throwing away large chunks of probability mass. 
- Shift towards the hypothesis of least surprise