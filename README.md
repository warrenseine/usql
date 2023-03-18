# usql

Binary for [usql](https://github.com/xo/usql), ready to download.

To download:

```shell
wget -q -O usql https://github.com/warrenseine/usql/raw/main/usql_static
```

or

```shell
curl -s -o usql https://github.com/warrenseine/usql/raw/main/usql_static
```

Then connect:

```shell
chmod +x usql
./usql pg://$PGHOST/$PGDATABASE
```
