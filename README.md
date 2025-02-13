# Anonymous Chat bot
Bale or Telegram

## Getting Started
clone the repository to your local machine.

### Dependencies
```
pip install -r requirements.txt
```

### Configuration File
example `configs.py` file for Bale:
```python
DATABASE_URI: str = "<YOUR_DATABASE_LOCATION>"
BOT_TOKEN: str = "<YOUR_BOT_TOKEN_FROM_BOTFATHER>"
URL: str = f"https://tapi.bale.ai/bot{BOT_TOKEN}/"
ROOT_URL: str = "https://bale.ai/<BOT_USERNAME>"
KEY: int = 0xA5A5A5A5
```

### Running the Application
```
python bot.py
```