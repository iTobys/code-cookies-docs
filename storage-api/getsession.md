# 2.1 新增Storage

## Usage - setSession\(\)

```javascript
Storage.setSession(name, val, local).then(res => {
    // todo
    console.log(res)
}).catch(err => {
    // err
    console.log(err)
})
```

需要参数:

1.  @params =&gt; name 需要设置Session的key值  
2.  @params =&gt; val 需要设置的Session的val值
3.  @params =&gt; local 切换LocalStorage, 默认为false 



