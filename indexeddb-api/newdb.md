# 3.1 实例化数据库

{% hint style="info" %}
indexedDb需要实例化使用，并且携带数据库名与版本号来进行实例化
{% endhint %}

```javascript
const dbname = "code_db" // 数据库名 默认code_db
const version = 1 // 数据库版本
const codeDb = new Db(dbname, version) // 实例化数据库
```

