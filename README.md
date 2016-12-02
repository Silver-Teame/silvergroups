silver team
commands list :دستورات سوپرگروه

!kick {username/id}
اخراج فرد با دستور در سوپر گروه

!ban {username/id}
بن کردن فرد در سوپر گروه

!unban {username/id}
ان بن کردن فرد در سوپرکوره

!who 
مشاهده لیست کل اعضای سوپرگروه

!modlist
مشاهده لیست مدیران 

!promote {username/id}
افزودن فرد به لیست مدیران 

!demote {username/id}
حذف فرد از لیست مدیران

!kickme
اخراج خود از سوپرگروه

!abote
فزودن متن درباره سوپر گروه

!setphoto
عوض کردن عکس سوپر گروه

!setname {newname}
عوض کردن اسم سوپرگروه

!rules
دریافت قوانین گروه 

!id
مشاهده ایدی سوپرگروه یا فرد 

!lock {links/spam/bots/leave...}
قفل کردن تنظیمات

!unlock {links/spam/bots/leave...}
باز کردن قفل تنظیمات

!set rules {text}
عوض کردن قوانین سوپرگروه

!set about {text}
عوض کردن درباره گروه

!settings
دریافت تنظیمات قفل ها

!newlink
ساخت لینک جدید

!link 
دریافت لینک سوپرگروه

!owner
مشاهده ایدی صاحب گروه

!setowner
انتخاب فرد به عنوان صاحب گروه

!setflood [value]
تنظیم حساسیت اسپم

!clean [modlist|rules|about]
پاک کردن تنظیمات

!res {username}
به دست اوردن ایدی فرد

!banlist 
لیست افراد بن شده

!log
لیست ورود اعضا

------------------------------------------------
تهسه شده در تیم برنامه نویسی سیلور 
@silver_team

مدیران میتوانند بجای استفاده از 
! 
از دستوراتی دیگر مانند 
{/و#و!}
استفاده کنند 


# Installation دستورات نصب

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make autoconf unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

cd $HOME

git clone https://github.com/silver-teame/silvergroups.git

cd silvergroups

chmod +x launch.sh

./launch.sh install

./launch.sh
# Enter a phone number & confirmation code.
```

#https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev libjansson* libpython-dev make autoconf unzip git redis-server g++ -y --force-yes && git clone https://github.com/SEEDTEAM/TeleSeed.git && cd TeleSeed && chmod +x launch.sh && ./launch.sh install && ./launch.sh
```
### Realm configuration

After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:
```
  sudo_users = {
   105413662
   ایدی بالارا پاک کنید و ایدی خودتونو وارد کنید
  }
```
Then restart the bot.

