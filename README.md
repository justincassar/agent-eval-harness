# agent-eval-harness

An evaluation harness for tool-using LLM agents, written in Go.

The goal is to run an agent through a suite of tasks in sandboxed
environments and grade each run on more than just the final answer:

- **Outcome**: is the answer right?
- **State**: is the workspace left in the right state?
- **Trajectory**: did the agent use its tools sensibly?
- **Reliability**: does it pass every time, or only sometimes?
- **Cost**: tokens, dollars and latency per task.

Work in progress. See the [design doc](docs/design.md) for goals, architecture
and the decisions behind them.

## License

[MIT](LICENSE)
