初始化：
```bash
git clone 

cd elk

mkdir ./data

docker-compose build

docker-compose up -d

docker-compose exec -T elasticsearch bin/init_sg.sh
```

`build`镜像后集成安装[search-guard](https://search-guard.com/)提供http验证,执行以上三部后验证生效
