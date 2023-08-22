This is the simple example of Lambda.

Deploy
```
cdk deploy
```

expected output
```
SimpleLambda.FunctionName = XXXX
```

Execution
```
python invoke_one.py XXXX
```

Expected output
```
"Welcome to Cloud Sushi. Your order is squid"
```

By runnninn this, we can send 100 requessts at the same time.
```
python invoke_many.py XXXX 100
```