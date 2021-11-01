# Bad Reasons to Reject Good Papers (and v.v.)

## or, Am I Reviewer #2 ?

## On reviewing in Computer Science, especially around PL-related topics (programming languages, semantics, verification)

## Peter Sewell, 2021-11-01

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
even have seen all the submitted titles and abstracts.  Instead, we
load all that responsibility for maintaining review quality and common
standards on our PC chairs - a nigh-on impossible task across hundreds
of on-line discussions.

This note tries to spell out some of what constitutes good reviewing,
to refresh and provide a little push towards a better consensus.  It's
focussed on PL-related research (programming languages, semantics, and
verification), but much is more generally applicable.  I started these
lists as POPL PC Chair in 2014, with another version 
on [twitter](https://twitter.com/peter_sewell_/status/1442750114196492288).

As reviewers, what do we have to decide?  Fundamentally, whether
publishing the paper will advance the subject in some substantial way.
In more detail:

- is the motivation real - does the paper address an important problem?
- would the claims it makes constitute substantial progress?
- are those claims backed up - is it technically solid?
- is it well-written - enough for readers (with the appropriate background) to understand?

Then, as our venues are typically competitive, we have to weigh the
paper against other submissions.


## Bad Reasons to Reject Good Papers

Reviewing is essentially a judgement call.  We discuss our review
processes at great length, and those processes do matter - we've tuned
them (and I think in many ways improved them) over the years - but the
most important thing is getting informed judgements from a suitably
expert and sensible group of people.  So this note is not about
process. Instead, we identify some of the bad forms of argument that
one sees again and again.  If one sees one of these, or (especially!)
if one finds oneself writing one, an alarm bell should ring...

1. I could have done this better, if only I'd got round to it
2. I can imagine some quite different research that I'd prefer 
3. I can imagine some quite different exposition that I'd prefer (suggesting actionable improvements is useful, of course)
4. It's not self-contained / accessible to me, because I don't know the work it builds on (even though it recaps as much as possible)
5. It's not self-contained, because this project is too big for all the details to fit in the page limit
6. I want more examples / discussion (fitting into the page limit by magic)
7. I want extra evaluation (even though it does a decent job to support the claims) 
8. I just wasn't excited by it (even though it's a clear advance on an important problem)   (our ABCD identify-the-champion scoring is good in many ways, but it fails for papers that hit this)
9. I'm assessing this as if it was about X, even though it's actually about Y
10. I'm assessing this as if it was a paper of kind A, even though it's actually of kind B  (PL spans lots of different kinds of papers, with different values and criteria)
11. It's about language design (bonus points if this is PLDI)
12. It's about the semantics of actual languages, which makes it complicated (bonus points if this is POPL)
13. They didn't mechanise all the proofs  (though they didn't claim that they did)
14. A previous paper claimed to do this (though it doesn't really subsume this, or didn't appear before this submission)
15. It could do with another pass (and the authors will thank us for rejecting it)  (very occasionally this is eventually true, but there's a big cost, especially to the careers of junior authors)
16. It presents a big project, not a single clever/cute idea that can be fully explained in a few pages
17. The idea here is too simple (even though it's very useful, and no-one fleshed it out and published it before) 
18. It's incremental w.r.t. previous work (even though it's a _big_ increment - most research is advancing previous work)   
19. This feels more like a paper for venue X (even though it could perfectly well fit here) (usually a PC chair will have to desk-reject just a couple of really out-of-scope papers)
20. This should be a journal paper instead (for good and ill, PL is based on conference publication)
21. The authors put a version on their web page / on arxiv / as a techreport  (that's explicitly allowed by our normal lightweight double-blind (LDB) policy, as otherwise normal scientific communication would be inhibited; the point of LDB is just to let reviewers normally review without first-impression bias)
22. I'm secretly working on a competing project (research isn't a zero-sum game: if a new area forms, with multiple groups contributing, everyone wins, so it's much better to be inclusive)
23. (and finally, the classic)  It doesn't cite my paper

Many of these boil down to having due respect for the authors and the
work they've put in.  Remember, they've typically spent between one
and ten person-years on this, while the reviewer has spent maybe a
day.  We're not awarding prizes for effort, and sometimes a reviewer
will understand things better, but one should be wary as a reviewer of
trying to require substantially different research or exposition.


## Good Reasons to Reject Bad PL Papers


On the other side, not all papers are good, unfortunately, and we
shouldn't shy away from rejecting poor-quality work, lest the subject
be contaminated by bogosity.  Returning to the above list, in order of
decreasing importance:

- is the motivation real - does the paper address an important problem?
- would the claims it makes constitute substantial progress?
- are those claims backed up - is it technically solid?
- is it well-written - enough for readers (with the appropriate background) to understand?

A clear "no" for any of these should rule the paper out from any
serious venue. In more detail:

i. The motivation isn't explained - it doesn't clearly explain why anyone should care
ii. The motivational argument is bogus
iii. The work is technically correct but pointless 
iv. It's technically wrong (and isn't straightforwardly fixable)
v. The claims are misleading: the work is over-sold and the authors aren't clear about the limitations
vi. The claims are unsubstantiated: it doesn't give the actual proofs or data, without a good reason why not
vii. The claims are unsubstantiated: the evaluation is too limited or too flawed to support the claims
viii. The exposition is so bad that it's hard (even for an informed reader) to understand what the authors have actually done
ix. It doesn't significantly advance the subject (it really is a minor increment over previous work)
x. It really has been done before 
xi. It is a good direction, but it's really insufficiently developed for this venue
xii. It is substantially less rigorous (theoretically or experimentally) than normal practice in the area

When arguing that a paper should be rejected, or summarising a PC
decision for the authors, it may be useful to identify exactly which
of these (or other) reasons justify that.


----------------------


While this is not about process, I do want to remark that the ways we
have typically implemented lightweight double-blind submission, good
though that is to avoid first-impression bias, have also made it
harder to find enough reviewers with expertise and good judgement,
e.g. aiming for two experts per paper. Most reviewers are now taken
from a PC or ERC pool, rather than exploiting the knowledge and
contacts of the whole PC to find the best experts.

