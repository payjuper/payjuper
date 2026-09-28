# Youngkyo Kim

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/youngkyo-kim-00a71134b)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:yj1son@naver.com)

CS senior at UW–Madison (May 2027). Looking for 2027 roles at the intersection of markets and code: quant research, quant development, trading systems, and data-driven investing.

I build trading systems and the data pipelines under them, then run them for real.

**Trading systems.** Built a Binance futures trading framework alone and ran it with my own capital: a pipeline over years of 1-minute data, a backtester that evaluated 100+ long/short strategy variants, and live bots placing TP/SL bracket orders. The backtest was profitable, the live bot lost money, and I traced the gap to in-sample overfitting, unfilled limit orders, and slippage.

**Financial data.** Shipped an Android app alone that turns Korean public disclosure data (DART insider trades, public officials' asset filings, economic indicators) from 4+ sources into 6 chart modules for retail investors. Postgres backend on Supabase, 24-user closed test, live on Google Play.

**Production systems.** Keep 100+ Linux and Windows machines running for UW–Madison's College of Engineering: OS migrations with no unplanned research downtime, EDR alert triage from process execution history.

**Applied AI.** Built four LLM apps on Azure at Microsoft AI School in Seoul, including a RAG pipeline over Azure AI Search.

**Before this.** Battalion communications specialist, Republic of Korea Army; interpreter with the U.S. Marine Corps during joint training.

**Stack:** Python, SQL/Postgres, C/C++, TypeScript, React/React Native, FastAPI, Supabase, Claude API, Azure OpenAI, Linux.

## Projects

| | |
|---|---|
| **[binance-trading-framework](https://github.com/payjuper/binance-trading-framework)** | Binance Vision data pipeline, rule-based backtester with equity curves, live long/short bots with TP/SL bracket orders. Ran live on perpetual futures. |
| **[Korea_history_quiz_api](https://github.com/payjuper/Korea_history_quiz_api)** | RAG quiz generator: Azure AI Search retrieval over past exam questions, Azure OpenAI generation. FastAPI. |
| **[Cheesehacks](https://github.com/payjuper/Cheesehacks)** | Team-matching platform for UW–Madison CS students, built in 24 hours with 3 teammates. React, Supabase/Postgres. |
| **[holdem-equity-trainer](https://github.com/payjuper/holdem-equity-trainer)** · [demo](https://payjuper.github.io/holdem-equity-trainer/) | Small practice tool: Monte Carlo hand equity with standard error, verified against exact enumeration. |
