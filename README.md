# redis-jedis-test

redis-server /usr/local/etc/redis.conf

```
==> Downloading https://homebrew.bintray.com/bottles/redis-3.2.8.sierra.bottle.2.tar.gz
######################################################################## 100.0%
==> Pouring redis-3.2.8.sierra.bottle.2.tar.gz
==> Caveats
To have launchd start redis now and restart at login:
  brew services start redis
Or, if you don't want/need a background service you can just run:
  redis-server /usr/local/etc/redis.conf
==> Summary
🍺  /usr/local/Cellar/redis/3.2.8: 11 files, 1.7MB
zhangxilais-MacBook-Pro:maps Philip$ redis
-bash: redis: command not found
zhangxilais-MacBook-Pro:maps Philip$ redis-server /usr/local/etc/redis.conf
63349:M 20 Apr 17:06:01.735 * Increased maximum number of open files to 10032 (it was originally set to 256).
                _._                                                  
           _.-``__ ''-._                                             
      _.-``    `.  `_.  ''-._           Redis 3.2.8 (00000000/0) 64 bit
  .-`` .-```.  ```\/    _.,_ ''-._                                   
 (    '      ,       .-`  | `,    )     Running in standalone mode
 |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
 |    `-._   `._    /     _.-'    |     PID: 63349
  `-._    `-._  `-./  _.-'    _.-'                                   
 |`-._`-._    `-.__.-'    _.-'_.-'|                                  
 |    `-._`-._        _.-'_.-'    |           http://redis.io        
  `-._    `-._`-.__.-'_.-'    _.-'                                   
 |`-._`-._    `-.__.-'    _.-'_.-'|                                  
 |    `-._`-._        _.-'_.-'    |                                  
  `-._    `-._`-.__.-'_.-'    _.-'                                   
      `-._    `-.__.-'    _.-'                                       
          `-._        _.-'                                           
              `-.__.-'                                               

63349:M 20 Apr 17:06:01.758 # Server started, Redis version 3.2.8
63349:M 20 Apr 17:06:01.759 * The server is now ready to accept connections on port 6379
```
