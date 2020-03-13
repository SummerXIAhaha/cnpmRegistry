cnpmjs.org


* 本地搭建私有npm
* 参考文章： [(https://blog.csdn.net/qq_37477349/article/details/88304769)]

* 主要问题：
1. 创建数据库，需在根目录下执行，通过source docs/db.sql的sql语句初始化需要数据
2. registryHost配置项很重要，如果只是本地下载配置127.0.0.1即可，如果外网下载，那么配置公网内本机IP即可。
3. 发版的包可采取@cnpm/name的形式

