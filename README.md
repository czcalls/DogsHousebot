# DogsHouse-Bot
Bot for https://t.me/dogshouse_bot

More crypto themes and softs in telegram: [Vaultboyportal](https://t.me/vaultboyportal "Blackhatshiller") 🦧
Additional soft information: https://t.me/vaultboyportal

## Functionality
| Functional                                                       | Supported |
|------------------------------------------------------------------|:---------:|
| Multithreading                                                   |     ✅     |
| Binding a proxy to a session                                     |     ✅     |
| Auto-login                                                       |     ✅     |
| Random sleep time between accounts, complete tasks, claim points |     ✅     |
| Support pyrogram .session                                        |     ✅     |
| Get statistics for all accounts                                  |     ✅     |

## Settings data/config.py
| Setting                      | Description                                                                                    |
|------------------------------|------------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**        | Platform data from which to launch a Telegram session                                          |
| **DELAYS-ACCOUNT**           | Delay between connections to accounts (the more accounts, the longer the delay)                |
| **PROXY_TYPE**               | Proxy type for telegram session                                                                |
| **WORKDIR**                  | directory with session                                                                         |

## Requirements
- Python 3.9 (you can install it [here](https://www.python.org/downloads/release/python-390/)) 
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage
1. Run the bot:
   ```bash
   python main.py
   ```
