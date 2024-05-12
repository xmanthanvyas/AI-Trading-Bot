# Trader Bot

Build a trader bot which looks at sentiment of live news events and trades appropriately.

# Startup 🚀
- Create a virtual environment `conda create -n trader python=3.10`
- Activate it `conda activate trader`
- Install initial deps `pip install lumibot timedelta alpaca-trade-api==3.1.1`
- Install transformers and friends `pip install torch torchvision torchaudio transformers`
- Update the API_KEY and API_SECRET with values from your Alpaca account
- Run the bot `python tradingbot.py`
