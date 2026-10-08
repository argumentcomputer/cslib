# CSLib

[![Certified by ix](https://img.shields.io/github/actions/workflow/status/argumentcomputer/cslib/ix-proof.yml?branch=dev&label=Certified%20by%20ix&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xOCA4aC0xVjZjMC0yLjc2LTIuMjQtNS01LTVTNyAzLjI0IDcgNnYySDZjLTEuMSAwLTIgLjktMiAydjEwYzAgMS4xLjkgMiAyIDJoMTJjMS4xIDAgMi0uOSAyLTJWMTBjMC0xLjEtLjktMi0yLTJ6bS02IDljLTEuMSAwLTItLjktMi0ycy45LTIgMi0yIDIgLjkgMiAyLS45IDItMiAyem0zLjEtOUg4LjlWNmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMSAxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXYyeiIvPjwvc3ZnPg%3D%3D)](https://github.com/argumentcomputer/cslib/actions/workflows/ix-proof.yml?query=branch%3Adev+is%3Asuccess)

The Lean library for Computer Science.

Official website at <https://www.cslib.io/>.

# What's CSLib?

CSLib aims at formalising Computer Science theories and tools, broadly construed, in the Lean programming language.

## Aims

- Offer APIs and languages for formalisation projects, software verification, and certified software (among others).
- Establish a common ground for connecting different developments in Computer Science, in order to foster synergies and reuse.

# Using CSLib in your project

To add CSLib as a dependency to your Lean project, add the following to your `lakefile.toml`:

```toml
[[require]]
name = "cslib"
scope = "leanprover"
rev = "main"
```

Or if you're using `lakefile.lean`:

```lean
require cslib from git "https://github.com/leanprover/cslib" @ "main"
```

Then run `lake update cslib` to fetch the dependency. You can also use a release tag instead of `main` for the `rev` value.

# Contributing and discussion

Please see our [contribution guide](/CONTRIBUTING.md) and [code of conduct](/CODE_OF_CONDUCT.md).

For discussions, you can reach out to us on the [Lean prover Zulip chat](https://leanprover.zulipchat.com/).
