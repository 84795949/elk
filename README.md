初始化：
git clone 

cd elk

docker-compose build

docker-compose up -d

docker-compose exec -T elasticsearch bin/init_sg.sh

build镜像后集成安装search-guard提供http验证,执行以上三部后验证生效
