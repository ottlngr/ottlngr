+++
title = "Being a package maintainer or: The social contract"
date = "2019-05-24"
author = "Philipp Ottolinger"
description = ""
+++

I am a \(R) package maintainer. 

A rational description of that circumstance could be: I'm the one who submitted a package to CRAN and it is my e-mail address which is listed in the `DESCRIPTION` file.

A hysteric description of that circumstance could be: OMG, did I really submit a package to CRAN, and so, to the entire world? The rest of my life, I gotta keep that shit running!

After `bib2df`, definitely the one of my packages with the greatest impact, got removed from CRAN for the second time within a few months, my perception of being a package maintainer clearly approached to the second possible description.

A bit of an assessment:

I slid into the R world around 2013-2014, reaching a high in 2015 and 2016, when I really tried to soak in everything that happended with and around R. I tried to read as many blogs as possible, I tried to become a member of the #rstats 'core' on Twitter and I was sitting in front of RStudio several evenings a week. Around that time, also `bib2df` originated. The main reason why my relationship to R and the eco- as well as the social system around it changed so dramatically, is the simple fact that I do not have that much time anymore for random hacking and hours in front of the #rstats hashtag. Or more precisely: I do not take so much time to do so anymore. 

Since I finished my M.Sc. and started into the working life in autumn 2016, my perception of free time changed, which is probably no surprise, and does precisely not include the whole R thing. The decline of time I spent with R gets increased by the fact that meanwhile R does hardly play a role at my work: In Summer 2017 the focus of my work shifted from data analysis and visualization to data engineering and programming, almost entirely with Python and SQL.

While this seems to be is a decision, whether or not she or he wants to keep spending a significant amount of time with R (or any other hobby/community), every one has to make on his own at first sight, it is not at a second sight, at least when you're a package maintainer (or play any comparable role in any kind of community).

The fact that `bib2df`, a peer-reviewed and rOpenSci approved package, got removed from CRAN for already two times in 2019, is not a sign of playing that role with sufficient responsibility.

When maintaining a package, you have quite a long list of stakeholders with individual demands:

* Users of your package want
  * a package that works and doesn't break existing code
  * a package that can be installed from CRAN at any time (partly also to not break existing code)

* CRAN as a platform
  * has its policy you as a maintainer have to comply to
  * does not want to have corrupt packages in its portfolio (that is why packages get checked regularly)

* Organizations, like rOpenSci
  * may have peer-reviewed your package and therefore assume a certain package quality
  * some kind of promote/feature your package by making it a bit more 'official'

Probably this list could be extended, but imaginary drawing that list up a few days ago, after receiving mails from CRAN because of failing checks, after receiving tweets asking for the package and after receiving issues on GitHub faulting the unavailability on CRAN without a immediate feel of responsibility, really brought me to my senses.
 
Maybe this interpretation of being a package maintainer seems a bit strict and overly demanding, but: I guess it would not be that difficult to hand off your packages to someone, if you really believe you can not put up the necessary time to satisfy your stakeholders anymore. 

But I wouldn't. Receiving three tweets a year declaring the joy the authors had using `bib2df` is a fair compensation for an average of 10 minutes a week it takes to fulfil the 'social contract' I signed. At least for me.
