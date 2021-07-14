# 备份bot

'docker cp /home/ql0/set.json qinglong:/ql/jbot/'
docker cp /home/ql0/getcookie.py qinglong:/ql/jbot/bot/
docker exec -it qinglong bash
ps -ef
kill 1234
python3 -m jbot

docker cp /home/ql0/set.json qinglong0:/ql/jbot/
docker cp /home/ql0/getcookie.py qinglong0:/ql/jbot/bot/
docker exec -it qinglong0 bash
ps -ef
kill 1234
python3 -m jbot

nohup python3 -m jbot >/dev/null 2>&1 &
