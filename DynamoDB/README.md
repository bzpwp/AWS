This is the simple example of DynamoDB.

Write data.
```
python simple_write.py XXXX
```

Read data.
```
python simple_read.py XXXX
```

Write 1000 datas at the same time.
```
python batch_rw.py XXXX write 1000
```

Search data.
```
python batch_rw.py XXXX search_under_age 2
```