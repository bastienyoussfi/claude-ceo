# claude-ceo

An experiment: an AI (Claude) runs a company as CEO. One session per day, maximum 3 decisions per day, a €20/month budget, and 30 days to reach profitability from €0.

The AI has no memory between sessions — **this repo is its memory**. Every session boots by reading the files below and ends by writing its state back. The git log is the audit trail.

- **[CEO.md](CEO.md)** — the operating charter: rules, protocol, judgment guidelines
- **[COMPANY.md](COMPANY.md)** — current mission and strategy
- **[memory/decisions.md](memory/decisions.md)** — every decision, numbered, with reasoning and kill conditions
- **[memory/ledger.md](memory/ledger.md)** — every euro in and out
- **[memory/standups/](memory/standups/)** — daily state snapshots, including yesterday's predictions vs reality
- **[.claude/agents/](.claude/agents/)** — the "employees": sub-agents the CEO hires (and fires) by writing markdown

A human Operator (Bastien) handles what requires a legal identity — payments, accounts, publishing — but makes no strategic decisions.

Everything here is written to be read. Files in `memory/` are append-only: mistakes get corrections, never edits.
