Welcome to My Sublime Text 2 Set Up
===================================

For years I loved and used Emacs and could not move to any other editor because
of lack of the configuration and customization (for my taste). For one, they
never provides the key-bindings I loved or a easy to develop in plug-in system.

Then, I found Sublime Text 2. A completely customizable editor allowing you to
easily modify all default behaviours so that they suit your editing style.

Here is hopping I can build on the work of sublemacspro, and other plug-ins and
get me an editor I want.


Installation
============

1. Install Package Control
2. Add this git repository as a channel
3. Use "Package Control: Install"


Conflicts
=========

Installing the following packages will probably generate conflicts dues
to the plug-in commands named the same.

 - sublemacspro


Features
========

Ctrl-\ is used a modmap modifier for most features that have been remapped.

The following features were adapted from various plug-ins:

sublemacspro
~~~~~~~~~~~~~

A number of key-bindings of sublemacspro were removed

 - Ctrl-r and Ctrl-s were remapped to search. Ctrl-\ r is now used to pull up
   symbols.

 - Kill line, region ... with kill ring using *M-w*, *C-w*, *C-y*

 - Yank with free choice from kill ring using fancy overlay: Just press *C-Y*
   to access the kill ring and search for your last copy and paste.

 - Rectangular cut and insert using *C-x r t* and *C-x r d**

 - Find file at point *M-x f f a p* opens the file your current cursor points to

 - Automatic mode detection like it's done in Emacs using prefixes
   *-\*- c++ -\*-*


Future
======

Probably more random Emacs goodness.


Authors and Contributors
========================
 - Me
 - Authors of sublemacspro
