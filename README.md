# MyCassandra

My Cassandra

## Use Cassandra with Docker in Windows

`docker compose up`

### CLI - CQL Shell

`docker exec -it rockthejvm-sparkstreaming-cassandra cqlsh`

```dos
create keyspace public with replication = { 'class': 'SimpleStrategy', 'replication_factor': 1 };
create table public.cars("Name" text primary key, "Horsepower" int);
select * from public.cars;
```

![1671900442590](image/README/1671900442590.png)

![1671900653879](image/README/1671900653879.png)

Unfortunately IntelliJ free version doesn't support Cassandra as of today.

### DataStax Studio

It needs Java 8.

```dos
C:\Apps\datastax-studio-6.8.21\bin>server.bat
Starting Studio. This may take a few minutes. You will be notified here when Studio is ready.


Looking for Java in C:\apps\jdk-11.0.16.1\
Java version located 11.0
ErrorCodes: Studio requires Java 8. Java version: 11.0 is not supported.
done.
```

## Use Cassandra with Docker in Mac

## Reference
