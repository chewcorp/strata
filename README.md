# strata
strata: layered agent memory on okf-core (library and CLI, harness-agnostic)

Episodic and empirical profiles are `[profiles.episodic]` and `[profiles.empirical]` in `fixtures/okf-core.toml`. `okf` is the [chewcorp/okf-core](https://github.com/chewcorp/okf-core) 0.6.0 CLI. Install that release wheel by URL so the artifact is the chewcorp build. Dependencies still come from PyPI; PyPI is not asked for a package named `okf-core`:

```sh
pip install "https://github.com/chewcorp/okf-core/releases/download/v0.6.0/okf_core-0.6.0-py3-none-any.whl#sha256=e219360611d143f3aae7efaeff7713f1fb95ce1f4e462e5689959758dc411fde"
```

Validate each fixture bundle:

```sh
okf validate --config fixtures/okf-core.toml --bundle episodic
okf validate --config fixtures/okf-core.toml --bundle empirical
```
