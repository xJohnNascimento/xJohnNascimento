Hi, I'm Jonathan, Staff Software Engineer and Tech Lead at [Stark Bank](https://starkbank.com) in São Paulo.

Since 2020 I've built systems that move and account for money in Brazilian finance:

- **Stark Bank** (2024–now): I lead engineering for credit and investments, crypto, and regulatory reporting, including the platform that files mandatory reports to Brazil's central bank and tax authority.
- **Itaú Unibanco** (2020–2024): I maintained and modernized the messaging core of Brazil's interbank settlement system, its equivalent of Fedwire, which carries 40M+ transactions a day and R$30 trillion (≈US$5.5T) a month. Alongside the legacy .NET Framework and IBM MQ stack, I built new services on .NET 6, Kafka and AWS, including the contingency portal that keeps settlement flowing when the primary channel is down.

That code is proprietary, so this is where I build the same kind of systems in the open.

**Now building:** a double-entry ledger and an FX service. They'll be pinned below as they ship.

<!--
Uncomment this section, and drop the "Now building" line, once the first project is public.

### Projects

| Project | What it does | Stack |
|---|---|---|
| [ledger](https://github.com/xJohnNascimento/ledger) | Double-entry, append-only ledger: balanced transactions, holds, balances and statements, events through a transactional outbox | Go, PostgreSQL, ConnectRPC, AWS, Terraform |
| [fx](https://github.com/xJohnNascimento/fx) | TODO: one line on what it does | TODO |
-->

### Stack

- **Languages:** Python, C#/.NET, TypeScript
- **Cloud:** GCP, AWS
- **Data and messaging:** PostgreSQL, BigQuery, SQL Server, Kafka, Pub/Sub, IBM MQ

### How I work

Correctness over throughput, small designs, and decisions written down as ADRs.
I plan first, then ship in small pull requests behind tests, CI and review.
AI agents do much of the implementation and a second model reviews it; I make the design calls and read every diff before it merges.

### Contact

[LinkedIn](https://www.linkedin.com/in/xjonathannascimento/) · [xjohn.nascimento@gmail.com](mailto:xjohn.nascimento@gmail.com)
