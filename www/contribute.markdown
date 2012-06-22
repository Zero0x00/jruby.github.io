---
layout: main
title: Contributing to JRuby
---
# Contributing to JRuby
  
JRuby depends on community contributions to survive. Here's how you can get involved:

**Get the Source** - The JRuby source is stored in our Git repository at JRuby.org and mirrored at GitHub.

- **Browse**: [**GitHub**](http://github.com/jruby/jruby)
- **Checkout**

      git clone git://jruby.org/jruby.git
      git clone http://jruby.org/repo/jruby.git
      git clone git://github.com/jruby/jruby.git
      git clone http://github.com/jruby/jruby.git

*Need [Git help](http://git-scm.com/)? It's ok, we're not Git experts either.*

**Build JRuby** - Once you've checked out the source, you just need to run &quot;ant&quot;&nbsp;or &quot;ant jar&quot;&nbsp;to build and &quot;ant test&quot;&nbsp;to run our test suite. We depend on <a href="http://ant.apache.org/">Apache Ant</a> 1.7.0 or higher.

      ant
      ant jar
      ant test

**Check out the Hacking Guide** - NaHi built an [awesome Prezi fly-through tour of the JRuby codebase][prezi]. Take a look through it for getting bearings with the codebase.

**Report Bugs** - Our bug tracker uses Atlassian JIRA. Please report anything you think is a bug! Performance problems are considered bugs, so please report those too.

- **Bug Tracker**: [**Browse**]({{ site.urls.jira }})

**Fix Bugs** - We'd love it if you help triage or fix open bugs. We've created a [**HelpWanted**][helpwanted] section of the bug tracker where we appreciate all the help we can get!

- **HelpWanted**: [Browse][helpwanted]

**Submit Code Changes** - Code changes are great.  Send them back with a [GitHub pull request][pullrequest] for review.

**Fix the wiki** - We also depend on community contributions and edits to keep our documentation informative and relevant. If you have a useful FAQ or walkthrough or article, please add it to the wiki. And we welcome anyone who wants to help reorganize or edit existing content.

- **Wiki**: [**Browse**]({{ site.urls.wiki }})

**Fix the website** - Our website source code is publicly available, and we graciously accept pull requests!

- **Website**: [**Browse**](http://github.com/jruby/jruby.github.com) &nbsp;|&nbsp;[**Checkout**](git://github.com/jruby/jruby.github.com.git)

[helpwanted]: http://bit.ly/jruby-help-wanted
[prezi]: http://prezi.com/tsuouxb3z4ln/jruby-hacking-guide/
[pullrequest]: https://help.github.com/articles/using-pull-requests

