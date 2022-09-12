- Устоновка userbot telegram для termux
1. Робимо config.ini
```
[pyrogram]
api_id =
api_hash =
```
2. Робимо config.ini для telegram premium (у кого є):
```
[pyrogram]
api_id_premium =
api_hash_premium =
```
3. Відкриваємо termux і пишимо таку команду:
```
apt update -y && apt upgrade -y && termux-setup-storage && pkg install python && python -m pip install pip --upgrade && python -m pip install pyrogram && python -m pip install tgcrypto
```
4. На сайті [Telegram](https://my.telegram.org/auth)