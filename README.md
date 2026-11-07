# Atelier

The art of building software. A software factory for those who care about
the code: it builds reliable, secure, performant and maintainable software
in a predictable, repeatable and measurable way.

## Why

I don't write the code myself, but that doesn't mean I can't control its
quality.

Agents write code fast. Left alone, they also make the decisions that should
have been mine: where a rule lives, how a failure is handled, what a unit of
work is. The code passes its tests and is still wrong for the system. Atelier
exists so those decisions are made once, by the developer, and the agents
build within them.

## What the factory is

- It is the loop that lets agents keep picking up tickets toward the
  developer's goal.
- It is the guard rails that let the developer work in a given profile and
  get consistent results.
- It is the map that makes clear which decisions belong to the developer,
  so they are not left to the AI.
- It is the window into the state of a project while it is being built.
- It is the landscape we work in.

## Architecture first

Atelier maps the lifecycle of software, from idea to code, to a core set of
ideas that drive the generation of code. It means thinking about
architecture first:

- how the system starts and how its parts are composed;
- what every request passes before any work begins;
- how code flows, and how modules talk to each other;
- where input is checked, and what each contract promises;
- what a unit of work is, and how units are ordered and run;
- where the business lives, how data reaches it, and the rules for changing it;
- what happens beyond our own data, and how failure is named and shown;
- what each path costs, how it is observed, and how it is proven.

These concepts apply differently depending on the type of application, which
is why they are broken into profiles, so that a desktop application is not
restricted by the principles of a REST API.

Atelier is described the same way as the software it builds: it has its own
product spec, its own design and its own profile. It is a software system
like any other.

## Pillars

Everything Atelier builds is held to four pillars: reliability, security,
performance and maintainability. They are written down once and measured.
Nothing in the code is tagged with them, and no build rule comes from them.
Each has a signal read from what the build already produces, and where the
code goes follows the signal, not the name.

## Why "Atelier"

An atelier is a workshop: the studio where a master sets the method and the
standard, apprentices do the work, and nothing leaves until the master signs
off. I call it Atelier because this is where the art is defined: the
developer's workshop.

In reality it is like the software it aims to create, a carefully designed
system of many moving parts, and from this workshop every part is visible and
explained.

## Status

Early. Atelier is being built alongside its first production application,
following its own process by hand before any of it is automated.

## License

MIT
