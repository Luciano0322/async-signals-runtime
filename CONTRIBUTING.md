# Contributing Guide

Thank you for your interest in this project.

This repository is primarily a **research space** for exploring an
async-first, fine-grained reactive runtime. It is not a production library and
does not currently aim to provide a complete implementation.

## 🧭 How You Can Contribute

### 1. Discussions & Architectural Feedback
The most valuable contributions at this stage are:

- feedback on the async propagation model  
- critique of the scheduling semantics  
- suggestions on transactional commits  
- insights from existing framework runtimes (React, Solid, Vue, Qwik, etc.)  
- alternative designs or formalization of the model  

Please open a **GitHub Discussion** for design conversations.

### 2. Issues
If you find inconsistencies, unclear explanations, or diagrams that can be
improved, feel free to open an Issue.

### 3. Prototypes
If you experiment with parts of the proposed runtime (e.g., a scheduler,
versioning system, async freeze snapshot, etc.), contributions are welcome.

However, please note:

> The goal is correctness and clarity, not shipping a full framework.

### 4. Code Style (for future implementations)
If the `src/` directory grows into a prototype runtime, the project will adopt:

- TypeScript  
- modular runtime architecture  
- no framework-specific dependencies  

But for now, code contributions are optional.

## 📄 Licensing
By contributing, you agree that your contributions will be licensed under the
MIT License of this repository.

Thank you for helping explore this new direction in UI runtime architecture.
