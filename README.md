## Dapphub Linear Logic

Dapphub is conducting R&D in linear logic.

Current work in progress:


### LL Motivation

An expansive introductory paper, motivating linear logic as a smart
contract programming language.

<https://github.com/dapphub/llmotivation>


### `calc`

`calc` is a linear logic tool, heavily inspired by CELF and Ceptre.

This is a generic theorem proover, currently implemented in javascript
(for use in interactive proof search in the browser), and with output to
a shallow embedding of linear logic in Isabelle/HOL.

<https://github.com/mhhf/calc>

A deep embedding is underway.


### LL Token

A simple specification of a fungible token, meant as a short
introduction to using linear logic to specify blockchain
applications.

<https://dapphub.github.io/LLsai/token>


### LL Sai

A more complex specification, of the [sai] stablecoin contract system.

<https://dapphub.github.io/LLsai/sai>

The longer term aim is for this document to become an interactive
literate program, generating theorem proofs on the fly and allowing the
reader to introduce new rules and try out new theorems.

[sai]: https://github.com/makerdao/sai


### LL EVM

An implementation of the EVM in linear logic, compliant with the
ethereum client vm-tests, allowing for proving theorems about EVM
bytecode.

Coming soon!


### Ceptre hacking

Both of the above specifications require a lightly modified version of
[ceptre] to run.

<https://github.com/dapphub/interactive-lp>

[ceptre]: https://github.com/chrisamaphone/interactive-lp


### LL poster

A useful cheat sheet for linear logic. The perfect gift for all your
friends!

<https://github.com/dapphub/LLPoster>
