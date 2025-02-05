---
title: "Guidelines and recommendations"
linkTitle: "Guidelines"
weight: 7
description: >
  Some guidelines and recommendations on testing from the Selenium project.
aliases: ["/documentation/nl/guidelines_and_recommendations/"]  
---

{{% pageinfo color="warning" %}}
<p class="lead">
   <i class="fas fa-language display-4"></i> 
   Page being translated from 
   English to Dutch. Do you speak Dutch? Help us to translate
   it by sending us pull requests!
</p>
{{% /pageinfo %}}

A note on "Best Practices": We've intentionally avoided the phrase "Best
Practices" in this documentation. No one approach works for all situations.
We prefer the idea of "Guidelines and Recommendations". We encourage
you to read through these and thoughtfully decide what approaches
will work for you in your particular environment.

Functional testing is difficult to get right for many reasons.
As if application state, complexity, and dependencies do not make testing difficult enough,
dealing with browsers (especially with cross-browser incompatibilities)
makes writing good tests a challenge.

Selenium provides tools to make functional user interaction easier,
but does not help you write well-architected test suites.
In this chapter we offer advice, guidelines, and recommendations
on how to approach functional web page automation.

This chapter records software design patterns popular
amongst many of the users of Selenium
that have proven successful over the years.
