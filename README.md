<a target="_blank" href="https://heroku.com/deploy?template=https://github.com/pa2tie/mixstat_bot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a><br>

# MIX Stat TGbot

HI! I'll help you make a telegram bot for ProfitSocial and iMonetizeIt.

This bot:
1. Donwload .csv statistic for today/yesterday
2. Upload stat on Zoho sheets
3. Drop link in chat (today/yesterday - every 30 min)


How install:
1. You need account on <a href="heroku.com">heroku.com</a> and <a href="github.com">github.com</a>
2. Create Telegram bot in @BotFather and copy API key
3. Add @RawDataBot to your chat and copy chat_id
4. Click "Deploy to heroku" button on top and create new app (add name, choose region)
5. Go to "Setting" your app and click "Reveal Config Vars", then add variables:
<br>PROFIT_LOGIN = ProfitSocial authorization mail
<br>PROFIT_PASSWORD = ProfitSocial authorization password
<br>IMON_LOGIN = imonetizeit authorization mail
<br>IMON_PASSWORD = imonetizeit authorization password
<br>TG_TOKEN = api token your telegram bot
<br>CHAT_ID = chat id in telegram, where bot will drop lins
<br>LANGUAGE_MSG = language messages (RU or EN(default))
<br>TZ = your Time Zone, example: Europe/Moscow (view all zones https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
6. Choose "Resourses" tab, then OFF "web" switcher and ON all "worker" (logs in "More" > "View logs")
7. Add your bot in TG chat

WELL DONE!
