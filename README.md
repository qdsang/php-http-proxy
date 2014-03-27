php-http-proxy
==============

php版本的代理，用于test环境数据不给力，直接修改index.php 代理到公网~

修改下index.php文件，引入proxy.php文件

适合纯接口的项目

关键点，使用了mac系统的dig命令解析host对应主机ip，用于跳过系统host配置
