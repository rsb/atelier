# Pillars

Everything Atelier builds is held to four pillars: reliability, security,
performance and maintainability. Every product inherits them, Atelier
included.

They are written down here once and measured. Nothing in the code is tagged
with them, and no build rule comes from them. Each pillar has a signal read
from what the build already produces, and the signals are read before
deciding what to do next. Where the code goes follows the signal, not the
name.

| Pillar | What it asks |
|---|---|
| **Reliability** | The software fails closed and stays correct when a dependency fails or two requests race. Errors are values, and none is thrown across a boundary. |
| **Security** | Every threat has a home in the code and a test that exercises it. |
| **Performance** | Every path has a written cost, and a change to that cost is deliberate. |
| **Maintainability** | Every spec has an address and a check, so drift is found, not remembered. |

What each pillar asks is the same everywhere. Its signal differs by stack, so
each profile names its own. A product does not restate the pillars: it
inherits them from here and reads its profile's signals.
