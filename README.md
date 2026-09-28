# Youngkyo Kim

CS senior at UW–Madison (May 2027). Looking for quant developer, trading systems, and trade support roles for 2027.

I build trading systems and the data pipelines under them, then run them for real:

- Built a Binance futures trading framework alone and ran it with my own capital: a pipeline over years of 1-minute data, a backtester that evaluated 100+ long/short strategy variants, and live bots placing TP/SL bracket orders. The backtest was profitable, the live bot lost money, and I traced the gap to in-sample overfitting, unfilled limit orders, and slippage.
- Shipped an Android app alone that turns Korean public disclosure data (DART insider trades, public officials' asset filings, economic indicators) from 4+ sources into 6 chart modules for retail investors; Postgres backend on Supabase, 24-user closed test, live on Google Play.
- Keep 100+ Linux and Windows machines running for UW–Madison's College of Engineering: OS migrations with no unplanned research downtime, EDR alert triage from process execution history.
- Built four LLM apps on Azure at Microsoft AI School in Seoul, including a RAG pipeline over Azure AI Search.
- Former battalion communications specialist, Republic of Korea Army; interpreter with the U.S. Marine Corps during joint training.

Python, SQL/Postgres, C/C++, TypeScript, React/React Native, FastAPI, Supabase, Claude API, Azure OpenAI, Linux.

## Projects

**[binance-trading-framework](https://github.com/payjuper/binance-trading-framework)**  
Binance Vision data pipeline, rule-based backtester with equity curves, live long/short bots with TP/SL bracket orders via the exchange API. Ran live on perpetual futures.

**[Korea_history_quiz_api](https://github.com/payjuper/Korea_history_quiz_api)**  
RAG quiz generator: retrieves past exam questions from Azure AI Search, generates multiple-choice items with explanations via Azure OpenAI. FastAPI.

**[Cheesehacks](https://github.com/payjuper/Cheesehacks)**  
Team-matching platform for UW–Madison CS students, built in 24 hours with 3 teammates: post projects with open roles, apply by role, search and filter. React, Supabase/Postgres.

**[holdem-equity-trainer](https://github.com/payjuper/holdem-equity-trainer)** · [demo](https://payjuper.github.io/holdem-equity-trainer/)  
Small practice tool: Monte Carlo hand equity with standard error, verified against exact enumeration. Built to train my own probability intuition.

[LinkedIn](https://www.linkedin.com/in/youngkyo-kim-00a71134b) · yj1son@naver.com
