
php版本较多，经常需要一些自定义扩展，所以采用自定义镜像
### 第一步
先制作php7.2的镜像
'''
cd myphp72
docker build -t myphp72 . 
'''
如果有更多php版本这里修改dockerfile即可

### 第二步
'''
docker-compose up -d
'''

默认MySQL的root密码root