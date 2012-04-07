---
layout: post
title: "What I Wish I Knew for the Design Project"
date: 2012-04-06 19:00
comments: true
author: "Michael Chang, David Hu, Ming-Ho Yee"
categories: [fydp, se390, se490, se491]
---

Having completed their design projects, the 2012 class of Software
Engineering gave an informal presentation today to share their
experiences.

Choosing Groups
---------------

"*I think Paul Thagard is a good customer.*" -D. Rayside

- Choosing your group is the key step, will be with them for **1.5
  years**
- Similar (interests, work ethic, coding styles)
  - "... or you'll be working by yourself, and there *will* be
    unhappiness."
- Technical Electives
  - Trains, Graphics are very high-workload -- if all of you are
    enrolled in these together, your project will stagnate or suffer
- Multiple Approaches
  - Find people you've worked with before, people who you know you can
    work with
    - Are the people "who you drink beer with" the best group
      members?
    - You know what kinds of (in)actions have made you (un)happy -
      can evaluate whether you're willing to live with those
  - Defer group formation, have people coalesce around project ideas
    - "Don't be afraid to work with someone you've never worked with
      before.'
  - Work with people you've never worked with before
    - You don't get to choose who you work with in industry
- Significant Others
  - Don't
  - Design project can strain relationships
    - "I'm not sure I'd want to work with my wife. You know, seeing the
      same person 168 hours a week. Maybe your relationship is more
      likely to succeed if you're in different project groups."
  - If you break up and you still have to work with them for design
    project...
- Analogies
  - Like roommates - not everyone you're good friends with is
    someone you want to be roommates with
  - D. Rayside: "P. Ward says, '_The difference between marriage and
    your group is that you can divorce a marriage._'"
    - "In 2011, a divorce did happen, but that meant someone
      _transferred out of the program_."

Choosing a Project
------------------

- Evaluate ideas wrt. personal goals for the design project
  - Build something the client will use
  - Cutting-edge research
- Don't throw out common sense
- It's fun to brainstorm and come up with ideas
  - Important to get a core idea ("minimal viable product") to work
    with
  - Take notes; record all ideas when brainstorming
  - Don't get stuck in this stage foreve
- Scope
  - Keep in mind that time is limited
  - Don't let the scope of your project get out of hand
  - Estimate 40 hours per person of time to get a working demo, then
    iterate

Having A Customer
-----------------

- Start looking for an external customer early
- Very useful to have a "real client" 
  - Client defines requirements (or even the project!)
  - Regular (daily/weekly) meetings can be motivating
    - "Here's what we've accomplished, and what we need to do."
- Be clear about expectations, esp. intellectual property, money, legal
  - Policy 73
  - "Things get more complicated when you go outside the university."
    - Anecdote: Client re-sold app to TTC, students got no money
  - Template IP agreements should be available when we start (P. Ward)
  - VeloCity / Student Success Office may also be able to give advice
    wrt. IP


Project Management
------------------

- Divide project into small and tangible chunks
- Have "feature freezes" early, to reserve time to fix bugs
  - Tempting to code right up to demo deadline, results in a broken
    demo
- Commit discipline
  - Have meaningful commit messages
  - Commit after each bug/feature, NOT after three and a half weeks
- Prioritize: requirements tend to slip each week
- Need to manage time properly - deadlines may be far, but they exist
- Tempting to think that you can work over co-op
  - But it's challenging after a 9-hour work day
  - Groups that -do- work on FYDP during work term reported feeling ahead
    of the game
- Consider selecting a team leader 
  ([BDFL](http://en.wikipedia.org/wiki/Benevolent_Dictator_for_Life))
  - Comment: There -will- be arguments over decisions
  - Comment: The arguments are usually opinion-related; probably won't
   have a huge impact on the project in the long run
- Get mobile apps into market ~1 month early to get feedback
  - Can fix bugs, or learn what to expect when demoing on symposium day

Technical Infrastructure
------------------------
- Project Infrastructure is useful (this isn't some random assignment)
  - Bug Trackers
  - Automated Build Systems
    - D. Rayside: "I will punish you for not having an automated build
      system."
  - Test Harnesses / Unit Tests
    - some things lend themselves really well to unit tests
    - UI is often hard to unit test
    - good for refactoring
  - Testimonial: GitHub is really easy for commits/bug tracking
  - bring in [Joel test](http://www.joelonsoftware.com/articles/fog0000000043.html)
- Domains
  - Do NOT use GoDaddy -- appear cheap, but have long TTLs on DNS
    updates (and make life hell if you want to switch away)
    - WhoisGuard makes them more expensive then competitors
  - Consider NameCheap, Netfirms, Dyn
- Email
  - Use Google Apps to set up email addresses with your domain name
    - Free tier exists -- use it!
    - Convenient, email isn't tied to personal accounts
    - Many registrars (e.g. NameCheap) will add the required MX
      records for Google Apps in one click
  - Use project-specific email when signing up for stuff
    - Useful if you want to split project off later for a startup
    - Avoids single point of failure (if you get hit by a bus and
      everything is attached to your email address...)
- Web Hosting
  - AWS, Prgmr, Linode
    - More control
    - Build from the ground up (learn sysadmin skills)
    - OpenBSD?
  - Elastic Beanstalk, App Engine
    - Usually locked into framework once chosen
- SSL
  - Free certs from cert.startcom.org, www.startssl.com
  - "Do not pay into the cartel"
- Frameworks: Django, Ruby on Rails
  - YMMV: Start with a framework that you're not familiar with, to learn about it
  - Be wary with ORM limitations: raw SQL is occasionally better
    - Does your ORM do _LEFT SEMI JOIN_?

Miscellaneous
-------------

"*Here's a story - an unprofessional story in a sense - of a wiki that
lived on a machine in someone's office. And that hard drive died.*"
-D. Rayside

- D. Rayside intends to add "a bit of structure" to provide "social
  motivation" to get students to work on the design project
  - Per-group bug tracker
  - Each team submits lines and hours, and we take the top and bottom
    and annoit them as "professionals" and "mediocrity"
  - "I want to keep the data in a programatically convenient form."
- Historical artifacts
  - Left by 2012 class for our study (hopefully backed up by ECE)
  - None from prior years

- We will likely have D. Rayside for SE 490

- The ultimate deadline is on symposium day at the end of 4B
  - People seem to like great ideas over good implementations of OK ideas

