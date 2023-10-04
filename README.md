# Therac-25-Anti-patterns

> An analysis of the famous catastrophe Therac-25 pitfalls, a computer-based radiotherapy device developed by AECL (Atomic Energy of Canada Limited) between 1985 and 1987.
> 
> This analysis is based on Mrs. Leveson's investigations article posted on the Stanford web archive with some Hardware-Software Co-design in mind.

## Table of contents:
- What's Therac-6, Therac-20, and Therac-25?
- The "Therac" series software defects.
- The "Therac" design pitfalls.
- How hardware protection overrides software pitfalls in Therac-6 and Therac-20.
- Therac-25 reported `Malfunction-45`.
- A deeper look into a simulation code and simulation fix environment.
- Naming anti-patterns utilized in the Therac software (Race conditions and concurrent programming).
- An approach to avoid these catastrophic errors.
