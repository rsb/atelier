# Glossary

The language of Atelier. There is one language, the business's, and this
file holds its terms. Atelier's business is building software, so its terms
are the terms of the craft. Every document and every name in the code uses
them as written here.

Each entry gives the meaning, what it is often confused with, and the
decision it comes from, by number in `prd/atelier/decisions.md`.

## Atelier
The software factory as a whole: its method, its guard rails, its loop, its
window and its landscape. Also this repository, where the factory is stated.
Not to be confused with: any one of its parts. The engine is one part.
From: D1.

## Product
What a repository builds. A repository holds exactly one product.
Not to be confused with: an application.
From: D6.

## Application
One deployable or runnable piece of a product: an api, a BFF, a CLI, a
desktop app, a worker. A product may have many; they all serve the one
product.
Not to be confused with: a product.
From: D6.

## Profile
The shape of a kind of software: its layout, its layers, its rules and
templates. A repository is built in one profile, which may be composed of
several profile nodes.
Not to be confused with: a product, which a profile shapes but does not
name.
From: D8.

## Profile node
One part of a profile, mounted at a path in a repository: an api node, a BFF
node, a CLI node. A node's chain runs from an application type to the
platform it runs on.
Not to be confused with: an application, which a node shapes.
From: D8.

## Story
How one kind of software is put together, told in the order something meets
it, one chapter per part.
Not to be confused with: a user story. A story here describes architecture,
not a requirement.

## Rule
Something that must hold. A broken rule is a finding.
Not to be confused with: a heuristic.

## Heuristic
A weighed default: a rule of thumb, not guaranteed correct, that leaves the
agent free to choose. A departure from one is a deviation, with no
consequence.
Not to be confused with: a rule.

## Check
How a rule or a heuristic is tested.
Not to be confused with: a test of the product's behaviour.

## Pattern
A named, recurring shape in the code. It has no check of its own.
Not to be confused with: a template, which realizes patterns in files.

## Template
Rules and patterns baked into files, so an agent composes parts instead of
inventing them.
Not to be confused with: a pattern.

## Instance
One private deployment of a profile, with real data and its own
configuration.
Not to be confused with: a product, which an instance runs.

## Invariant
A named property an instance declares, such as having real users, that rules
can depend on. Never a rule itself.
Not to be confused with: a rule.

## Custody
Who holds a credential and may act with it. Only the driver holds the
factory's key; no agent holds a credential.
Not to be confused with: access, which says who may run an operation.

## Trust base
The parts of Atelier that hold power: its rules, its sandbox, its key, its
engine. They are built at the desk and never by an agent attempt.
From: D9.
