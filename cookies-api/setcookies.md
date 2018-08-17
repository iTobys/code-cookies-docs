# 1.2 新增cookies

## Usage - setCookies\(\)

```javascript
Cookies.setCookies(keyname, value, vEnd, infinity = true).then(res => {
    // todo
    console.log(res)
}).catch(err => {
    // err
    console.log(err)
})
```

需要参数:

1. @params =&gt; keyname 需要新增cookies的key值  
2. @params =&gt; value 需要新增的cookies的value值
3. @params =&gt; vEnd cookies过期时间，默认7200秒，支持传入new Date\(\)以及数字（毫秒）
4. @params =&gt; infinity 是否永久缓存，默认为false



