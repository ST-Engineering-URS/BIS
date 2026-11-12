# Elixir

This directory contains the BIS Elixir application. Keep reusable
data-processing and analysis code under `lib/` and its tests under `test/`.

From this directory, run:

```sh
mix compile
```

Add tests under `test/` as processing behavior is introduced. Add dependencies
only when required by a defined use case, and document external data inputs and
configuration through environment variables rather than committed secrets.
