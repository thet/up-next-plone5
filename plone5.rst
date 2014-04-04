
Up next: Plone 5
================

$ whoami
--------

* Johannes Raggam (DI(FH))

* Seit 2003: Zope 2

* Seit 2004: Plone

* Seit 2005: Collective

* Seit 2008: AT Contributor

* Seit 2009: Plone Core Contributor

* Seit 2012: Framework Team Member


$ whatis Plone
--------------

Enterprise CMS

Collaboration System

Document Management System

CMS Framework


$ whatis Plone
--------------

Object Database, Content Tree und Object Traversal

Security Record ++

Permission und Workflow System ++

UI: Backend = Frontend

Plugability ++


$ apropos Plone
---------------

GPLv2

Python 2.7

Zope 2, Mother of all Frameworks

ZODB (Zope Object Database)

Zope Component Architecture GOODNESS!

Legacy Code Hell MADNESS!

Buildout GOOD/MADNESS!

236 PyPI Packges!


$ whois Plone
-------------

* Seit 2002 (Europython, Alex Limi, Alan Runyan: Plone 1.0)

* Offenes Entwicklungsmodell:
  - github.com/collective - Github-Issue für R/W Access - 426 Members
  - github.com/plone - Plone Core Contributor Agreement - 318 Members

= 318 Core Contributors!

* Github to the rescue! (Pull-Requests, Code reviews)

* Continuous Integration to the rescue! (Jenkins, TravisCI)


$ whois Plone
-------------

* Framework Team

* Testing Team

* Documentation Team

* UI Team

* Accessibility


$ whois Plone
-------------

* PLIP Process

* Sprints


$ whereis Plone
---------------

http://plone.org/

http://www.fsf.org/

http://science.nasa.gov/

http://www.amnesty.ch/

http://www.donaufestival.at/ + NÖKU

http://htu.tugraz.at/

http://helsinki.at/

http://mur.at/



to the rescue: Plone 5
----------------------

* Neues Contenttype Framework: plone.app.contenttypes

* Neues Kalender Framework: plone.app.event

* Neues Widgetset: plone.app.widgets

* Neues Javasript Development Environment: Mockup

* Neues Theme: Barceloneta

* CSRF Protection





Die Herausforderungen
----------------------

* Developers, Developers, Developers!

* Paradigmentshift: Javascript
  -> Mockup
  -> JSON API


Use It!
--------

https://github.com/collective/minimalplone4/

https://github.com/plone/buildout.coredev/tree/5.0














Eric Steele on UI/Accessibility testing
Subject:	Re: [Plone-developers] Usability testing Plone 5.0
Date:	Tue, 11 Mar 2014 07:08:54 -0400 (03/11/2014 12:08:54 PM)

Paul Roeland is leading an accessibility team. They've already been pushing
significant markup changes, adding ARIA roles, and generally making sure Plone
5 is fully WCAG2 compliant. Our blind tester, Michelle, is still at Penn State
and I'm sure we could talk her into finding where things break in Plone 5.
Asko's added automated testing to catch the basic issues if they creep in. We
have a UI team that's been steering design choices. We have several groups who
have volunteered as focus groups.


From:	Paul Roeland <paul@cleanclothes.org>
Subject:	Re: [Plone-developers] Usability testing Plone 5.0
Date:	Tue, 11 Mar 2014 16:11:25 +0100

- about 157 differing shades of blue were tested, to make sure we comply
with colorblind- and contrast rules.
- modals (that's fancyspeak for popups) have proper, accessible close
buttons.
- ARIA roles have been added where sensible, not just to the toolbar,
but also to all content areas, portlets etcetera
- we have a bullet-proof way of including vector-based/font-based icons,
that works across devices, screenreaders, etctera.
