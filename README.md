# agent-eval

A local CLI for evaluating coding agents against fixed programming tasks.

The MVP will be implemented in Go and starts with a small Go task suite. The runtime
design keeps task execution, grading, and language profiles separate so that
additional programming languages and execution backends can be added later.

## Status

Initial workspace setup. See the [implementation specification](docs/agent-eval-spec.md).

## Requirements

- Go 1.23 or newer
