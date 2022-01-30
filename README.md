# PekeBot
Telegram bot for pokémon go task reporting

First of all you have to set up your database information and bot token in `config.py`

Then, you shall be able to run the bot by just executing `bot.py`

The bot is running with a MongoDB database, so you have to re-write most of `bot_utils.py` if you are using any other database server

The `scrap.py` script is used to update the database whenever there is a monthly rotation or event task via CMD
