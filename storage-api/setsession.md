# 2.2 获取Storage

## Usage - getSession\(\)

```javascript
Storage.getSession(name, local).then(res => {
    // todo
    console.log(res)
}).catch(err => {
    // err
    console.log(err)
})
```

需要参数:

1.  @params =&gt; name 需要查询session的key值  
2.  @params =&gt; local 切换LocalStorage, 默认为false 



