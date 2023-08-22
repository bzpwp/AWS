The example of s3.

uploads file
```
echo "Hello world!" >> tmp.txt
python simple_s3.py XXXX upload tmp.txt
```

downloads file
```
python simple_s3.py XXXX download tmp.txt
```