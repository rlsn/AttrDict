# AttrDict
 An attribute dictionary that's very handy everywhere

### main usage
key = attribute
```
dic = AttrDict(a=1,b=2)
dic.c = 3
print(dic.b)
```

### json file support
```
dic.to_json(filename) # save
dic = AttrDict.from_json(filename) # load
```
