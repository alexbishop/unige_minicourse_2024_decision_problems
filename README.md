# On Decision Problems in Groups

This repo contains the notes for a 2-part minicourse I gave at the Unversity of Geneva on 21 and 22 of May 2024.

[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Abstract

In 1911, Max Dehn considered the word problem, conjugacy problem and isomorphism problem for finitely presented groups. Motivation for these problems can be found in algebraic topology. In particular, the word problem allows us to verify if a curve is contractable; the conjugacy problem enables us to check if two given curves are free homotopic; and the isomorphism problem gives us a method to confirm that two spaces are not isomorphic. Moreover, in the case of knot theory, the isomorphism problem allows us to identify if a given knot is the unknot. These three problems, studied by Dehn, are fundamental to the study of group theory and are all examples of decision problems of groups.

In our first talk, we focus on the word problem for groups. Solutions to this problem are important as they allow us to perform calculations and decide on the equality of group elements. We begin by studying examples and classes of groups for which the word problem is easily solvable. In fact, under certain interpretations of random group presentations, almost all finitely presented groups have such an easily solvable word problem. We end this talk by showing that there exist finitely presented groups with undecidable word problems, that is, there is no algorithm that can correctly determine if any given product of group generators is the group identity.

In our second talk, we study the class of group properties known as Markov properties. Examples of such properties include being the trivial group, finite, abelian, amenable, torsion-free, having a solvable word problem, or having a solvable conjugacy problem. Using the unsolvability of the word problem from our first talk, we show that no algorithm can decide if a given finitely presented group has a particular Markov property. For example, it is impossible, in general, to decide if a given finitely presented group is abelian.

## Compiling the Notes

To compile these notes, simply run `latexmk` from within one of the directories `talk1` or `talk2`.

## Download Compiled Version

You can download a compiled version of these notes from the [GitHub Releases page](https://github.com/alexbishop/unige_minicourse_2024_decision_problems/releases).
