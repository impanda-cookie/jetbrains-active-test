# 注意: `对于version > 2018.1.x`产品本方法已被弃用，最新的套路请参照:https://www.imsxm.com/jetbrains-license-server.html , 纯属搬运，仅限学习.

# jetbrains-easy-active-test

本方式只是整理了[imsxm.com] 的套路，纯属搬运适用于习惯docker的懒人, 仅用于测试学习使用，商业请使用正版。 

# usage
``` 
docker run --name jetbrains-active-test -v <current_nginx.conf>:/etc/nginx/nginx.conf:ro -p 8888:80 -d nginx:alpine
```
# or
```
docker run -d --name  jetbrains-active-test -p 8888:80 cowpanda/jetbrains-active-test:latest
```

> 如果本方式未过期的话，在jetbrains的`license server` 中输入 `http://localhost:8888` 激活即可(_windowns/mac osx 则输入虚拟机所在IP_)
