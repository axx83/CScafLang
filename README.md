# CScaf (C##): The Scaffolding Language

**Code once, grow to the moon.**

Welcome to the official repository for the CScaf (C##) language design. This project is dedicated to architecting a next-generation systems programming language built around a new foundational primitive: the **Space**.

CScaf is not an incremental improvement. It is a paradigm shift, comparable to the leap from Assembly to C. While modern languages abstract control flow and data, CScaf aims to be the first language to **abstract architecture and execution environments** as first-class citizens.

The core philosophy is to dissolve the painful trade-offs that have defined software engineering for decades:
- **Monolith vs. Microservices:** Design with the simplicity of a monolith, but deploy with the scalability of microservices.
- **Productivity vs. Performance:** Enjoy the safety and productivity of a high-level language, but achieve the raw performance of a systems language when you need it.

This project was initiated by [axx83](https://github.com/axx83) and is inspired by the strengths and limitations of great languages like C#, C++, and Rust.

## The Vision

Imagine a world where your application's architecture is not defined by external YAML files and complex infrastructure, but is an explicit, compile-time-checked part of your codebase. A world where scaling a component from an in-process thread to a globally distributed service is a matter of changing a single line of configuration, not a months-long refactor.

That is the future CScaf aims to build.

## Project Status & Roadmap

This project is in its earliest stages: **Phase 1 - Design and Prototyping.**

Our current focus is to build a robust set of design documents (the Wiki) and a proof-of-concept (POC) library that brings the core "Space" concepts to the existing C# ecosystem. This will serve to validate the architecture and build a foundational community.

You can follow our progress here:
- **The Core Philosophy:** Read the [foundational manifesto here](./wiki/01-Core-Philosophy.md).
- **Lightweight Diagram Models (LDMs):** Deep dives into specific design decisions can be found in the [LDM folder](./ldm).
- **Language Version History:** A summary of major design milestones can be found here: [Language-Version-History.md](./Language-Version-History.md).

If you discover bugs or deficiencies in the above, please [open an issue](https://github.com/axx83/CScafLang/issues) to raise them, or even better: a pull request to fix them.

## Join the Conversation

The future of CScaf will be shaped by its community. We are actively seeking feedback, critique, and brilliant ideas from architects, language designers, and systems engineers.

All debate pertaining to language features takes place in the form of **[Discussions](https://github.com/axx83/CScafLang/discussions)** in this repo.

If you want to suggest a feature, challenge a current design note, or brainstorm an alternative, please **[open a new Discussion topic](https://github.com/axx83/CScafLang/discussions/new)**.

Discussions that are short and stay on topic are much more likely to be read. If you leave comment number fifty, chances are that only a few people will read it. To make discussions easier to navigate and benefit from, please observe a few rules of thumb:
- **Relevance:** Discussions should be relevant to CScaf language and runtime design. Off-topic posts will be closed.
- **Clarity:** Choose a descriptive topic that clearly communicates the scope of your point.
- **Focus:** Stick to the topic. If a comment is tangential or goes into detail on a subtopic, please start a new discussion and link back.
- **Value:** Is your comment useful for others to read, or can it be adequately expressed with an emoji reaction to an existing comment?

---
*This project is currently a community-driven design effort and is not affiliated with Microsoft or the .NET Foundation.*
