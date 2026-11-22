# strata
strata: layered agent memory on okf-core (library and CLI, harness-agnostic)

Episodic and empirical profiles are `[profiles.episodic]` and `[profiles.empirical]` in `fixtures/okf-core.toml`. `okf` is the [chewcorp/okf-core](https://github.com/chewcorp/okf-core) CLI. That package is not published on PyPI; install it from chewcorp's index:

```sh
pip install okf-core \
  --index-url https://chewcorp.github.io/okf-core/simple/ \
  --extra-index-url https://pypi.org/simple/
```

Validate each fixture bundle:

```sh
okf validate --config fixtures/okf-core.toml --bundle episodic
okf validate --config fixtures/okf-core.toml --bundle empirical
```
