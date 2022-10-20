```/etc/apt/sources.list```
```
# 海外源(香港科技大学)
# 把域名替换掉
https://mirror.xtom.com.hk
# 国内源(腾讯云)
http://mirrors.tencent.com
```

### debian 10
```
deb http://mirrors.tencent.com/debian/ buster main non-free contrib
deb-src http://mirrors.tencent.com/debian/ buster main non-free contrib
deb http://mirrors.tencent.com/debian-security buster/updates main
deb-src http://mirrors.tencent.com/debian-security buster/updates main
deb http://mirrors.tencent.com/debian/ buster-updates main non-free contrib
deb-src http://mirrors.tencent.com/debian/ buster-updates main non-free contrib
deb http://mirrors.tencent.com/debian/ buster-backports main non-free contrib
deb-src http://mirrors.tencent.com/debian/ buster-backports main non-free contrib
```

### debian 11
```
deb http://mirrors.tencent.com/debian/ bullseye main non-free contrib
deb-src http://mirrors.tencent.com/debian/ bullseye main non-free contrib
deb http://mirrors.tencent.com/debian-security/ bullseye-security main
deb-src http://mirrors.tencent.com/debian-security/ bullseye-security main
deb http://mirrors.tencent.com/debian/ bullseye-updates main non-free contrib
deb-src http://mirrors.tencent.com/debian/ bullseye-updates main non-free contrib
deb http://mirrors.tencent.com/debian/ bullseye-backports main non-free contrib
deb-src http://mirrors.tencent.com/debian/ bullseye-backports main non-free contrib
```

### ubuntu20.* LTS
```
deb http://mirrors.tencent.com/ubuntu/ focal main restricted universe multiverse
deb-src http://mirrors.tencent.com/ubuntu/ focal main restricted universe multiverse
deb http://mirrors.tencent.com/ubuntu/ focal-security main restricted universe multiverse
deb-src http://mirrors.tencent.com/ubuntu/ focal-security main restricted universe multiverse
deb http://mirrors.tencent.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src http://mirrors.tencent.com/ubuntu/ focal-updates main restricted universe multiverse
#deb http://mirrors.tencent.com/ubuntu/ focal-proposed main restricted universe multiverse
#deb-src http://mirrors.tencent.com/ubuntu/ focal-proposed main restricted universe multiverse
deb http://mirrors.tencent.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src http://mirrors.tencent.com/ubuntu/ focal-backports main restricted universe multiverse
```
