1. You need to install python-telegram-bot version 13.7

Type these cmds into your Terminal:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
```bash
brew install python
```
```bash
pip install python-telegram-bot==13.7
```
If your device use python3, type these cmds
```bash
brew install python3
```
```bash
pip3 install python-telegram-bot==13.7
```
And this cmd to install module docker:
```bash
pip install docker
```
or
```bash
pip3 install docker
```
**Recommend you use ChatGPT to install if you dont know much abt code**

2. Create telebot in Telegram by BotFather

3. Install Visual Studio Code for MacOS. Link https://code.visualstudio.com/download

4. Create file and paste the **scrpit**, replace your "TOKEN TELE BOT" and "WORKER COMMAND", then save the file as "**docker.py**"

5. Run this cmd in terminal
```bash
python docker.py
```
```bash
python3 docker.py
```

There are 5 basic commands in bot:
- /containers_status
- /images_status
- /remove_containers
- /remove_images
- /rerun_command

