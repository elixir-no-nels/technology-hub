---
layout: default
---

Writing clean and easy to understand code is one of the most important aspects of the software development. The concept of the clean code is language agnostic. Some languages such as Python and Go have ways to enforce you to write more clean code.

There are several essential clean code principles:
- [KISS](https://en.wikipedia.org/wiki/KISS_principle): Keep It Simple Stupid. A design principle originating from the U.S. Navy that goes back to 1960 already. It states that most systems should be kept as simple as possible (but not simpler, as Einstein would have said). Unnecessary complexity should be avoided. The question to ask when you're writing code is "can this be written in a simpler way?"

- [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself): Don't Repeat Yourself. Closely related to KISS and the minimalist design philosophy. It states that every piece of knowledge (code, in this case) must have a single, unambiguous, authoritative representation within a system (codebase). Violations of DRY are referred to as WET: We Enjoy Typing, Write Everything Twice, Waste Everyone's Time.

- [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it): You Aren't Gonna Need It. A developer should not add functionality unless deemed necessary. YAGNI is part of the Extreme Programming (XP) methodology, which wants to improve software quality and increase responsiveness to customer requirements. YAGNI should be used in conjunction with continuous refactoring, unit testing, and integration.

- [Composition over inheritance](https://en.wikipedia.org/wiki/Composition_over_inheritance): Not an acronym, sadly. It's a principle where you design your types over what they do instead of over what they are. Composition is favored over inheritance by many developers, because inheritance forces you to build a taxonomy of objects early on in a project, making your code inflexible for changes later on.

- [Favor readability](https://en.wikipedia.org/wiki/Computer_programming#Readability_of_source_code): It's not because a machine can read your code that another human can. Particularly when working with multiple people on a project, always favor readability over conciseness. There's no point in having concise code if people don't understand it.

There is no universal ways to write clean code. And nobody's code is ever perfect. However, pratcice and frequent code reviewing can significantly improve your code's quality