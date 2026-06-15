# Contributing to the C# implementation of AXON

Thank you for your interest in contributing to the C# (`axon-cs`) implementation of the AXON protocol.

This repository will host the .NET class library that implements the AXON protocol as defined in the [spec repository](https://github.com/axon-prot/spec). The goal is to provide a clean, idiomatic C# API for the protocol that can be used across .NET applications.

## Getting Started

### Prerequisites

- **Git** – for cloning and contributing.
- **.NET SDK** (version 6.0 or later) – to build and test the library.
- **A text editor or IDE** – e.g., Visual Studio, Visual Studio Code, Rider.

### Setup

```bash
# Clone the repository (if not already cloned)
git clone <your-fork-url>
cd axon-cs

# Build the project

dotnet build
```

## How to Contribute

- **Feature work** – Implement new protocol capabilities or extend the library in a clean, test‑driven manner.
- **Bug fixes** – Address issues in the current implementation. Provide a test case that reproduces the bug before fixing it.
- **Documentation** – Improve this README, design docs, or API documentation.
- **Tests** – Add or enhance unit tests. The project uses the standard `dotnet test` framework.

## Workflow

1. **Fork** the repository and create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Make changes** and write tests.
3. **Run tests** locally:
   ```bash
   dotnet test
   ```
4. **Commit** using conventional commit style (e.g., `feat: add handshake support`).
5. **Push** your branch and open a **merge request**.

## Code Style

- Follow the official Microsoft C# coding conventions.
- Use `nullable` reference types and enable implicit usings.
- Keep the public API surface minimal and well‑documented.

## License

The implementation will be released under the **MIT License**.

## Additional Resources

- The protocol specification can be found in the [spec repository](https://github.com/axon-prot/spec).
- For guidance on .NET library design, refer to the Microsoft documentation on [Class Library Design Guidelines](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/).

We welcome contributions and look forward to building a robust C# implementation of AXON together!
