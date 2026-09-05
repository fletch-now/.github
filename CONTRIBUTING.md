# Contributing

Issues and pull requests are welcome on every repository in this organisation.

- Run the tests before opening a pull request: `npm test` in Node repositories, `python -m unittest` and `go test ./...` where those exist.
- Style: `function` declarations over arrow constants, explicit return types on top-level functions, no nested ternaries, and comments that explain why rather than what the line does.
- Keep README claims to what can be checked. No uptime, audit or security adjectives.
- Changes to the OpenAPI snapshot in fletch-api come from the live spec; edit the source of truth at fletch.now, not the snapshot.

Fletch is not affiliated with Robinhood Markets, Inc.
