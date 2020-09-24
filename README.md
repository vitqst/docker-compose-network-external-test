# Up app truoc
```
cd app
docker-compose up -d
```

check service up thanh cong bang cach vo trang localhost:5000


# Up mysql
```
cd mysql
docker-compose up -d


## truy cap vao bash cua mysql
docker-compose exec db bash

## Install ping package
apt update 
apt install iputils-ping -y

## Kiem tra connect tu mysql container sang app container 
ping redis 

```
