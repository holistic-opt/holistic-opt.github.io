---
layout: default
title: DopCert
group: "navigation"
id: home
---
### About
DopCert is a framework developed using the [Coq Proof Assistant](https://coq.inria.fr/) for formally verifing query optimizations in databases. It consists of the following parts:

1. HoTTSQL, a SQL like language that covers all major SQL features, including selection-projection-join, aggregation, correlated subqueries, and indexes. We provide a *machine checkable denotational semantics* of HoTTSQL using [Homotopy Type Theory](https://homotopytypetheory.org/) for proving rewriting rules.
2. A library that consists of building blocks of proofs and automatic decision procedures (e.g., decision procedure for conjunctive queries).
3. Machine checkable proofs for existing rewrite rules from database literature as well as real-world optimizers, ranging from basic ones such as selection push down to complex ones such as magic sets rewrites.

### Source

[GitHub Repository of DopCert](https://github.com/uwdb/DopCert)

### Publications
* [HoTTSQL: Proving Query Rewrites with Univalent SQL Semantics (preprint)](http://arxiv.org/abs/1607.04822)

### Contact

If you have any question, want to contribute to the project, or just want to say hi, email us at 
[DopCert@cs.washington.edu](mailto:DopCert@cs.washington.edu).
<!-- chushumo at cs dot uw dot edu or weitzkon at cs dot uw dot edu. -->


### People

DopCert is developed by the [Database Group](http://db.cs.washington.edu/) and the [Programming Languages and Software Engineering Group](http://uwplse.org/) at the [University of Washington](http://www.washington.edu/), the main contributors are:

<a class="person" href="http://shumochu.com/">
  <span class="name">Shumo Chu</span><br/>
  <img class="profile" src="http://stechu.github.io/images/my_portrait.jpg"/>
</a>

<a class="person" href="http://konne.me">
  <span class="name">Konstantin Weitz</span><br/>
  <img class="profile" src="http://www.konne.me/assets/profile.png"/>
</a>

<a class="person" href="http://www.stanleywang.org">
  <span class="name">Chenglong Wang</span><br/>
  <img class="profile" src="http://www.stanleywang.org/image/me.jpg"/>
</a>

<a class="person" href="https://homes.cs.washington.edu/~akcheung/">
  <span class="name">Alvin Cheung</span><br/>
  <img class="profile" src="https://homes.cs.washington.edu/~akcheung/self.jpg"/>
</a>

<a class="person" href="https://homes.cs.washington.edu/~suciu/">
  <span class="name">Dan Suciu</span><br/>
  <img class="profile" src="https://homes.cs.washington.edu/~suciu/files/me-7-2006-mexico.jpg"/>
</a>


