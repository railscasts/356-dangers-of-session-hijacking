# RailsCasts Episode #356: Dangers of Session Hijacking

http://railscasts.com/episodes/356-dangers-of-session-hijacking

Requires Ruby 1.9.2 or higher.


### Commands used in rails console

```
sudo tcpdump -i lo0 -A
curl http://todo.dev/
curl http://todo.dev/ -H 'Cookies: ...'
curl https://todo.dev/ -k -H 'Cookies: ...'
```
