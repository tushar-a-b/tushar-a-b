<h1>Hi, I'm Tushar</h1>

Backend engineer building distributed systems and AI developer tooling.

## What I'm building now

- **Trust Identity Protocol (TIP)** at [theailaborg](https://github.com/theailaborg): a content-provenance platform with cryptographic signing, juror-based dispute resolution, and Merkle-anchored canonical state. I work across the whole ecosystem: the [public protocol core](https://github.com/theailaborg/tip-protocol), plus the SDK, browser extension, AI classifier, protocol node, mobile web app, and WordPress plugin in private org repos. That work happens on my work account, [@t-bhendarkar](https://github.com/t-bhendarkar), which is where my daily contribution graph lives.
- **ML and data tooling** at the same org: PII redaction, an LLM inference toolkit, research-paper extraction and metadata pipelines, and audio transcription (private repos).
- **[Ship & Tell](https://github.com/tushar-a-b/ship-and-tell)**: an MCP server and Claude Code skill that mines your local AI coding sessions and turns them into tweets, threads, and articles. No external API: the coding agent's own model does the writing, and nothing leaves your machine.

## Recent shipped work

- [Async classifier pipeline](https://github.com/theailaborg/tip-protocol/pull/69): moved a slow classifier out of the request path so the API returns immediately and the two halves fail independently
- [Canonical-state reset fix](https://github.com/theailaborg/tip-protocol/pull/72): made clear and build functions exact inverses so Merkle roots stay consistent across nodes
- [Subagent transcript mining](https://github.com/tushar-a-b/ship-and-tell/commit/ca24007): found that Claude Code stores 5x more transcripts than the obvious glob shows, and built dedup-aware reading on top

## Stack

Python, TypeScript, Node.js, React, Next.js, Postgres, Redis, Laravel.

## Reach me

- Website: [tusharbhendarkar.com](https://tusharbhendarkar.com)
- LinkedIn: [tushar-bhendarkar](https://www.linkedin.com/in/tushar-bhendarkar-486096151)
- Email: tusharbhendarkar44@gmail.com
