## 数据过大问题
有时候，提交的数据量过大会导致问题。尝试通过以下命令增大 Git 的缓存：

git config --global http.postBuffer 157286400

# odoo-compose

## 安装教程

## ubtunu安装docker

### 1.  docker-compose
设置好yaml文件配置后执行以下命令。
建议创建以下文件路径：
../odoo/odoo16
../odoo/odoo-compose

备份路径：
../odoo
自动创建backup文件夹

社区版安装
```
docker-compose -f compose-portainer.yaml -p compose-portainer up -d
docker-compose -f compose-portainer-local.yaml -p compose-portainer-local up -d


docker-compose -f docker-compose.yaml -p odoo17 up -d
docker-compose -f docker-compose.yaml -p odoo17pg15 up -d
docker-compose -f docker-compose.yaml -p aosone17pg15 up -d
docker-compose -f docker-compose.yaml -p aos17pg15 up -d
docker-compose -f docker-compose.yaml -p cover17pg15 up -d

docker-compose -f docker-compose.yaml -p odoo18 up -d


docker-compose -f docker-compose-cover.yaml -p cover17pg15 up -d

docker-compose -f docker-compose-cover-t.yaml -p covertt17pg15 up -d

docker-compose -f docker-compose-cover-t.yaml -p covertttt17pg15 up -d




docker-compose -f docker-compose-ce-s.yaml -p aosce17pg15 up -d
docker-compose -f docker-compose-ce-s-1.yaml -p aosce17pg15-1 up -d
docker-compose -f docker-compose-ce-s.yaml -p coverce17pg15 up -d


docker-compose -f docker-compose-ce-nginx-certbot-truebuy-com-cn.yaml -p aosce17pg15nginxcertbot up -d
docker-compose -f docker-compose-ce-addons.yaml -p aosce17pg15base up -d
docker-compose -f docker-compose-posgresql.yaml -p pg15 up -d



docker-compose -f docker-compose-local.yaml -p odoo17pg15 up -d
docker-compose -f docker-compose-local.yaml -p odoo17pg15-1 up -d
docker-compose -f docker-compose-local.yaml -p aosone17 up -d


docker-compose -f docker-compose-community.yaml -p aos17c up -d

docker-compose -f docker-compose-minio-local.yaml -p aos17minio up -d



```
企业版
```
docker-compose -p odoo16-compose up -d
```
### 2.  安装DOCKER
#### 2.1 ubuntu部署
#### 2.2 mac部署
### 3. compose 的配置说明 

## 使用说明

1.  数据备份：copy env.sample to .env, 数据备份的路径
2.  如果出现权限受限不能备份，则给文件夹进行写入权限

## 参与贡献

docker exec -it --user root 59f6cbbcb817 /bin/bash

docker exec -it --user root 9d2071293bbd0352dbe192936a81c445cc253a7840005a72d4dd5faad9896bda /bin/bash

/lib/python3/dist-packages/odoo/addons/web/static/src/core/utils/files.js

docker commit -m "add python pkg" d731d50a48a6 redblow/aosone:17.0

docker commit d731d50a48a6 redblow/aosone:17.0

docker tag d731d50a48a6 redblow/odoo:17.0

docker tag d731d50a48a6 redblow/aosone:17.0

```
基础功能：
auth_totp  base  base_import  base_import_module  base_setup  bus  iap  web  web_editor  web_tour  web_unsplash

cd /lib/python3/dist-packages/odoo

```

```
pg_restore -U odoo -W -d covertop -1 /Users/aos/covertop.dump

恢复文本格式的备份
psql -U odoo -f /Users/aos/covertop covertop.net.513

恢复docker部署的pg数据库文件的方法
docker network create cover17pg15restore
docker network connect cover17pg15restore 535510dfb2e89454f66872cf8e0756f87a7a0b2afaf4b508a943467a5e86db26
docker run -it --rm --name my-postgres --network cover17pg15restore postgres:15 bash
docker run -it --rm --name my-postgres-restore --network cover17pg15restore \
  -v /Users/aos/projects/odoo/odoo/backups/:/mnt/backup/ \
  -e PGPASSWORD=PGPASSWORD \
  -e PGHOST=535510dfb2e8 \
  -e PGPORT=5432 \
  -e PGDATABASE=postgres \
  postgres:15 bash

备份的是文本文件使用以下命令
psql -U odoo -f /mnt/backup/cover17 cover17
psql -U odoo -d cover17 -f /mnt/backup/cover17
psql -U odoo -f /mnt/backup/cover1702 cover17


dump文件使用以下命令
pg_restore -U odoo -d cover17 -1 /mnt/backup/covertop17.dump
```

```
docker network create cover17pg15restore
docker network connect cover17pg15restore 18e874ff7148
docker run -it --rm --name my-postgres-restore --network cover17pg15restore \
  -v /home/mt/aos/17/odoo/backups/:/mnt/backup/ \
  -e PGPASSWORD=PGPASSWORD \
  -e PGHOST=18e874ff7148 \
  -e PGPORT=5432 \
  -e PGDATABASE=postgres \
  postgres:15 bash

备份的是文本文件使用以下命令
创建一个空数据库
createdb -U odoo cover.aos.one
psql -U odoo -f /mnt/backup/cover1702 cover.aos.one

docker exec -it --user root e3285a5547dc /bin/bash


```




UncaughtClientError > TypeError
Uncaught Javascript Error > Cannot set properties of null (setting 'innerHTML')
TypeError: Cannot set properties of null (setting 'innerHTML')
    at http://localhost:9169/web/assets/aefad20/web.assets_web.min.js:19271:710



## 创建一个空模块的命令
```angular2html
./odoo-bin scaffold wechat_oauth odoo/addons-3rd/
./odoo-bin scaffold products_recorder odoo/addons-3rd/
./odoo-bin scaffold loyalty_third_provider odoo/addons-3rd/mobilesite/
./odoo-bin scaffold mobilesite_sale odoo/addons-3rd/mobilesite/
./odoo-bin scaffold loyalty_plan odoo/addons-3rd/mobilesite/
./odoo-bin scaffold logistics_management odoo/addons-3rd/mobilesite/
./odoo-bin scaffold account_bank_statement_line odoo/addons-3rd/mobilesite/

./odoo-bin scaffold mobilesite_helpdesk ../../odoo18addons/addons-3rd/mobilesite/
./odoo-bin scaffold mobilesite ../odoo18addons/addons-3rd/mobilesite/



```

```

docker exec -it --user root 69cff0bedecb /bin/bash


```

### 取消恢复数据的尺寸限制
#### odoo/addons/web/controllers/database.py

```angular2html
@http.route('/web/database/restore', type='http', auth="none", methods=['POST'], csrf=False, max_content_length=None)

```





docker-compose -f docker-compose.yaml -p cover1796pg15 up -d

docker exec -it --user root 6b0a2a2dea694461c13c4c5857ed93016362124471aec68ef09cc85bb6201fdf /bin/bash

docker exec -it --user root de4f329698a2469334873ab969da70630ff54722f623b763cb358662d0cecca0 /bin/bash

docker commit coverce17pg15-web-1 redblow/aos:17.9.6