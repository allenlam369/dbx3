
CONTAINER ID   IMAGE                         COMMAND                  CREATED         STATUS         PORTS                                                            NAMES
e4619c8af556   postgres                      "docker-entrypoint.s…"   5 minutes ago   Up 2 minutes   5433/tcp, 0.0.0.0:5433->5432/tcp, :::5433->5432/tcp              db_postgres_1
bc535dcac907   mongo                         "docker-entrypoint.s…"   5 minutes ago   Up 2 minutes   27018/tcp, 0.0.0.0:27018->27017/tcp, :::27018->27017/tcp         db_mongo_1
2ef7c6a4d196   phpmyadmin/phpmyadmin:5.0.1   "/docker-entrypoint.…"   5 minutes ago   Up 2 minutes   8081/tcp, 0.0.0.0:8081->80/tcp, :::8081->80/tcp                  db_myadmin_1
3dde023a1e28   mysql:8.0.19                  "docker-entrypoint.s…"   5 minutes ago   Up 2 minutes   3307/tcp, 33060/tcp, 0.0.0.0:3307->3306/tcp, :::3307->3306/tcp   db_mysql_1


