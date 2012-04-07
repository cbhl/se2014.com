---
layout: post
title: "What I Wish I Knew for the Design Project"
date: 2012-04-06 19:00
comments: true
author: "Michael Chang, David Hu, Ming-Ho Yee"
categories: [fydp, se390, se490, se491]
---

Having completed their design projects, the 2012 class of Software
Engineering gave an informal presentation on Thursday to share their
experiences.

Choosing Groups
---------------

"*I think Paul Thagard is a good customer.*" -D. Rayside

- Choosing your group is the key step, will be with them for **1.5
  years**
- Similar (interests, work ethic, coding styles, language/framework)
  - "... or you'll be working by yourself, and there *will* be
    unhappiness."
- Technical Electives
  - If enrolled together, your project will stagnate or suffer
- Multiple Approaches
  - Find people you've worked with before, people who you know you can
    work with
  - Defer group formation, have people coalesce around project ideas
    - "Don't be afraid to work with someone you've never worked with
      before.'
  - "You don't get to choose who you work with in industry."
- YMMV: Significant Others
  - "I'm not sure I'd want to work with my wife. You know, seeing the
    same person 168 hours a week. Maybe your relationship is more
    likely to succeed if you're in different project groups."
- Analogies
  - Like roommates - not everyone you're good friends with is someone
    you want to be roommates with
  - D. Rayside: "P. Ward says, 'The difference between marriage and
    your group is that you can divorce a marriage.'"
    - "In 2011, a divorce did happen, but that meant someone
      _transferred out of the program_."

Choosing a Project
------------------

- Evaluate ideas wrt. personal goals for the design project
  - Research?
- It's fun to brainstorm and come up with ideas
  - Take notes; record all ideas when brainstorming
  - Don't get stuck in this stage forever
- Scope: build MVP (Minimal Viable Product) first, then iterate
  - est. 40 hrs/person for MVP -- any more and it's not minimal enough

Having A Customer
-----------------

- Start looking for an external customer early
  - "Good" client defines requirements, will use product (daily?)
  - Regular (daily/weekly) meetings can be motivating
- Be clear about expectations, esp. intellectual property, money,
  legal
  - Policy 73
  - "Things get more complicated when you go outside the university."
  - Template IP agreements coming: P. Ward, VeloCity/SSO

Project Management
------------------

- Divide project into small and tangible chunks
- "Feature freezes" for bug fixing
- Have meaningful commit messages
- Commit after each bug/feature, NOT after three and a half weeks
- Prioritize: requirements tend to slip each week
- Work over co-op is challenging after 9-hr work day
  - Groups that -do- work on FYDP during work term reported feeling
    ahead of the game
- Consider selecting a team leader
  ([BDFL](http://en.wikipedia.org/wiki/Benevolent_Dictator_for_Life))
  - Comment: There -will- be arguments over decisions
- Get mobile apps into market ~1 month early to get feedback

Technical Infrastructure
------------------------
- Bug Tracking: GitHub
- Automated Build Systems
  - D. Rayside: "I will punish you for not having an automated build
    system."
- Test Harnesses / Unit Tests
  - good for refactoring
- bring in [Joel
  test](http://www.joelonsoftware.com/articles/fog0000000043.html)
- Domains
  - Do NOT use GoDaddy
  - Alternatives: NameCheap, Netfirms, Dyn
- Email
  - Google Apps: Free Tier
  - Use project-specific email when signing up for stuff
    - Avoids single point of failure (if you get hit by a bus and
      everything is attached to your email address...)
- Web Hosting
  - Cloud/VPS: AWS, Prgmr, Linode
    - Skills and Flexibility
    - OpenBSD?
  - Elastic Beanstalk, App Engine, Heroku
    - Vendor lock-in
- SSL
  - Free certs from cert.startcom.org, www.startssl.com
- Be wary with ORM limitations: raw SQL is occasionally better
  - Does your ORM do _LEFT SEMI JOIN_?

Miscellaneous
-------------

"*Here's a story - an unprofessional story in a sense - of a wiki that
lived on a machine in someone's office. And that hard drive died.*"
-D. Rayside

- D. Rayside intends to add "a bit of structure" to provide "social
  motivation" to get students to work on the design project
  - Each team submits lines and hours, and we take the top and bottom
    and annoit them as "professionals" and "mediocrity"
  - "I want to keep the data in a programatically convenient form."
- Historical artifacts available from 2012 class
  - None from prior years
- We will likely have D. Rayside for SE 490
- The ultimate deadline is on symposium day at the end of 4B
- Be enterprising, practical, creative, risk-taking, innovative,
  relevant

