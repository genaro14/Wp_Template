# Utils
## DB Scripts
### Dump
```
$ docker exec database mysqldump wordpress --password=wordpress  > ./dump/db.dump
```
### Restore
```
$ docker exec -i database mysql -u root -pwordpress wordpress < ./dump/db.dump

```