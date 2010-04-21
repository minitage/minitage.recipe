******************************************************************************
Recipe for compiling and installing software with or without minitage
******************************************************************************

.. contents::

=======================
Introduction
=======================

This was a collection of recipes which can be use inside or outside a minitage environment.

As they are now all splitted out from this package, we keep only left the
entry points for asccendant compatibility purpose.
the build environment automaticly.

The egg has those entry point:
    - *cmmi*: install configure/make/make install softwares
    - *fetch*: fetch something, somewhere, with git, http, frp, static, hg, svn or bzr.
    - *egg*: install python eggs / packages 'setuptoolisables'
    - *printer*: print or dump to a file all versions needed to achieve eggs
      requirements (versions.cfg made easy)
    - *scripts*: install scripts from an egg and install egg dependencies if they
      are not already in the cache
    - *wsgi*: Make a Python paste configuration file eatable by mod_wsgi with
      all the eggs dependencies you need.

You can browse the code on minitage's following resources:

    - http://git.minitage.org/git/minitage/eggs/minitage.recipe/
    - http://www.minitage.org/trac/browser/minitage/eggs/minitage.recipe

You can migrate your buldouts without any effort with buildout.minitagificator:

    * http://pypi.python.org/pypi/buildout.minitagificator

======================================
Makina Corpus sponsorised software
======================================

  http://www.makina-corpus.com & http://makina-corpus.org

    plone at makina-corpus org


