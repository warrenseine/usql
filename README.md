# usql

Binary for [usql](https://github.com/xo/usql), ready to download.

To connect to Postgres:

```shell
wget -q -O usql https://github.com/warrenseine/usql/raw/main/usql_static
chmod +x usql
./usql pg://$PGHOST/$PGDATABASE
```

or

```shell
curl -s -o usql https://github.com/warrenseine/usql/raw/main/usql_static
chmod +x usql
./usql pg://$PGHOST/$PGDATABASE
```

or

```python
python3 -c "from urllib.request import urlretrieve; urlretrieve('https://github.com/warrenseine/usql/raw/main/usql_static', 'usql')"
chmod +x usql
./usql pg://$PGHOST/$PGDATABASE
```
