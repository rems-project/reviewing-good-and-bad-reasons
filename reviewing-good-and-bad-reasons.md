# Bad Reasons to Reject Good Papers, and vice versa

### (or, Am I Reviewer #2?)

### On reviewing in computer science, especially around PL-related topics (programming languages, semantics, verification)

### Peter Sewell, 2021-11-05  (`Peter.Sewell@cl.cam.ac.uk`)

Peer review is an essential aspect of academic research: when it works
well, it provides a feedback loop that stimulates and rewards
high-quality research, helping the subject advance.  But, as we all
know, it doesn't always work well.  There never was a Golden Age when
it did, of course, but it's become harder to maintain a shared view of
what constitutes good reviewing as the subject grows, with larger
numbers of submissions, larger programme committees, and the shift to
purely on-line discussion.  All these have weakened the feedback loop
that promoted high-quality reviewing, as PC members no longer have to
explain their assessments live in front of their peers, often see
nothing of the discussion of papers they did not review, and may not
even have read all the submitted titles and abstracts.  Instead, we
load all that responsibility for maintaining review quality and common
standards on our PC chairs - a nigh-on impossible task across hundreds
of on-line discussions.

This note tries to spell out some of what constitutes good reviewing,
to refresh and provide a little push towards improving our consensus.  It's
focussed on PL-related research (programming languages, semantics, and
verification), but much is more generally applicable.  I started these
lists as POPL PC Chair in 2014 and expanded them on
[twitter](https://twitter.com/peter_sewell_/status/1442750114196492288), and an edited version has been used by Amal Ahmed and Jan Vitek as part of the OOPSLA 2022 reviewing guideleines; 
the current version is on
[github](https://github.com/rems-project/reviewing-good-and-bad-reasons/blob/main/reviewing-good-and-bad-reasons.md).
Comments are welcome, preferably by email; 
many thanks to all those who have commented
on previous versions.

As reviewers, what do we have to decide?  Fundamentally, whether
publishing the paper will advance the subject in some substantial way.
In more detail:

- is the motivation real - does the paper address an important problem?
- would the claims it makes constitute substantial progress?
- are those claims backed up - is it technically solid?
- is it well-written - enough for readers (with the appropriate background) to understand?

Then, as our venues are typically competitive, we have to weigh the
paper against other submissions (how competitive they _should_ be is a
question, but we won't go into that here) - so reviewers need some
sense of the level of contribution appropriate to the venue, so that
their scores are broadly comparable.


## Bad Reasons to Reject Good Papers

Reviewing is essentially a judgement call.  We've discussed our review
processes at great length over the years, and those processes do
matter - we've tuned them, and I think in many ways improved them -
but, fundamentally, peer review relies on informed judgements from a
suitably expert and sensible group of people.  So this note is not
about process. Instead, it identifies some of the bad forms of
argument that one sees again and again.  If one sees one of these, or
(especially!)  if one finds oneself writing one, an alarm bell should
ring...

1. I could have done this better, if only I'd got round to it
2. I can imagine some quite different research that I'd prefer 
3. I can imagine some quite different exposition that I'd prefer (suggesting actionable improvements is useful, of course)
4. It's not self-contained / accessible to me, because I don't know the work it builds on (even though it recaps as much as possible)  (in this case the reviewer has to give a non-expert view, and one should be looking for more expert reviewers that do have the right background)
5. It's not self-contained, because this project is too big for all the details to fit in the page limit
6. I want more examples / discussion (fitting into the page limit by magic)
7. I want extra evaluation (even though it does a decent job to support the claims) 
8. I just wasn't excited by it (even though it's a clear advance on an important problem)   (our ABCD identify-the-champion scoring is good in many ways, but it fails for papers that hit this)
9. I'm assessing this as if it was about X, even though it's actually about Y
10. I'm assessing this as if it was a paper of kind X, even though it's actually of kind Y  (PL spans lots of different kinds of papers, with different values and criteria)
11. It's about language design (bonus points if this is PLDI)
12. It's too mathematical (bonus points if this is POPL)  (this is usually an instance of 4)
13. It's about the semantics of actual languages, which makes it complicated (bonus points if this is POPL)
14. They didn't mechanise all the proofs  (though they didn't claim that they did)
15. A previous paper claimed to do this (though it doesn't really subsume this, or didn't appear before this submission)
16. It could do with another pass (and the authors will thank us for rejecting it)  (very occasionally this is eventually true, but there's a big cost, especially to the careers of junior authors)
17. It presents a big project, not a single clever/cute idea that can be fully explained in a few pages (these are different kinds of paper; both are good)
18. The idea here is too simple (even though it's very useful, and no-one fleshed it out and published it before) 
19. It's incremental w.r.t. previous work (even though it's a _big_ increment - most research is, necessarily, advancing previous work)
20. This feels more like a paper for venue X (even though it could perfectly well fit here) (usually a PC chair will have to desk-reject just a couple of really out-of-scope papers)
21. This should be a journal paper instead (for good and ill, PL is based on conference publication)
22. The authors put a version on their web page / on arxiv / as a techreport  (that's explicitly allowed by our normal lightweight double-blind (LDB) policy, as otherwise normal scientific communication would be inhibited; the point of LDB is just to let reviewers normally review without first-impression bias)
23. I'm working on a competing project (research isn't a zero-sum game: if a new area forms, with multiple groups contributing, everyone wins, so it's much better to be inclusive)
24. (and finally, the classic)  It doesn't cite my paper

Many of these boil down to having due respect for the authors and the
work they've put in - they've typically spent between one and ten
person-years on the submitted work, while the reviewer has spent maybe
a day.  Reviewers have to form a judgement, and sometimes will
understand things better than the authors despite the mismatch of
investment, but one should be cautious of assuming that one's first
reaction is necessarily correct. 
One should also be cautious of arguing
that substantially different research or exposition would be needed.
The authors may already have been there and tried that, and in any
case one has to review the paper at hand, not some hypothetical other.
And one should be cautious of
confusing suggestions (or whims!)  and requirements; 
in writing a review, it's important to distinguish the main points
justifying your view from random thoughts and suggestions.

They also highlight the need for reviewers to be dispassionate and
aware of their own biases: to assess as best they can whether the
subject would be best served by accepting the paper, not how much they
personally like it.

Of course, none of them are absolutes - even the last reason
above can be a legitimate complaint in specific circumstances, e.g. if
that uncited paper renders the submitted work moot.


Another bad reason arises during discussion, after the first reviews have been written.  At the end of the process, one has to arrive at accept/reject decisions, but during the process it's all too easy to regard the current scores as an objective assessment, e.g. saying _this is a "B" paper_.  The whole point of the discussion and author response is to consider whether reviews are wrong or miscalibrated - otherwise we'd just order papers by the original scores.


## Good Reasons to Reject Bad PL Papers


On the other side, not all papers are good, unfortunately, and we
shouldn't shy away from rejecting poor-quality work, lest the subject
be contaminated with bogosity.  Returning to the above list, in order of
decreasing importance:

- is the motivation real - does the paper address an important problem?
    (sometimes, simply identifying an important problem is a major contribution)
- would the claims it makes, if true, constitute substantial progress?
- are those claims backed up - is it technically solid?
- is it well-written - enough for readers (with the appropriate background) to understand?

A clear "no" for any of these should rule the paper out from any
serious venue. In more detail:

1. The motivation isn't explained - it doesn't clearly explain why anyone should care
2. The motivational argument is bogus
3. The work is technically correct but pointless  (basically a rephrasing of the above)
4. The claims (presuming they are substantiated) wouldn't significantly advance the subject (it really is a minor increment over previous work)
5. ...or, so far, really insufficiently developed for this venue
6. It really has been done before 
7. The claims are misleading: the work is over-sold and the authors aren't clear about the limitations, or about the relationship to previous work
8. The claims are unsubstantiated: it doesn't give the actual proofs or data, without a good reason why not
9. The claims are unsubstantiated: the evaluation is too limited or too flawed to support the claims
10. It is substantially less rigorous (theoretically or experimentally) than normal practice in the area
11. It's technically wrong (and isn't straightforwardly fixable) 
12. The exposition is so bad that it's hard (even for an informed reader) to understand what the authors have actually done

When arguing that a paper should be rejected, or summarising a PC
decision for the authors, it may be useful to identify exactly which
of these (or other) reasons justify that.


---


The above is about how we review, as individuals, but before that
comes the selection of reviewers, which is typically up to the PC
chair(s) and the process that they and the surrounding organisation set
up, and careful bidding by PC members.  Finding enough reviewers with appropriate expertise and good
judgement for each paper, e.g. aiming for two experts per paper, is
the most important thing we can do to improve our decisions.

(This note is not about process, but I do also want to remark that the
ways we have typically implemented lightweight double-blind
submission, good though that is to avoid first-impression bias, have
also made it harder to do this. Most reviewers are now taken from a relatively small PC or ERC pool, and perhaps with automated assignment, rather than exploiting the knowledge and contacts of the
whole PC to find the best experts.)




