# centos7test
russtlt@servirt:~/data/centos7test$ docker ps
CONTAINER ID        IMAGE                     COMMAND                  CREATED             STATUS              PORTS                                            NAMES
47bb349cef3f        centos_nginx              "/usr/sbin/nginx -..."   2 hours ago         Up 2 hours          0.0.0.0:8088->80/tcp                             centos_nginx_1
bb9cea4c390f        php-test-app              "container-entrypo..."   2 hours ago         Up 2 hours          0.0.0.0:8443->8443/tcp, 0.0.0.0:8800->8080/tcp   centos_php_1
2a8cb6b45234        centos_phpmyadmin         "/run.sh superviso..."   2 hours ago         Up 2 hours          8080/tcp, 9000/tcp, 0.0.0.0:8082->80/tcp         centos_phpmyadmin_1
d0dd8cc75937        centos/mysql-57-centos7   "container-entrypo..."   2 hours ago         Up 2 hours          0.0.0.0:3306->3306/tcp                           centos_db_1
3f5758149746        centos/redis-32-centos7   "container-entrypo..."   12 hours ago        Up 2 hours          0.0.0.0:6379->6379/tcp                           centos_redis_1

http://russtlt.ddns.net:8088/ nginx
http://russtlt.ddns.net:8800/ phpinfo
http://russtlt.ddns.net:8082/ phpmyadmin

