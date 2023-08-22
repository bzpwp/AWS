This is a simple example of starting ECS.

This bot uses natural language processing to provide simple responses.

Use this docker image for response.

```
"tomomano/qabot:latest"
```

This is deployed by FARGATE.

By runnning ```run_task.py```, we can get response.

```
python run_task.py ask "John is playing with Karen." "Who is Karen playing with?"
```

expected output
```
Answer: John
Score: 0.9946632385253906
```

By running this, multiple questions defined in problems.json can be asked simultaneously.
```
python run_task.py ask_many
```

