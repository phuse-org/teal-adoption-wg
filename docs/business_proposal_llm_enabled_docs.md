
# Proposal: LLM-Enabled Documentation for teal
PHUSE Working Group – teal Adoption | Funding request for access to an LLM

##  Summary
The teal Adoption Working Group requests PHUSE funding for access to a large language model (LLM) to build and test an LLM-enabled knowledge base for teal. LLMs are increasingly how people access knowledge, and we want teal's documentation and expertise to be easy to use that way. We will investigate and select the most suitable knowledge base approach (for example an "LLM wiki" of linked Markdown files in a format such as Google's Open Knowledge Format, OKF), and publish guidance so users can "bring their own model" (BYOM) to learn about teal and ask questions. This is the working group's first LLM funding request.

Funding requested: [TBC]

##  Background on teal
The open-source teal pharmaverse packages are used across the pharmaceutical industry for the interactive generation and review of TLGs, letting clinicians, statisticians and programmers explore outputs (for example by subgroup or lab parameter) without separate tables for every scenario, and reducing ad hoc programming requests. This PHUSE Working Group brings the community together to share knowledge and enhance the packages, including training materials, performance, new features and a maintenance and governance model.

## What we want to develop
- A teal knowledge base – curated, LLM-readable content covering teal modules, data and filtering, reporting, deployment, common patterns and FAQs, built from public teal and pharmaverse documentation, vignettes and examples. We will keep teal's existing knowledge intact and traceable, with sources recorded.
- Open, portable format – we will evaluate options and pick the best fit (for example an LLM wiki in OKF: Markdown with YAML frontmatter, plus index and log files), favouring plain, version-controlled files that humans and any model can read.
- BYOM guide – short, practical instructions for pointing a user's own model (commercial API, company-approved internal model, or local model) at the knowledge base, including a few example prompts.
- Test set – a set of representative teal questions used to check answer quality, with and without the knowledge base.

## Intended use case and expected benefits
Use case: LLMs are now a common way for people to find and learn things. A new or existing teal user (statistician, programmer, or app developer in a PHUSE member organisation) asks questions such as "How do I add a filter panel to my module?" and gets answers grounded in curated teal documentation, using whichever model they already have access to.

Expected benefits:
- Faster onboarding and lower barrier to teal adoption across the community.
- More consistent, referenced answers than a general-purpose model working from its training data alone.
- Compiled once and reused, so the token cost is paid at build time rather than on every user query.
- No vendor lock-in or platform to host: the output is plain files in GitHub that anyone can fork.
- A reusable pattern and learnings for other PHUSE working groups.

## Scope

In scope: teal, including the core framework and the most used teal.modules.* packages, using public documentation only. No confidential or company data.

Wider use: this is the working group's first LLM funding request, but the approach and learnings could be useful to other PHUSE working groups, and not only for knowledge base creation. We would share what we learn about using LLMs, bring-your-own-model setups and costs.

# Cost breakdown and funding request
[To be completed]

# Ongoing and future costs
- Hosting: none required. The knowledge base lives in a GitHub repository.
- LLM usage by end users: under BYOM, users use their own model access. PHUSE does not carry this cost.
- Maintenance: teal evolves, so pages will need periodic refresh. This will be done by the working group. Some further LLM access may be requested later; this is optional and not part of the current ask.
- Infrastructure: none planned. A hosted chat interface, if ever wanted, would be a separate proposal with its own costs.
- Risks to note: model pricing changes, and LLM answers can be wrong, so human review of generated pages is part of the plan.

# Measuring success
- Answer quality: on the test question set, the share of questions answered correctly with the knowledge base vs. without. Target: [e.g. at least X% improvement].
- Delivery: the knowledge base and BYOM guide published on GitHub within [X] months, passing OKF linting.
- Adoption: repository stars/clones, and number of users who report trying it (e.g. via a short feedback form after PHUSE sessions).
- User feedback: brief survey on whether it helped them learn or use teal.
- Cost: actual LLM usage and spend within the approved funding.
- Reuse: interest from other working groups.
