# 3.2 打开数据库

## Usage - openDb\(\) {#usage-cleansession}

```javascript
const createStorage = [
    {
        name: 'name',
        isUnique: true
    },{
        name: 'age', // 数据库字段名
        isUnique: false  // 数据是否支持重复
    }
]

codeDb.openDb(name, key, createStorage).then(res => {    
    // todo    
    console.log(res)
}).catch(err => {
    // err
    console.log(err)
})
```

需要参数:

1.  @params =&gt; name 数据表名
2.  @params =&gt; key 数据表主键 默认为id
3.  @params =&gt; createStorage 数据库表字段名，结构与变量createStorage一致

​

