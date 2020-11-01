# NakamaDockerCompose
# This is what i have so far with my docker compose file

# It's nakama is given this error

nakama        | + /nakama/nakama migrate up --database.address+  root@localhost:26257?sslcert=crdbcerts/client.root.crt 

nakama        | + sslrootcert=crdbcerts/ca.crt 

nakama        | + /nakama/nakama migrate up --database.address root@roach-0:26257 

nakama        | sslkey=crdbcerts/client.root.key 

nakama        | + sslmode=verify-full 

nakama        | {"level":"info","ts":"2020-11-01T22:51:37.050Z","caller":"migrate/migrate.go:139","msg":"Database 
connection","dsn":"root@localhost:26257?sslcert=crdbcerts/client.root.crt"} 

nakama        | {"level":"fatal","ts":"2020-11-01T22:51:37.051Z","caller":"migrate/migrate.go:147","msg":"Error pinging database","error":"dial tcp 127.0.0.1:26257: 
connect: connection refused"} 

nakama        | {"level":"info","ts":"2020-11-01T22:51:37.054Z","caller":"migrate/migrate.go:139","msg":"Database connection","dsn":"root@roach-0:2625, it's saying          

nakama        | + /nakama/nakama migrate up --database.address+  root@localhost:26257?sslcert=crdbcerts/client.root.crt 

nakama        | + sslrootcert=crdbcerts/ca.crt 

nakama        | + /nakama/nakama migrate up --database.address root@roach-0:26257 

nakama        | sslkey=crdbcerts/client.root.key 

nakama        | + sslmode=verify-full 

nakama        | {"level":"info","ts":"2020-11-01T22:51:37.050Z","caller":"migrate/migrate.go:139","msg":"Database connection","dsn":"root@localhost:26257?sslcert=crdbcerts/client.root.crt"} 

nakama        | {"level":"fatal","ts":"2020-11-01T22:51:37.051Z","caller":"migrate/migrate.go:147","msg":"Error pinging database","error":"dial tcp 127.0.0.1:26257: connect: connection refused"} 

nakama        | {"level":"info","ts":"2020-11-01T22:51:37.054Z","caller":"migrate/migrate.go:139","msg":"Database connection","dsn":"root@roach-0:26257"} 

nakama        | {"level":"fatal","ts":"2020-11-01T22:51:37.055Z","caller":"migrate/migrate.go:147","msg":"Error pinging database","error":"ERROR: node is running secure mode, SSL connection required (SQLSTATE 08P01)"}7"} 

nakama        | {"level":"fatal","ts":"2020-11-01T22:51:37.055Z","caller":"migrate/migrate.go:147","msg":"Error pinging database","error":"ERROR: node is running secure mode, SSL connection required (SQLSTATE 08P01)"}
