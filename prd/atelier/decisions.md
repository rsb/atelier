# Decisions

Numbered, so every other document cites a decision by its number. A
decision is worked out in the research record and stated here. A changed
decision keeps its number and says what it replaced.

## D1. Atelier is the name, and it is a product
The whole system is named Atelier. It is described the way any product is:
its own product spec, its own design, its own profile.
2026-11-06.

## D2. Atelier is the source of truth
Ideas and the business of building software start here. Other parts point
to Atelier; Atelier explains them and points to them by stable names: names
of parts and concepts, never their files. The research record is a scratch
pad; Atelier states what is true now.
2026-11-06.

## D3. Nothing needs Atelier to run
Atelier depends on the other parts, never the reverse. The loop runs with
no Atelier present. For ideas the direction is the opposite: every part
points here for what it is.
2026-11-06.

## D4. A file lives with its subject
A file lives with the part whose subject it is, unless the loop reads it.
Then it lives where the loop reads it, and Atelier cites it. Tools whose
subject is a project live with the engine; tools whose subject is the whole
system live in Atelier.
2026-11-06.

## D5. The registry stays its own part
The registry holds what good code is. The engine holds how work is run and
judged. Atelier holds how it all fits. Each is its own repository.
2026-11-06.

## D6. One product per repository
A repository holds one product. It may have many applications and many
interfaces, and they all serve the one product.
2026-11-07.

## D7. One language
A product has one language, the business's. Its terms are held in
`GLOSSARY.md` at the root of the repository, in uppercase for visibility
and importance. The code speaks the same language. A naming conflict is
resolved by the layers: the path says which meaning is in use.
2026-11-07.

## D8. Atelier is a profile of profile nodes
A profile is the shape of one repository. Atelier's profile is composed of
nodes from different families: a CLI, a desktop app, an api and BFF, and
background workers.
2026-11-07.

## D9. The trust base is built at the desk
Atelier's own parts hold power, so they are built by the owner at the desk
and never by an agent attempt. A trust-base repository carries no
governance lock.
2026-11-06.

## D10. The method's folders are the same in every repository
`prd/` and `design/` have the same shape in every repository the factory
builds, Atelier's included, whatever the stack. The code's folders follow
the profile.
2026-11-07.

## D11. Manual first
The profile, containment and the CLI come before the loop. Atelier is used
by hand first.
2026-11-07.

## D12. The foundations sit at the root
Two documents sit at the root of Atelier, in uppercase: `GLOSSARY.md`, the
language everything speaks, and `PILLARS.md`, the standard everything is
held to. Every product inherits the pillars from Atelier and does not
restate them; it reads its profile's signals for them.
2026-11-07.
