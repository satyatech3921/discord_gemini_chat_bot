#Gemini Discord Bot

## [English](README_EN.md) | Traditional Chinese

This is a Chat bot that uses the Gemini model API developed by Google to connect to the Discord bot

- The channel has two modes: black and white list (please see **FAQ**)

- Text chat has short-term memory function (the upper limit of the number of memorized sentences can be customized)

- Able to perform image recognition

- Can be used in DM channel

- Ability to easily understand website content through crawlers

# Preparatory work

Fill in the required robot settings in `config.json`

```
pip install -U -r requirements.txt
```

Put prompt into `call_api.py` (can be skipped) [Tutorial](docs/zh/q7.md)

Put history into `call_api.py` (can be skipped) [Tutorial](docs/zh/q3.md)

Execute `main.py`

# introduce

- ### [Principles of operation](docs/zh/principles.md)

- ### [Commands](docs/zh/commands.md)

- ### [File description](docs/zh/files.md)

- ### [Update log](docs/zh/log.md)

# FAQ

- ### [What should I do if I want to change channel.json to channel whitelist instead of blacklist?](docs/zh/q1.md)

- ### [How to obtain Gemini api key?](docs/zh/q2.md)

- ### [How to write Prompt prompt words?](docs/zh/q7.md)

- ### [How to generate history for training?](docs/zh/q3.md)

- ### [Error:The caller does not have permisson](docs/zh/q4.md)

- ### [Error:No such file or directory: 'config.json/channel.json'](docs/zh/q5.md)

- ### [Selection of different Gemini models](docs/zh/q6.md)
