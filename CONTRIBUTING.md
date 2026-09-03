# Contributing to the Stateless Society Project

The Stateless Society project is an open RFC project for developing and testing structural specifications for stateless societies.

The project is authored by **Rick Simnett** and published by **The Stateless Co.**

The objective is not ideological agreement.

The objective is to develop specifications capable of surviving clear, adversarial, structural testing.

## Start With the Specification

Before submitting a challenge or proposed change, read the current version of the relevant RFC.

The foundational specification is:

**RFC-0001: A Structural Definition and Classification Model for Stateless Societies**

Its invariant is:

> **Voluntary Order Without Rulers**

Arguments should be evaluated against the definitions, derivations, constraints, and classification logic contained in the specification itself.

---

## Discussions

Use **Discussions** for:

- questions,
- interpretation,
- debate,
- edge cases,
- exploratory criticism,
- competing arguments,
- implementation ideas, and
- proposed spokes or applications of the framework.

Strong disagreement is welcome.

Whenever possible, make arguments concrete and testable.

A disagreement does not automatically constitute a defect in the specification.

---

## Issues

Use **Issues** when you are asserting a specific problem with an RFC.

Three Issue forms are provided.

### Counterexample

Use this when you believe you have identified a classification failure.

The strongest counterexample is either:

> A system with rulers that **PASSES** the classifier.

or:

> A plainly stateless system that necessarily **FAILS** it.

A counterexample should identify the relevant RFC language and demonstrate how the classifier produces the incorrect result.

### Structural / Logical Objection

Use this for:

- contradictions,
- unsupported derivations,
- inconsistent definitions,
- ambiguous classification rules,
- missing structural cases, or
- other internal problems with the model.

### Editorial / Specification Correction

Use this for:

- spelling or grammar,
- formatting,
- broken links or references,
- inconsistent terminology,
- metadata problems, or
- other non-structural corrections.

General philosophical disagreement belongs in Discussions rather than Issues.

---

## Pull Requests

Pull Requests propose exact changes to the canonical repository.

For substantive changes, an Issue should normally identify the problem before a Pull Request proposes the solution.

Small editorial corrections may be submitted directly.

A Pull Request should:

1. identify the RFC and section being changed,
2. link the relevant Issue when one exists,
3. explain the proposed change,
4. explain why the change is necessary, and
5. describe its effect on the specification.

Pull Requests are reviewed before becoming part of the canonical specification.

Acceptance of an Issue does not guarantee acceptance of a particular proposed solution.

---

## Review Standard

The central question is not:

> Do we agree?

It is:

> **Does the objection actually break the model?**

A useful objection should identify a contradiction, classification failure, unsupported derivation, ambiguity, or other reproducible structural problem.

Arguments based on assumptions not contained in the specification should identify those assumptions explicitly.

If an objection exposes a real failure, the specification should change.

If it does not, the specification should not change merely because the conclusion is unpopular or disputed.

---

## Changes to the Canonical Specification

Accepted changes are merged into the protected `main` branch.

The project uses a linear history and squash merging for Pull Requests.

Published versions of the specification are preserved as versioned GitHub Releases.

This allows the current specification to evolve while historical releases remain permanently identifiable.

---

## Licensing of Contributions

Unless explicitly stated otherwise, contributions submitted to this repository are provided under the same **Creative Commons Attribution 4.0 International (CC BY 4.0)** license that applies to the repository's licensed specification materials.

By submitting a contribution, you represent that you have the right to submit it under those terms.

See [LICENSE.md](LICENSE.md) for license information.

---

## Debate the Model, Not the Person

Criticism can be aggressive.

Personal attacks are not useful.

Attack assumptions.  
Attack definitions.  
Attack derivations.  
Attack classifications.  
Find contradictions.  
Find failure modes.

Make the argument testable.

---

## Read It. Challenge It. Help Refine It.

The Stateless Society Specification is intended to be challenged.

If you can break it, show how.

If the challenge holds, the specification should become stronger because of it.
