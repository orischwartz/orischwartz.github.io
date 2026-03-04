## Google Rewrites Applications Every Few Years. Can You?

_March 3, 2026_

A quarter-century ago Joel Spolsky [published](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/) one of the most popular and frequently cited essays on his (excellent) blog. He describes Netscape's decision to rewrite their browser from scratch. It took 3 years, caused their product to stagnate, and cemented Microsoft's dominance in the nascent browser market. He calls it the "single worst strategic mistake" a software company can make.

This essay is frequently revisited. The rewrite was actually important because it produced the Gecko engine (Firefox), broke Microsoft's stranglehold, and became an important part of a more competitive browser landscape.

There are plenty of examples of both failed and successful software rewrites. Like everything else in tech, the answer to "should we do a rewrite" is: [it depends](https://convincedcoder.com/2018/08/31/It-depends/).

We all understand the risks of [second system syndrome](https://en.wikipedia.org/wiki/Second-system_effect). There are [patterns](https://martinfowler.com/bliki/StranglerFigApplication.html) for dealing with legacy applications. Yet total rewrites can be good if you can afford it.

Google famously rewrites most software ["every few years"](https://arxiv.org/pdf/1702.01715). Mere mortals would love to do the same but that would [be a mistake](https://skamille.medium.com/avoiding-the-rewrite-trap-b1283b8dd39e) for many teams. Google has armies of junior and mid-level engineers to throw at the task and you do not.

Or maybe now you do.

I [don't believe](https://orischwartz.com/posts/even-with-fleet-of-coding-agents.html) AI coding agents are going to replace entire software businesses or good engineers any time soon. But they are indisputably valuable under the right conditions:

- New/greenfield projects work better than legacy codebases.
- Applications built on modern, popular stacks are better than old ones because they're over-represented in the training data (e.g., typescript/react/tailwind).
- Small applications are easier to work with than larger ones.

In other words, better for new projects than the legacy codebase you wanted to replace 10 years ago. (Try asking your favorite coding agent to modify an Ant build script from 2004. It will fail in creative ways.)

But there is one really valuable use of coding agents for legacy applications: rewrites.

AI is very effective at extracting the meaning out of your 20-year-old JDK 1.4 code and spitting out idiomatic typescript or kotlin equivalents. The original source code [acts like an extremely detailed prompt](https://x.com/karpathy/status/2023476423055601903?s=20). And emitting the new, modern code is a strength of LLMs.

You would need senior-ish engineers to drive the process and all the same business risks would still apply. But what was previously an insurmountable, tedious task suddenly becomes possible.

If you have a comprehensive test suite or a spec, you can work miracles like [reimplementing NextJS](https://blog.cloudflare.com/vinext/) in a week (for actual, real use, not [PR stunt slop use](https://fortune.com/2026/01/23/cursor-built-web-browser-with-swarm-ai-agents-powered-openai/)).

It is becoming more affordable to modernize your old code.
