# Contributing to JuliaNeutrino

We welcome contributions, which can come in many forms:

## Bug reports and discussions

If you think you found a bug in any of our packages, feel free to open an issue at the specific GitHub repo.
For our packages, it should be a link like `https://github.com/JuliaNeutrino/PACKAGE.jl`.

Focused suggestions and requests can also be opened as issues.
Before opening a pull request, start an issue on the topic, please.

## Pull requests

- Keep each pull request to one topic: a bug fix, a feature, or a documentation change.
- Add tests for new code, and a test that reproduces the bug for a bug fix.
- Format the code with [JuliaFormatter.jl](https://github.com/domluna/JuliaFormatter.jl) using the `.JuliaFormatter.toml` of the repository. GLoBES.jl also has a [pre-commit](https://pre-commit.com) configuration that runs the formatter and the other linters.
- Do not commit unrelated `Manifest.toml` changes or other temporary files.

## Physics changes

When a change affects physical results (probabilities, event rates, χ²), please cite the paper or the C GLoBES routine it follows, and add a test against a reference value.
