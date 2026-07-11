# FrontierSWE Deep Research

A comprehensive research report on [FrontierSWE](https://epoch.ai/benchmarks/frontierswe) — the ultra-long-horizon AI programming benchmark by Epoch AI that tests whether coding agents can complete open-ended software engineering projects spanning hours to tens of hours.

## What's Inside

The report covers:

- **Benchmark Design** — 17 tasks across Implementation, Research, and Performance categories with 20-hour time windows
- **Model Performance** — Rankings and deep dives on Claude Fable 5, GLM-5.2, DeepSeek V4-Pro, MiniMax M3, Kimi K2.7, Qwen3-Coder, and more
- **Lessons for Software Engineers** — Short-horizon saturation, the context-handling gap, benchmark contamination, agent failure modes, and why the harness matters more than the model
- **Harness Engineering Best Practices** — Context management, error recovery, tool design, hooks & enforcement, feedback loops, and long-horizon execution patterns

## Quick Takeaways

- **Claude Fable 5** leads FrontierSWE with 0.900 dominance
- **GLM-5.2** is the #1 open-source model (0.740), within 1% of Opus 4.8 at ~1/6 the cost
- A well-scaffolded mid-tier model outperforms a poorly-scaffolded frontier model
- No model has fully solved any FrontierSWE implementation task — the benchmark remains unsaturated

## File

- [`FrontierSWE-Deep-Research-Report.md`](./FrontierSWE-Deep-Research-Report.md) — Full report (~3,900 words, 24 cited sources)

## License

MIT
