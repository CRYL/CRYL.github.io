---
title: 'Far from any separable and maximally entangled states'
date: 2023-03-11
permalink: /posts/2023/03/
tags:
  - entanglement
---

We show that there is some entanglement witness that cannot witness any
maximally entangled states. At the first sight it seems to be the
opposite: the maximally entangled states contains the 'most'
entanglement in some sense, so at least one of them should be detected
by a fixed entanglement witness. Unfortunately it does not hold.

Let $\operatorname{MAXE}$ be the set of all maximally entangled state,
$\operatorname{SEP}$ be the set of separable states. We first show that
the convex hull of $\operatorname{MAXE}\cup\operatorname{SEP}$ is
closed.

The convex hull $$\begin{aligned}
    \operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}:=\{\rho|\rho=\sum_jp_j\rho_j,\rho_j\in\operatorname{MAXE}\cup\operatorname{SEP},p_j\ge0,\sum_jp_j=1\}\end{aligned}$$
is closed.

**Proof ** Note that $\operatorname{MAXE}$ is an orbit of the group
action the unitary group $U(d)$ which is compact, so
$\operatorname{MAXE}$ is compact. It is well-known that
$\operatorname{SEP}$ is compact. Therefore
$\operatorname{MAXE}\cup\operatorname{SEP}$ is compact. Since
$\operatorname{MAXE}\cup\operatorname{SEP}\subseteq\mathcal{B}(\mathbb{C}^d\otimes\mathbb{C}^d)$
is finite-dimensional, its convex hull is also compact, thus closed.
$\blacksquare$

We can also show that any partially entangled pure state
$\sigma=| \psi\rangle\!\langle \psi |, \ket{\psi}\notin\operatorname{MAXE}$
is not in the convex hull: note that $\sigma$ is an extreme point in the
set of all density matrices. Suppose for contradiction that
$\sigma\in\operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}$,
then it must be also extreme in
$\operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}$. So it
must be either maximally entangled $\ket{\psi}\in\operatorname{MAXE}$ or
separable $\ket{\psi}=\ket{\psi}_A\otimes\ket{\psi}_B$, a contradiction.

So we have a closed convex set
$\operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}$, and a
point $\sigma$ which is not in the set. By Hahn--Banach theorem, there
is a linear functional denoted by hermitian operator $H$ such that
$\operatorname{Tr}[H\sigma]<0$ and $\operatorname{Tr}[H\rho]\ge0$ for
all
$\rho\in\operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}$.
Obviously
$\operatorname{SEP}\subseteq\operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}$,
so $H$ separates $\operatorname{SEP}$ and $\sigma$, therefore is an
entanglement witness. Also,
$\operatorname{MAXE}\subseteq\operatorname{cov}\{\operatorname{MAXE}\cup\operatorname{SEP}\}$,
so $H$ cannot witness any maximally entangled states.

Acknowledgement {#acknowledgement .unnumbered}
===============

We thank Marek Miller for valuable discussion.