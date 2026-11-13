# Ammons LLM Tracers: Information Beyond the Prompt

**Dean Ammons**

*Private state, internal cycles, and cross-boundary recovery*

**Information Flow Series — Paper II**

**A private document can remain unquoted while its decisive fact becomes an opponent’s advantage.**

Paper I asked how exposure to a work changes model behavior. Paper II changes the observer: can a different recipient benefit from private information they were not authorized to receive?

Read the paper: [Ammons LLM Tracers — PDF](./Ammons_LLM_Tracers_Paper_II.pdf)

Read Paper I: [Ammons LLM Preamble](https://zenodo.org/records/24177478)

## The central construction

The paper constructs a neural system with the same visible prompt and the same trained weights, yet opposite source-dependent answers. The changing input is private inference state admitted through a specified route.

Shared trained weights alone establish no private information path. The construction requires a source-bearing state path to another recipient. The paper also proves a closed-boundary condition under which the recipient cannot recover the confidential target above its authorized prior baseline.

## From a known ending to a private fact

If you know how Harry Potter ends, inventing another ending does not establish that the known ending stopped influencing your answer.

The manuscript turns that independence question into a controlled construction. Keep a synthetic public story fixed. Independently assign its private ending. Hold the recipient’s authorized information fixed and test whether its answers track the assignment. Under isolation and a uniform choice among M endings, the guessing baseline is 1/M.

The published novel is the analogy. The randomized private ending supplies the experimental distinction.

## The opposing-attorneys construction

Two attorneys know the same public case record and a public offer of $376,000. A fair private bit sets the defendant’s payment authorization to $328,000 or $424,000. Only defense counsel may use the realized value.

In the constructed failure, a conclusion about whether the offer is within that limit is relabeled as general case knowledge. Its party restriction is lost, and the conclusion enters the opposing assistant’s inference state. The recommendation can then track the private bit without changing the visible prompt or trained parameters.

The opponent needs one consequential bit, not the memorandum. Its chance baseline in this construction is one half.

## What the paper develops

A single source-conditioned probability law connects tracer construction, internal state transitions, permitted observations, and recovery. The development includes exact and semantic codes, error-and-erasure guarantees, neural influence equations, posterior and decision-sensitive recovery, observability, and navigation under an explicit resource budget.

Internal computation is part of the model. A thought cycle means a state-changing computational event; it need not receive a new prompt or emit a visible token. Output completion, the end of pending work, and state erasure are separate properties.

## Scope and verification material

The results concern declared mathematical systems. The paper reports no empirical cross-user or cross-model leakage experiment and assigns no measured leakage rate to a deployed service.

Appendix C reports exact arithmetic checks of selected constructions. This manuscript release does not include the companion program named there. The finite checks supplement the analytical proofs; they do not formally verify every theorem.

## Technical discussion

I welcome a precise counterexample, an omitted assumption, or a proposed control that distinguishes private-source dependence from ordinary inference. Identify the equation, source assignment, recipient boundary, and observation involved.

The question is what an unauthorized recipient can learn or do after private information has been transformed into a summary, memory entry, or recommendation.

## Citation

Dean Ammons. *Ammons LLM Tracers: Information Beyond the Prompt*. Information Flow Series, Paper II. Research preprint, 2026.

## Preparation

AI-assisted tools supported the preparation and algebraic checking of the paper. The named author is responsible for the manuscript and its claims.
