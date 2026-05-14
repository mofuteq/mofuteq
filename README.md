# mofuteq

I build AI agents by asking an old question: **whose agent are they?**

I use coding agents every day, from the principal side of the relationship. What I think AI agents should be — and what they should refuse to do — comes from that experience, then from law, economics, and literature.

You learn what a good agent is by being responsible for what a bad one produces.

The repositories below are small, opinionated answers to the question of *for whom* an AI agent acts. Each has a defined principal, a bounded scope, and a refusal to substitute its judgment for the principal's.

## Current work

### [contract-question-agent](https://github.com/mofuteq/contract-question-agent)

An agent for the contract reviewer, not the drafter.

It does not decide whether a contract is acceptable. It returns the questions a well-informed reviewer should ask before making that judgment.

**Principal:** contract reviewer  
**Artifact:** verification questions  
**Boundary:** no verdict

### [trend-to-rule](https://github.com/mofuteq/trend-to-rule)

An agent for the reader trying to make sense of a noisy domain.

It does not recommend what to do. It extracts shared structure from canonical and emerging signals, then returns an interpretable rule — a reference frame in the form of “when X, signal Y.”

**Principal:** domain reader / decision-maker  
**Artifact:** interpreted rules  
**Boundary:** no prescription

### [Mia StudyWorks](https://note.com/mia_studyworks)

A learning-design label for exploring the same question in self-directed study.

A study tool should not pretend to be the learner. It should structure attention, reduce friction, and help the learner see what to practice next.

**Principal:** learner  
**Artifact:** study frames, practice scaffolds, metacognitive prompts  
**Boundary:** no substitution for learning

## Engineering posture

- **LLMs as controlled transformation components**, not the center of the system.
- **Structure as engineering substrate**, not the surface the user reads.
- **Decision-grade artifacts over confident answers**: questions, rules, traceable evidence, and reference frames.
- **Explicit state machines over open-ended loops** when reproducibility, attribution, and debugging matter.
- **Abstention as a feature**: a useful agent must know when not to answer.
- **No-disclaimer-by-design**: the agent avoids judgments that would require warning users not to trust them.
- **Provider contracts over provider lock-in**: typed boundaries, observable workflows, and replaceable infrastructure.
- **AI tools as principal-bounded delegation**: I use coding agents daily, and the boundaries I demand from them are the boundaries I build into mine.

## Next

I am working toward Georgia Tech OMSCS to restate these commitments in more formal ML and systems language: calibrated abstention, frame-lending representations, controlled transformation pipelines, and agent workflows with explicit decision boundaries.

## Background

Applied AI engineering in domain-heavy contexts. The thesis above is what I have come to think after trying to make LLMs useful inside real workflows without making them the center of those workflows.

I am interested in where AI agents should stop — and how that line can be enforced in code.