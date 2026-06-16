## There's more than one way to be a 10x engineer

_June 16, 2026_

If you work in tech long enough you will hear about a mythical creature that is 10x better than their peers.

The industry is obsessed with this idea. Why? Have you ever heard of a 10x lawyer, doctor, or accountant? Even in sports where generational talents are universally acknowledged, we never refer to them as 10x. What is it about software that makes us believe in this idea?

The term is brandished by both VCs and engineers in the trenches so it can't be dismissed as out of touch.

Paul Bucheit, the early Google engineer who built the first version of Gmail in one day (10x alert!) recently told the story of Bret Taylor [rewriting the Google Maps codebase in a single weekend](https://open.spotify.com/episode/0oRAHcP9g41jcEzpDtOa4b):

> It had way too much XML bloat. Anyway, Bret got frustrated with this, and over a weekend, rewrote their entire JavaScript for Google Maps. And he made it... if I remember correctly, like a third the size and 10 times as fast. They show up on Monday and he's just completely replaced all of the code. That's the kind of engineer Bret... and the thing is, it isn't bad code. Like, it isn't like sloppy stuff. He'll crank out really high quality code very quickly. So he's... he's like... **he's not even a 10x engineer. He's like, 100x, or 1,000x engineer**. He's just really good.

We've all seen heroic efforts like this. But software engineering is a team sport and large changes/rewrites/refactors can only be labeled as successful if they increase the productivity of the team.

Your work needs to unlock productivity or capabilities that weren't possible before.

Does rewriting Google Maps to be faster and smaller qualify? If it allowed the team to ship something better or sooner, then yes. You'd have to ask them to know for sure (I'm pretty sure it did).

So that's one way to make a 10x contribution: stay up all weekend churning out large amounts of high quality code. Most people cannot do this but it is possible.

There's another way to make outsize contributions: by exercising good judgement and saving your team a lot of wasted effort and operational headaches.

Taylor and Bucheit were cofounders of FriendFeed, a startup that Facebook acquired in 2009 (partly to get Taylor, who became CTO).

Iteration speed is always important but for startups it is critical. One way to stay flexible and move quickly is with a schema-less database (NoSQL). But this technology didn't exist (or was [unstable](https://couchdb.apache.org)) when FriendFeed was founded in 2007.

So [FriendFeed repurposed the dependable MySQL](https://backchannel.org/blog/friendfeed-schemaless-mysql) relational database into a schema-less NoSQL db. It allowed them to add new features quickly, with no index or schema modifications, while scaling to 250M rows (this was a lot back then). And they got all the stability and tooling benefits of running on a mature ([boring](https://boringtechnology.club/)) technology.

10x decisions often have this shape: repurpose something that already exists for a new use. Bucheit was able to [build the first prototype of gmail in "one day"](https://www.youtube.com/watch?v=xsxM0YIsgx4) because he adapted his email to fit into an existing project that made usenet discussions searchable.

A smart design choice early can save your team months or even years of wasted effort. It can make the difference between success and failure. The potential impact is limitless. It's analogous to the way Jeff Bezos [describes business outcomes](https://www.goodreads.com/quotes/10886669-we-all-know-that-if-you-swing-for-the-fences):

> We all know that if you swing for the fences, you're going to strike out a lot, but you're also going to hit some home runs. The difference between baseball and business, however, is that baseball has a truncated outcome distribution. When you swing, no matter how well you connect with the ball, the most runs you can get is four. In business, every once in a while, when you step up to the plate, you can score 1,000 runs.

This is a realistic way for engineers to make 10x contributions: improve your business's chances of success.
