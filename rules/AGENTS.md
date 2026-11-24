# Using RetailVest Smart Money

Use the `smart-money` tools for questions about what well-known investors and hedge funds own or traded, who owns a US
stock, insider trades, 5%+ stakes, a company's audited figures, and futures positioning.

- Names work as people say them: "Buffett", "Ackman", "Nvidia", "Apple", "BRK-B". If a tool answers `did_you_mean`,
  ask which one, or pick the obvious match and say so.
- 13F holdings are quarterly snapshots of long US positions, filed up to 45 days after the quarter ends. Say the quarter
  ("as of Q3 2026"), and don't present them as current positions. They leave out shorts, cash, bonds and non-US holdings.
- COT (futures positioning) is weekly, as of the stated report date.
- `copy_investor_backtest` results are hypothetical and past performance; say so.
- Link the filing (`sec_url`, `source_url`, `url`) when quoting a figure.
- This is data and research, not investment advice. Don't tell the user to buy or sell.
