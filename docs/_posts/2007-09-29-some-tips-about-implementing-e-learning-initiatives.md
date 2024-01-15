---
title: "Some tips about implementing e-learning initiatives"
date: "2007-09-29"
categories: 
  - "education"
tags: 
  - "elearning"
  - "management"
---

Recently, I commented on this topic for someone, and that made me look around for some help, couldn't find any canned (and free!) listing of things to do/avoid during implementing e-learning initiatives in a developing country like India which has low bandwidth availability, large number of languages to be supported, and in general a low availability of e-learning case studies. Here is my attempt at a brief note to help such implementations (this is extremely brief!):

Here are some points to keep in mind at the outset of planning and implementation:

1. Depending on bandwidth, course content should be created so that it utilizes least amount of bandwidth, think about a caching server located at each site to cache the content which will improve response time. This is critical if there are multiple sites connected via VPN (and hence bandwith availability for e-learning can be quite less, and content launches typically consume large bandwith if not planned correctly).
2. The content you create (and LMS that you use) should be localized; sooner or later you will need it. Check the support of the tools you use (LMS, LCMS, content authoring tools), as well as make sure the content you create is either globalized or is created in a way where creating seperate version for a language manually is easy (think of pictures and animations without text for example).
3. Do you need to create content that requires multiple authors or single author is enough? That puts requirements on your content creation tools. Multi-author generated content requires collaboration across authors and you might need authoring environment that supports such scenarios. Single author is easy, but if your authors are truely distributed, it may not work out.
4. Especially for multi-site deployments, there are  two models to use
    1. All training and content is common, shared across all sites seamlessly and by default, without any control on hiding any content from any site. This is suitable for cases when e-learning initiative is to manage online training only and sites are only recepients of the training and not creators, and there is no notion of local training.
    2. Each site has its mini-LMS within the LMS, where some content (and other details) are local and some are shared explicitly by administrators of the site with other (some or all) sites. This allows most flexibility. For example: instructor led training are mostly local (because of costs involved in travel to attend them) but they can be tracked using the same system and remain hidden to other sites. LMS vendors call it domains or groups.
5. If you require online training delivered through instructors (virtual classroom, like WebEx, Microsoft Livemeeting), you should make sure such an option is available within your budget, and integrates well with your LMS. These integration can be tricky at times.
6. Make sure your content is standards-compliant, but more importantly, works with the LMS you have chosen. Self-created contents are painful to make them work with a given LMS vendor and care must be taken at the beginning to pick right standards and interoperable pieces.
7. If you outsource content creation (it is always a good idea to do so if you have significant amount to create since it is highly specialized activity), so it will be good to understand the technologies, process and subject matter expertise of those guys, as well as what LCMS they plan to use. Custom-created content and their working with LMS are  biggest painpoint in any e-learning initiative.

Here are some articles you may find useful to go through. These are from ASTD (Americal Society of Training and Development) learning site: [http://www.learningcircuits.org](http://www.learningcircuits.org/), this site is a great resource by the way.

Buy Versus Build: A Battle of Needs [http://www.learningcircuits.org/2002/jan2002/elearn.html](http://www.learningcircuits.org/2002/jan2002/elearn.html)

Evaluating E-Learning Developers [http://www.learningcircuits.org/2002/dec2002/elearn.html](http://www.learningcircuits.org/2002/dec2002/elearn.html)

Managing the E in E-Learning [http://www.learningcircuits.org/2002/nov2002/elearn.html](http://www.learningcircuits.org/2002/nov2002/elearn.html)

[E-Learning](http://www.learningcircuits.org/2005/aug2005/obrien.htm) [](http://www.learningcircuits.org/2005/aug2005/obrien.htm)[Maintenance Strategies — Why You Need One](http://www.learningcircuits.org/2005/aug2005/obrien.htm)

[Driving Higher Ed Institutions to an](http://www.learningcircuits.org/2004/sep2004/ross.htm) [](http://www.learningcircuits.org/2004/sep2004/ross.htm)[Enterprise](http://www.learningcircuits.org/2004/sep2004/ross.htm) [](http://www.learningcircuits.org/2004/sep2004/ross.htm)[Approach](http://www.learningcircuits.org/2004/sep2004/ross.htm)

[Pitfalls of LMS](http://www.learningcircuits.org/2004/jul2004/howard.htm) [](http://www.learningcircuits.org/2004/jul2004/howard.htm)[Implementations](http://www.learningcircuits.org/2004/jul2004/howard.htm)

[Basics Of CMS](http://www.learningcircuits.org/2002/may2002/mayberry.html) [](http://www.learningcircuits.org/2002/may2002/mayberry.html)[Implementation](http://www.learningcircuits.org/2002/may2002/mayberry.html)

Another way of learning is to to get a peek into what other problems you might encounter and what to look out for, it will be good to look for LMS case studies, almost all LMS vendors have some case studies and success stories (ASTD has also listed some); however, since these are mostly vendor written, they may hide more than they will reveal, so it is good only for starting point.

[http://www.moodle.com](http://www.moodle.com/) is a great open source LMS, there are tons of open source CMS out there, so if you are on shoe-string budget and have some techies in-house, exploring all open-source solution may be a good idea.

Overall, e-learning initiative design and implementation is a complex activity, hopefully this writeup helps somewhat. drop me a note if you need any help and I will try to write more.
