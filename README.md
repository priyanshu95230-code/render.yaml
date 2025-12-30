services:
  - type: worker
    name: insta-story-bot
    env: python
    buildCommand: pip install -r requirements.txt
    startCommand: python bot.py
