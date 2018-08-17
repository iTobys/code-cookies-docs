# 2.1 新增Storage

## Usage - getCookies\(\)

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

1.  @params =&gt; keyname 需要查询cookies的key值  
2.  @params =&gt; local 切换LocalStorage, 默认为false 



