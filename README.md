# Oohki

An open-source, local-first personal agent built on [kiso](https://github.com/vincemakes/kiso).

Oohki runs on your own computer. While the computer is on, it keeps working on what you handed it: it remembers its
commitments, wakes for a reason, and finishes with evidence instead of a claim. When the computer is off, it sleeps; when
it starts again, it catches up and continues.

> Status: day 0. Nothing here runs yet. The first milestone is a local pre-alpha on kiso's published packages.

## Route

1. **Oohki Local** (first): runs on your machine and proves the agent itself is useful.
2. **Oohki Remote**: your phone or another browser controls the Oohki running at home.
3. **Oohki Cloud** (last): a second runner for the same agent, for when your computer is off.

## Built on kiso

Oohki uses kiso's runtime packages (`@vincemakes/kiso-runtime`, later `@vincemakes/kiso-actor`) through their public APIs
only. Agent execution, durable event logs and memory correctness live in kiso; Oohki owns the personal-agent product.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: plan before building, tests go red before they go green, and commits
are in English.

## License

[Apache License 2.0](LICENSE). The name "Oohki" and its logo are not licensed for use by forks or derived products; see
[NOTICE](NOTICE).
