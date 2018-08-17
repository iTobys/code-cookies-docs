# 2.3 删除指定Storage

## Usage - delSession\(\)

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

1.  @params =&gt; name 需要删除session的key值  
2.  @params =&gt; local 切换LocalStorage, 默认为false 



