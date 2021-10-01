# Academic Library 

# TOC 

Jump to 

__Sections:__

[1. Introduction](#introduction)

[2. Template](#template-for-new-entries)

__Authors:__
[A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) [J](#j) [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) [X](#x) [Y](#y) [Z](#z) 

# Introduction 

I wanted a low-dependency way to organise my academic books and articles. Open-source and paid-for software tools for this are pretty good but I don't want to buy into a system (paying with my time) that might be useless down the line. To resolve this I am making my own simple system, essentially an alphebetised stack of papers. 

When I read a paper IRL, I like to:

- have a copy of the paper that I keep after reading;
- make light or detailed notes as I read;
- write a short summary so that I don't have to re-read the same paper to remember its key points or which of an author's papers to cite. 


This is a place to store such summaries and keywords for academic papers, books and online resources. It is linked to a master bib file (library.bib) for citing these resouces. 

I've tried this sort of thing before and it fell apart because I did not give myself rules and templates for adding new entries. Below are my starting guidelines 

## Including a new entry

- The original documents should be filed using bibtex naming. e.g.  `chavez2005estimating.pdf`

- Annotated versions should be filed by appending "\_annotated". e.g. `chavez2005estimating_annotated.pdf`

- Detailed notes should be filed by appending "\_notes". 
	- Typed notes should be filed in markdown documends e.g. `chavez2005estimating_notes.md` 
	- Hand written notes should be scanned or exported as pdf documents e.g. `chavez2005estimating_notes.pdf`

- Each document should have a (human corrected) bibtex entry in library.bib 

- Each document should have a rhetorical précis entry in this document along with keywords

## A note on git
Github has very nice rendering of markdown and so I want to make the most of that when creating this library document. 

The plain text files (.md and .bib) should be version controlled, but pdf documents should not. Google drive is currently being used to provide local and cloud storage of pdfs. 


## What is a rhetorical précis? 

__Attribution:__ [lumenlearning.com]( https://courses.lumenlearning.com/englishcomp2kscopex92x2/chapter/rhetorical-precis/)


A rhetorical precis analyzes both the content (the what) and the delivery (the how) of a unit of spoken or written discourse. It is a highly structured four-sentence paragraph blending summary and analysis. Each of the four sentences requires specific information; students are expected to use brief quotations (to convey a sense of the author’s style and tone) and to include a terminal bibliographic reference. Practicing this sort of writing fosters precision in both reading and writing, forcing a writer to employ a variety of sentence structures and to develop a discerning eye for connotative shades of meaning.

__Format:__ 

Four sentences summarising the aim, how is is addressed, why it is important, and who the target audience for this work is. 

1. Name of author, [optional phrase describing author], genre and title of work, date in parentheses (additional publishing information in parentheses); a rhetorically accurate verb (such as “asserts,” “argues,” suggests,” “implies,” claims,” etc.); a THAT clause containing the major assertion or thesis statement of the work.
2. An explanation of _how_ the author develops and/or supports the thesis, usually in chronological order.
3. A statement of the author’s purpose followed by an “in order to” phrase.
4. A description of the intended audience and/or the essay’s tone


__Worked example:__ 

---------------------------------------------------------------------

`varty2021inference`

**Title:** _Inference for extreme earthquake magnitudes accounting for a time-varying measurement process. {ArXiV preprint, 2021} (20 pages)._

**Authors:** _Zak Varty, Jonathan Tawn, Peter Atkinson and Stijn Bierman._

**Key words:** _extreme value_, _earthquake_, _threshold selection_, _magnitude of completion_, _seismology_, _bootstrap._

In this paper, Varty et al (2021) propose a new threshold selection method for modelling earthquake catalogues where the magnitude distribution is stationary but detection of small events improves over time. The paper generalises the Gutenberg-Richter law to the GPD and uses metrics based on PP and QQ plots to balance between bias and variance when selecting a time-varying threshold. This procedure more than doubles the usable catalogue size for Groningen earthquakes and gives the first emprircal evidence that the magnitude distribution in this region has a finite upper end point. The paper is targeted at applied and research statisticians with an interest in EVT but would be accessible to a statistically-minded seismologist. 

---------------------------------------------------------------------

# Template for new entries 


---------------------------------------------------------------------

`firstauthor1970word`

**Title:** _Title goes here. {Journal, YYYY} (NN pages)._

**Authors:** _Author One, Author Two and Author Three. (optional affiliations)_

**Key words:** _key word 1_, _key word 2_, _key work 3_. 

1. _What_ is the document and _what_ does it say? 
2. _How_ do they do / show this?
3. _Why_ are they bothering to do this in the first place?
4. _Who_ is the intended audience for this work?

In this DOC_TYPE, AUTHOUR VERB that THESIS\_STATEMENT.
They DO/SHOW this by ACTIONS. 
This is important to PEOPLE because REASONS. 
This work would be useful when PEOPLE are doing ACTIVITY.

---------------------------------------------------------------------

# A
# B
# C
# D
# E
# F
# G 
# H 
# I 
# J 
# K
# L
# M
# N 
# O
# P 
# Q
# R 
# S 
# T 
# U 

# V 

---------------------------------------------------------------------

`varty2021inference`

**Title:** _Inference for extreme earthquake magnitudes accounting for a time-varying measurement process. {ArXiV preprint, 2021} (20 pages)._

**Authors:** _Zak Varty, Jonathan Tawn, Peter Atkinson and Stijn Bierman._

**Key words:** _extreme value_, _earthquake_, _threshold selection_, _magnitude of completion_, _seismology_, _bootstrap._

In this paper, Varty et al (2021) propose a new threshold selection method for modelling earthquake catalogues where the magnitude distribution is stationary but detection of small events improves over time. The paper generalises the Gutenberg-Richter law to the GPD and uses metrics based on PP and QQ plots to balance between bias and variance when selecting a time-varying threshold. This procedure more than doubles the usable catalogue size for Groningen earthquakes and gives the first emprircal evidence that the magnitude distribution in this region has a finite upper end point. The paper is targeted at applied and research statisticians with an interest in EVT but would be accessible to a statistically-minded seismologist. 

---------------------------------------------------------------------

# W 
# X 
# Y 
# Z
