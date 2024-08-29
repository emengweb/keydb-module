## split so file
```
split -b 15m librejson.so librejson-part-
```

## concat so file
```
cat librejson-part-* > librejson.so
```
