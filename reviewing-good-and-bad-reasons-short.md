# Bad Reasons to Reject Good Papers, and vice-versa (Am I Reviewer #2 ?)
# Peter Sewell, 2021-11-01

This note tries to spell out some of what constitutes good reviewing, to refresh and provide a little push towards a better consensus.

As reviewers, what do we have to decide? Fundamentally, whether publishing the paper will advance the subject in some substantial way. In more detail:

- is the motivation real - does the paper address an important problem?
- would the claims it makes constitute substantial progress?
- are those claims backed up - is it technically solid?
- is it well-written - enough for readers (with the appropriate background) to understand?

Then, as our venues are typically competitive, we have to weigh the paper against other submissions (how competitive they should be is a question, but we won't go into that here) - so reviewers need some sense of the level of contribution appropriate to the venue, so that their scores are broadly comparable.

## Bad Reasons to Reject Good Papers

Reviewing is essentially a judgement call. We've discussed our review processes at great length over the years, and those processes do matter - we've tuned them, and I think in many ways improved them - but, fundamentally, peer review relies on informed judgements from a suitably expert and sensible group of people. So this note is not about process. Instead, it identifies some of the bad forms of argument that one sees again and again. If one sees one of these, or if one finds oneself writing one, an alarm bell should ring...

- I could have done this better, if only I'd got round to it
- I can imagine some quite different research that I'd prefer
- I can imagine some quite different exposition that I'd prefer
- It's not self-contained/accessible to me, because I don't know the work it builds on 
- It's not self-contained, because this project is too big for all the details to fit in the page limit
- I want more examples / discussion (fitting into the page limit by magic)
- I want extra evaluation (even though it does a decent job to support the claims)
- I just wasn't excited by it (even though it's a clear advance on an important problem)
- I'm assessing this as if it was about X, even though it's actually about Y
- I'm assessing this as if it was a paper of kind X, even though it's actually of kind Y  (PL spans many kinds of papers, with different values and criteria)
- It's about language design
- It's too mathematical
- It's about the semantics of actual languages, which makes it complicated
- They didn't mechanise all the proofs (though they didn't claim that they did)
- A previous paper claimed to do this (though it doesn't really subsume this)
- It could do with another pass (and the authors will thank us for rejecting it)
- It presents a big project, not a single clever/cute idea that can be fully explained in a few pages
- The idea here is too simple (even though it's very useful, and no-one fleshed it out and published it before)
- It's incremental (even though it's a _big_ increment - most research is advancing previous work)
- This feels more like a paper for venue X (even though it could perfectly well fit here)
- This should be a journal paper instead (for good and ill, PL is based on conference publication)
- The authors already put a version on the web 
- I'm working on a competing project
- (and finally, the classic) It doesn't cite my paper

Many of these boil down to having due respect for the authors and the work they've put in. Remember, they've typically spent between one and ten person-years on this, while the reviewer has spent maybe a day. We're not awarding prizes for effort, and sometimes a reviewer will understand things better than the authors, but one should be wary as a reviewer of trying to require substantially different research or exposition.

Of course, none of them are absolutes - even the last reason above can be a legitimate complaint in specific circumstances, e.g. if that uncited paper renders the submitted work moot.

Another bad reason arises during discussion, after the first reviews have been written.  At the end of the process, one has to arrive at accept/reject decisions, but during the process it's all too easy to regard the current scores as an objective assessment, e.g. saying "this is a `B' paper".  The whole point of the discussion is to consider whether reviews are wrong or miscalibrated - otherwise we'd just order papers by the original scores.


## Good Reasons to Reject Bad PL Papers

On the other side, not all papers are good, unfortunately, and we shouldn't shy away from rejecting poor-quality work, lest the subject be contaminated by bogosity. Returning to the above list, in order of decreasing importance:

- is the motivation real - does the paper address an important problem? (sometimes, simply identifying an important problem is a major contribution)
- would the claims it makes, if true, constitute substantial progress?
- are those claims backed up - is it technically solid?
- is it well-written - enough for readers (with the appropriate background) to understand?

A clear "no" for any of these should rule the paper out from any serious venue. In more detail:

- The motivation isn't explained - it doesn't clearly explain why anyone should care
- The motivational argument is bogus
- The work is technically correct but pointless (basically a rephrasing of the above)
- The claims (presuming they are substantiated) wouldn't significantly advance the subject (it really is a minor increment over previous work)
- ...or, so far, really insufficiently developed for this venue
- It really has been done before
- The claims are misleading: the work is over-sold and the authors aren't clear about the limitations, or about the relationship to previous work
- The claims are unsubstantiated: it doesn't give the actual proofs or data, without a good reason why not
- The claims are unsubstantiated: the evaluation is too limited or too flawed to support the claims
- It is substantially less rigorous (theoretically or experimentally) than normal practice in the area
- It's technically wrong (and isn't straightforwardly fixable)
-  The exposition is so bad that it's hard (even for an informed reader) to understand what the authors have actually done

When arguing that a paper should be rejected, or summarising a PC decision for the authors, it may be useful to identify exactly which of these (or other) reasons justify that.

---

This is a slightly shortened version of this note, with edits by Jan Vitek.
