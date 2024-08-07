---
layout: post
title:  "Thoughts on Secure coding training"
---
Because secure coding training is often conceived as a check-the-box compliance activity, it gets resourced accordingly and lightly implemented. _So what can a developer get out of a videos & quizzes-only approach_? 

They certainly practice watching videos and taking tests, but does this activity correspond to increased secure coding competency (our desired outcome)?

I think a well-designed secure coding training program has the potential to be a real force multiplier in the context of modern DevSecOps with its platform engineering focus. _Can we figure out how to measure competency, connect it to outcome, and better position our developers for success_?

## The problem in a nutshell
So why does the technology world have a cybersecurity problem? If you believe that "software is eating the world", then perhaps much of the answer lies in how we develop software.

To the extent that an existing vulnerability is a security bug that was _unwittingly_ written into code by a developer, how many bugs can we prevent from being introduced by improving secure coding competency and awareness?

After all, if the well-meaning developer knows to (and how to) write secure code, under what circumstances would vulnerable code still be produced?

## Relative positioning in the SDLC
As an Application Security engineer working in DevOps, I try to help teams by implementing self-service infrastructure (i.e., platform engineering) that puts alert data into developer hands at "the right time", ideally in phase with their standard workflow and when newly written code is still fresh in mind (_bugs are cheaper to fix then_).

This "layer of defense" primarily leverages SAST (static application security testing) at the pull request, which is great for what it is, as a timely safety net to catch known security bugs that we can detect through static analysis of code, but are there meaningful things we can do earlier in the SDLC -- _especially to avoid writing the bug in first place_?

## The experiment
Can secure coding be learned? Can it be taught? _What happens when we place a more carefully considered emphasis on teaching and learning_? And properly resource it.

After inheriting a "videos + quizzes" secure coding training program (a good one for what it was) a few years ago and opportunistically re-designing and re-implementing it this past year around an innovative platform (with an opinion on how to measure and score secure coding competency) that provides high-quality hands-on labs and a "hack it first, then fix it" approach for developers, I have reason to be cautiously optimistic, maybe even naively excited about further possibilities.

-- JW
