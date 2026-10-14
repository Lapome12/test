# test

Uses [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) (`vibe-trading-ai` on PyPI), a natural-language finance research agent with backtesting. Requires Python >= 3.11.

## Setup

```bash
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/vibe-trading init    # creates ~/.vibe-trading/.env (LLM API keys etc.)
.venv/bin/vibe-trading --help
```

Optional extras (e.g. Anthropic models, IBKR): `.venv/bin/pip install "vibe-trading-ai[anthropic,ibkr]==0.1.16"`.
