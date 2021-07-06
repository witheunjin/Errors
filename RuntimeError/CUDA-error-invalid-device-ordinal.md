# CUDA Error 1
Project Name
```
NCF-PT_ejlee
```

Error Message
```
RuntimeError: CUDA error: invalid device ordinal
```

SOLUTION
```
Change GPU Device Number (src/train.py Line 59)
7 to 0
```
