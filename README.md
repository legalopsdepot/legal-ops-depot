# Legal Ops Depot

A free law library for your AI assistant: U.S. court rules, statutes, regulations, constitutions and more than 10 million court decisions with overruled flags, from Legal Ops Depot. Your assistant quotes the source text with a citation and a link. You can also read your own Legal Ops Depot matters.

Legal Ops Depot prepares court filings that the buyer files themselves. It is not a law firm, attorney or paralegal service, does not represent anyone and does not give legal advice. This plugin quotes source text with links; it does not tell anyone what to file or how a court will rule.

## What is in it

- **Connector:** the read-only Legal Ops Depot MCP server, `https://mcp.legalopsdepot.com/mcp`. Sign in with a Legal Ops Depot account when your assistant asks (OAuth; no key to paste). The Free plan allows 40 calls a day; Plus 300, Pro 1,500, Firm 10,000. No tool can create, change, file, pay for or delete anything.
- **Skills:**
  - `law-lookup`: reads the exact text of a statute, regulation, constitution section or court rule.
  - `court-deadline-rule`: finds and quotes the rule that sets the time limit for a filing in a named court.
  - `citation-check`: checks each case cited in a draft against the case-law database and reports found / mismatch / not found.
  - `filing-checklist`: builds a tick-box checklist of format, content, service and filing rules for one filing type in one court.
  - `highest-authority`: lists cases on a topic ranked by authority for the user's court, with quoted passages and links.

Every skill states a rule, statute or case only when the text came back from a Legal Ops Depot tool in the same conversation.

## Install

- **Claude Code:** `claude --plugin-dir ./legal-ops-depot` (or install from the Claude directory once listed).
- **Cursor:** install from the Cursor Marketplace once listed. The same folder carries `.cursor-plugin/plugin.json` and `mcp.json`.
- **Claude, ChatGPT, Grok or any assistant that takes a custom connector:** add `https://mcp.legalopsdepot.com/mcp` as a custom connector and sign in.

Then ask, for example: "What does 42 U.S.C. 1983 say?" or "What rule sets the deadline for a notice of appeal in the Eleventh Circuit?"

## Support and policies

- Support: https://www.legalopsdepot.com/support or contact@legalopsdepot.com
- Privacy: https://www.legalopsdepot.com/privacy
- Terms: https://www.legalopsdepot.com/terms

## License

MIT. See `LICENSE`.
