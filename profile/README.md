# Repetition Algebra (rep-algebra)

Welcome to **rep-algebra**, an organization dedicated to the study, formalization, and practical application of algebraic structures for repeated patterns in sequences.

## Overview

The origin of this project dates back to my undergraduate thesis (University of Buenos Aires, 2002), where I proposed **AS2**, a data structure and algebraic framework for understanding **supermaximal repeats** in sets of dependent sequences. While string algorithms have evolved significantly over the last decades—suffix arrays, suffix automata, FM-indexes, BWT-based methods, streaming algorithms—one aspect has remained largely unexplored:

> **No formal algebra has ever been proposed to describe, classify, or test the behavior of string algorithms on repeated patterns.**

The **Repetition Algebra** introduced in that thesis provides a structured, mathematical way to reason about repetitions, maximality, factor expansion, and structural relationships between repeated substrings. The idea remained dormant for years, but recent needs in streaming systems, event processing, and log analysis make it more relevant than ever.

## Mission

The goal of this organization is to **revive, modernize, and extend** the Repetition Algebra into a mature theoretical and practical tool for contemporary problems involving repeated patterns.

Specifically, we aim to:

### 1. **Formally validate and test existing string algorithms**

Many algorithms for repeat detection, maximal repeats, suffix structures, and compression operate on implicit assumptions about the structure of repetitions.
Repetition Algebra offers a way to:

* characterize repetitions algebraically,
* compare algorithms against algebraic expectations,
* and design formal test cases that reflect structural edge conditions.

### 2. **Open new directions in theoretical computer science**

By extending the algebra to incorporate:

* diffuse repetitions,
* composite repetitions,
* scalable repetition structures,
* and streaming-based variants,

we hope to define **new families of problems and algorithms**, grounded in formal algebraic properties.

### 3. **Apply repetition algebra to modern real-world data**

Contemporary systems generate massive amounts of sequential data:

* event logs
* machine execution traces
* system monitoring streams
* sensor sequences
* biological signals
* stock and trading streams

Many of these sequences contain **repetitions with structure**, not just raw duplicates.
Our goal is to provide tools, theory, and algorithms for detecting these repetitive structures efficiently and formally.

## Projects in this Organization

The organization will host:

* **The original AS2 thesis and documentation**
* **Supmax**, the original implementation for detecting supermaximal repeats
* **Modernized AS2-Stream**, a reimplementation compatible with streaming and contemporary suffix structures
* Libraries, prototypes, and experiments based on the extended Repetition Algebra
* Experimental datasets, proofs of concept, and theoretical notes

## Long-Term Vision

Our long-term initiative is to develop:

* a **complete algebraic theory of repetitions**,
* a **suite of tools and libraries** for working with repetitive structures,
* and a set of **rigorous tests and benchmarks** for string algorithms,
  all grounded in a formal, expressive, and extensible algebra.

The organization welcomes collaboration, discussion, and contributions from researchers, developers, and practitioners interested in string algorithms, algebraic structures, and streaming data systems.

## Copyright

© 2002–2025 Cristian S. Rocha.
All rights reserved unless otherwise stated in individual repositories.
