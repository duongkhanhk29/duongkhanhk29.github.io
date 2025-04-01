---
title: "Formal Statements in Economic Articles"
date: 2025-03-25
permalink: /posts/formal-statements-in-economic-articles/
excerpt: "A detailed comparison of the different formal statements (e.g., Definitions, Axioms, Lemmas) commonly used in economic research, highlighting their purpose, role in proofs, and importance in theory."
tags:
  - Economic Theory
  - Formal Logic
  - Mathematical Economics
---

In economics research, formal mathematical statements are used to clearly define concepts, state assumptions, and prove results. This document provides an overview of the main types of formal statements used in academic economic articles, followed by examples.

## Types of Formal Statements

### Definition
A definition introduces a precise meaning for a concept. In economics, definitions are crucial because small differences in wording can lead to different theoretical implications.

> **Definition: Risk Aversion**  
A utility function $u(\cdot)$ exhibits risk aversion if it is concave, i.e., $u''(x) < 0$ for all $x$.

### Axiom
An axiom is a fundamental assumption that is taken as given without proof. Economic models often begin with axioms that describe rational behavior.

> **Axiom: Independence Axiom**  
If $A \succ B$, then for any probability $p$, a lottery that gives $A$ with probability $p$ and $C$ otherwise is preferred to a lottery that gives $B$ with probability $p$ and $C$ otherwise.

### Lemma
A lemma is an auxiliary result used to prove a more important result, such as a theorem or proposition.

> **Lemma**  
If preferences are continuous and strictly convex, then the demand function is single-valued.

> *Proof:* See Appendix A.

### Proposition
A proposition is a mathematical result that is true but not as fundamental as a theorem. Propositions often describe properties of equilibrium or optimization results.

> **Proposition**  
If firms are price-takers in a perfectly competitive market, then the equilibrium price equals marginal cost.

> *Proof:* See Appendix B.

### Theorem
A theorem is a major result that is rigorously proven using axioms, lemmas, and previously established results.

> **Theorem: First Welfare Theorem**  
In a competitive equilibrium, the allocation of resources is Pareto efficient.

> *Proof:* See Mas-Colell et al. (1995), Chapter 16.

### Corollary
A corollary is a direct consequence of a theorem or proposition that requires little additional proof.

> **Corollary**  
If preferences are homothetic, then income expansion paths are straight lines.

> *Proof:* Follows directly from Theorem 2.

### Claim
A claim is a smaller result within a proof that is used to simplify the argument.

> **Claim**  
The function $f(x)$ is increasing for $x > 0$.

> *Proof:* Immediate from the first derivative.

### Remark
A remark provides additional insights or interpretations of a result.

> **Remark**  
The equilibrium condition in Proposition 2 is analogous to the Nash equilibrium concept in game theory.

### Example and Counterexample
An example illustrates a concept or result, while a **counterexample** shows a situation where a proposed statement fails.

> **Example**  
Consider a firm facing a linear demand curve $P = a - bQ$. The profit-maximizing quantity follows from the first-order condition.

### Assumption
An assumption is an explicit condition imposed on a model to structure its conclusions.

> **Assumption**  
Firms maximize expected profit subject to a convex cost function.

## Comparison of Formal Statements in Economics Articles

| **Formal Statement** | **Purpose** | **Role in Proofs** | **Dependence on Assumptions** | **Importance in Theory** |
|----------------------|-------------|--------------------|-----------------------------|--------------------------|
| **Definition**        | Provides a precise meaning for a concept. | Not part of a proof, but necessary for clarity. | Independent of assumptions; sets the foundation. | Essential for consistency and rigor in theory. |
| **Axiom**             | States fundamental assumptions taken as given. | Forms the basis of logical reasoning. | Assumptions are intrinsic and not derived. | Critical, as they shape the structure of economic models. |
| **Assumption**        | Specifies conditions imposed on a model. | Used to simplify or structure a proof. | Dependent on modeling choices; can be relaxed or tested. | Important for tractability and applicability of results. |
| **Lemma**             | Provides an intermediate result used in a larger proof. | A stepping stone to proving propositions or theorems. | Usually follows from assumptions and basic results. | Useful but not necessarily significant outside the proof. |
| **Proposition**       | States a true result, often related to equilibrium properties. | Can be proven directly or derived from lemmas. | Derived from assumptions and earlier results. | Provides useful but not fundamental insights. |
| **Theorem**           | Establishes a fundamental result with broad implications. | The highest level of formal proof in a paper. | Strongly dependent on model assumptions. | Central to economic theory and often widely cited. |
| **Corollary**         | A direct consequence of a theorem or proposition. | Follows immediately from a higher-level result. | Inherits assumptions from the theorem or proposition. | Often useful but not as important as the theorem itself. |
| **Claim**             | A small result within a proof. | Helps break down complex proofs. | Often context-specific and dependent on previous results. | Minor but useful for structuring arguments. |
| **Remark**            | Provides additional insights or explanations. | Not part of a formal proof but aids understanding. | Can discuss implications of assumptions but does not depend on them. | Helps clarify results but is not central to theory. |
| **Example**           | Illustrates a concept, result, or assumption. | Used to validate or counter claims. | May depend on assumptions but is not a formal statement. | Helpful for intuition but not essential to proofs. |
