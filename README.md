# The Riemann Hypothesis: A Reading List

A collection of explainers, proof resources, and profiles of **Levent Alpöge**
and **Alessandro Maria Masullo**, whose separate approaches to the Riemann
Hypothesis became public on November 20, 2026. Start with the background videos,
explore each argument and its review, or get to know the mathematicians behind them.

**Updated November 21, 2026.** The
[Lean and Mathlib communities](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/)
have certified Alpöge's formal proof of the Riemann Hypothesis, released as roughly
17 million lines of Lean code. Lean is a programming language and proof assistant
for checking mathematical arguments. The verified generalization covers
**Dirichlet L-functions**, as detailed in
[Andrew Sutherland's report](https://math.mit.edu/~drew/grh/).
Work to explain and simplify the mathematics continues.

Masullo's proposed proof of the **Generalized Riemann Hypothesis (GRH)** was
developed without AI, according to
[Ravi Vakil's announcement](https://math216.wordpress.com/2026/11/20/hurried-announcement-alessandro-masullo-grh/).
Vakil's subsequent update reports problems in the draft; it remains under review,
with a community effort to formalize parts of the argument in Lean.

- [Background](#background)
- [About Lean](#about-lean)
- [Alpöge: the proof and its verification](#alpöge-the-proof-and-its-verification)
- [About Levent Alpöge](#about-levent-alpöge)
- [Masullo: the proposed proof and formalization](#masullo-the-proposed-proof-and-formalization)
- [About Alessandro Maria Masullo](#about-alessandro-maria-masullo)
- [About Terence Tao](#about-terence-tao)

## Background

These introductions explain the problem and its significance; the videos predate
the November 2026 announcement.

- **[Riemann Hypothesis — Wikipedia](https://en.wikipedia.org/wiki/Riemann_hypothesis)**\
  A reference overview of the zeta function, the hypothesis's history, its connection
  to prime numbers, and related generalizations.

- **[The Riemann Hypothesis, Explained — Quanta Magazine](https://www.youtube.com/watch?v=zlm1aajH6gY)** · Video\
  Alex Kontorovich introduces the problem and why it matters, with animated
  explanations of the patterns behind prime numbers.

- **[But What Is the Riemann Zeta Function? — 3Blue1Brown](https://www.youtube.com/watch?v=sD0NjbwqlYw)** · Video\
  A visual introduction to the zeta function and analytic continuation, building
  intuition for the function at the heart of the hypothesis.

- **[Riemann Hypothesis — Numberphile](https://www.youtube.com/watch?v=d6c6uIyieoo)** · Video\
  Edward Frenkel introduces the hypothesis and its place among mathematics' most
  celebrated problems.

- **[The Key to the Riemann Hypothesis — Numberphile](https://www.youtube.com/watch?v=VTveQ1ndH1c)** · Video\
  Jon Keating explores L-functions and why this broader family of functions could
  help illuminate the Riemann Hypothesis.

## About Lean

- **[Lean (Proof Assistant) — Wikipedia](https://en.wikipedia.org/wiki/Lean_(proof_assistant))** · Overview\
  An introduction to Lean's history, mathematical foundations, libraries, and
  uses in formalizing mathematics and verifying software.

- **[Lean — Official Website](https://lean-lang.org/)** · Getting started\
  The project's home page, with examples, learning resources, documentation,
  and links to its mathematical library and community.

## Alpöge: the proof and its verification

### Announcement and independent checks

- **[Alpöge's Original Announcement](https://alpo.ge/remark.pdf)** · PDF\
  His account of discovering the argument with Claude, its mathematical ideas,
  and links to the Lean proof archive, split into 14 compressed parts.

- **[Lean Verification of the Riemann Hypothesis](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/)** · Joint statement\
  The Lean and Mathlib communities certify the formal statement and proof,
  explaining the compilation, statement comparison, and independent proof checks.

- **[Verification Files — Andrew Sutherland, MIT](https://math.mit.edu/~drew/grh/)** · Technical report\
  Detailed results, logs, and theorem statements for independent checks of the
  Lean proof, including its scope for Dirichlet L-functions.

### Explanations and discussion

- **[Proof Guide and Verification — Michael Rubinstein, Waterloo](https://www.math.uwaterloo.ca/~mrubinst/alpoge_claude_grh/)** · Research resources\
  Independent verification results and a working exposition for the Riemann zeta
  function. The exposition still takes its central inequality from the Lean proof.

- **[A Map, Guide, and Record of Checks — riemann-rev](https://nasqret.github.io/riemann-rev/)** · Interactive guide\
  An independent reading project with a proof atlas, mathematical explanations,
  links to Lean source, and a dashboard tracking verification results.

- **[Discussion: Alpöge Proves the Riemann Hypothesis — Lean Zulip](https://leanprover.zulipchat.com/#narrow/channel/113488-general/topic/Discussion.3A.20Alp.C3.B6ge.20Proves.20the.20Riemann.20Hypothesis/with/642477265)** · Community discussion\
  The Lean community's discussion thread about the proof and ongoing work to
  examine it. Requires a browser with JavaScript enabled.

- **[Alpöge's Claude-Assisted Proof Verified in Lean — Kingy AI](https://kingy.ai/blog/levent-alpoge-claude-riemann-hypothesis-proof/)** · News explainer\
  An accessible overview of the announcement, Claude's role, the published
  archive, and what the independent verification establishes.

- **[Alpöge's Riemann Hypothesis Proof: Claimed vs. Verified — explainx.ai](https://explainx.ai/blog/levent-alpoge-anthropic-riemann-hypothesis-claude-lean-proof-claimed-vs-verified-2026)** · News explainer\
  A dated account of the announcement and successive verification results,
  explaining statement matching, proof checkers, and the remaining review process.

## About Levent Alpöge

- **[Levent Alpöge's Personal Website](https://alpo.ge)** · Primary source\
  His introduction, research papers, theses, CV, and links to coverage of his
  work in number theory.

- **[Levent Alpöge — LinkedIn](https://www.linkedin.com/in/levent-alp%C3%B6ge-b6426319/)** · Professional profile\
  His LinkedIn profile; viewing the full profile may require signing in.

- **[Levent Alpöge — Wikipedia](https://en.wikipedia.org/wiki/Levent_Alp%C3%B6ge)** · Biography\
  An overview of his education, career, mathematical research, awards, and work
  with AI, with references for further reading.

- **[Who Is Levent Alpöge? — Nacionale](https://www.nacionale.com/en/articles/who-is-levent-alpoge-anthropic-mathematician-riemann-hypothesis-claude-proof)** · Profile\
  A profile tracing his academic training, earlier number theory results, move
  to Anthropic, and the context of the Riemann announcement.

- **[Who Is Levent Alpöge? — Clarín](https://www.clarin.com/us-news/who-is-levent-alpoge-the-anthropic-mathematician-who-claims-solved-the-riemann-hypothesis-with-claude_0_2WdGvYKBVM.html)** · Profile\
  A profile of his education, research career, and collaboration with Claude.

- **[Who Is Levent Alpöge? | Mint](https://www.livemint.com/ai/artificial-intelligence/who-is-levent-alp-ge-meet-anthropic-s-technical-staff-member-who-solved-the-riemann-hypothesis-with-ai-tool-claude-11795321945858.html)** · Profile\
  A profile covering his education, academic awards, research, and move to
  Anthropic, alongside an account of the Claude-assisted proof announcement.

## Masullo: the proposed proof and formalization

- **[Hurried Announcement: Alessandro Masullo GRH — Ravi Vakil](https://math216.wordpress.com/2026/11/20/hurried-announcement-alessandro-masullo-grh/)** · Primary announcement\
  Introduces Masullo's human-derived argument, links to *The Music of the Primes*,
  and describes Brian Conrad's feedback. An update reports problems that must be
  resolved before the proposed proof can be accepted.

- **[Masullo's GRH Draft: Claimed vs. Verified — explainx.ai](https://explainx.ai/blog/alessandro-masullo-grh-human-proof-claimed-vs-verified-november-2026)** · News explainer\
  Summarizes the draft's release, Masullo's background, and subsequent reports
  of gaps and revisions, with context on how the argument is being assessed.

- **[Formalising Masullo's Proof of GRH — Lean Zulip](https://leanprover.zulipchat.com/#narrow/channel/113488-general/topic/Formalising.20Masullo.27s.20proof.20of.20GRH/with/642566278)** · Community discussion\
  A discussion thread for efforts to translate the manuscript into Lean and
  examine its arguments. Requires a browser with JavaScript enabled.

- **[RiemannMasullo — Lean Formalization Project](https://github.com/mccorvie/riemann-masullo)** · Source repository\
  An ongoing formalization with a progress map, open proof tasks, and errata.
  Work currently covers prerequisites and early chapters; the project has not
  verified the manuscript's main theorem or GRH.

## About Alessandro Maria Masullo

- **[Alessandro M. Masullo — LinkedIn](https://www.linkedin.com/in/alessandro-m-masullo-459094113/)** · Professional profile\
  His LinkedIn profile; viewing the full profile may require signing in.

- **[Arithmetic Deformations of Crystalline Cohomology — Stanford Digital Repository](https://purl.stanford.edu/kp533pz4708)** · Dissertation record\
  Stanford's record of Masullo's doctoral thesis, with its abstract, dissertation
  access, and academic advisors, including degree supervisor Brian Conrad.

- **[Who Is Alessandro Masullo? — Nacionale](https://www.nacionale.com/en/articles/who-is-alessandro-masullo-all-human-riemann-hypothesis-proof-grh-ravi-vakil-stanford)** · Profile\
  A profile of his Stanford training and research background, the release of
  his GRH draft, and the questions raised during its review.

## About Terence Tao

Terence Tao, a Fields Medalist and a leading voice on AI in mathematics, offers
valuable context for these developments. His earlier, tentative suggestion of
human–AI progress around 2050 makes a striking companion to the November 2026
announcement. These interviews are a reminder of how difficult it is to forecast
the pace of AI-assisted discovery, even with exceptional mathematical expertise.
His emphasis on collaboration also anticipated a central feature of Alpöge's work.

- **[Terence Tao — Wikipedia](https://en.wikipedia.org/wiki/Terence_Tao)** · Biography\
  An overview of his life, mathematical contributions, major awards, and views
  on AI and the formalization of mathematics.

- **[Euler, Navier–Stokes, and the Generalized Riemann Hypothesis — Tao's Blog](https://terrytao.wordpress.com/2026/11/20/unforced-euler-singularity-unforced-navier-stokes-singularity-and-the-generalized-riemann-hypothesis/)** · Expert commentary\
  His November 20 account of three AI-assisted developments, including Alpöge's
  Lean proof, with links to verification efforts and observations on the work
  needed to understand the mathematics.

- **[No More Heroes: Terence Tao on AI — Numberphile](https://www.youtube.com/watch?v=bAnwMdfcMVw)** · Full interview\
  The October 2026 conversation behind the 2050 remark, discussing AI-generated
  proofs and mathematical understanding. Tao tentatively imagines further progress
  through humans and AI around 2050; this is speculation rather than a firm deadline.

- **[Tao's Earlier Outlook and the November Announcement — Some Conditions Apply](https://www.youtube.com/shorts/5OIkY1yTQOQ)** · Short video\
  A retrospective juxtaposing Tao's earlier remarks with the subsequent proof
  announcement. The full Numberphile interview above provides the broader context.

- **[Why the Riemann Hypothesis Is So Difficult — Lex Clips](https://www.youtube.com/watch?v=FCrtYilXpk0)** · Interview excerpt\
  Tao explains the obstacles facing familiar proof techniques and his uncertainty
  about when the problem would be solved, in a June 2025 conversation with Lex Fridman.

- **[Will AI Prove the Riemann Hypothesis Without Understanding It? — Dwarkesh Clips](https://www.youtube.com/watch?v=PU1LMVGcyXA)** · Interview excerpt\
  A discussion of whether a formal proof would yield human insight, how a large
  Lean proof might be interpreted, and the promise of humans working with powerful AI tools.
