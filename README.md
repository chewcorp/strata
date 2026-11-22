# strata
strata: layered agent memory on okf-core (library and CLI, harness-agnostic)

Episodic and empirical profiles are `[profiles.episodic]` and `[profiles.empirical]` in `fixtures/okf-core.toml`. Validate each fixture bundle:

```sh
okf validate --config fixtures/okf-core.toml --bundle episodic
okf validate --config fixtures/okf-core.toml --bundle empirical
```
