RedisJsonv2.8.3
Not compatible with keydb

## split so file
```
split -b 15m librejson.so librejson-part-
```

## concat so file
```
cat librejson-part-* > librejson.so
```
