# football
足球圈H5跨平台

##  时间线
2017-2-10迁移到lnmp
2017-2-12完成迁移到lnmp环境
2017-2-13phpframework
## 安装CentOS7.1配置环境的问题
   -  安装路径问题
   -- U盘安装CentOS要配置引导路径
   -  yum install mysql
   -- 这里因mysql被甲骨文收购，源里没有mysql用mariadb代替
   - yum install php-fpm nginx
   - nginx 403 502 500 304
   - 403:权限注意文件夹755 文件644 502:PHP-fpm状态 500:PHP代码或PHP-mysql 304:文件未改变传回304 ：尽量避免 搜索引擎排名
   - 403：静态都403可能SElinux安全策略 暂停getenforce 0
   - nginx-> fastcgi<=>php-fpm->php<->mysql 


  * 使用__struct()构造方法里连接数据库，写了mysql.class 2-13 
  * explode() string->array 参数1分隔符 参数2string 
  * implode() arrary->string 参数1粘合符 参数2arrary 
  * 参数3.limit 分正负 意义为分割到正数/倒数第几个 
  * 2
