## 使用说明
  * 使用webstorage时，如果需要存储复杂数据类型如对象类型，那么就需要先将对象类型转成JSON格式的字符串类型才能存储到webstorage中；从webstorage中取出复杂类型的数据后，为了方便操作，我们也会将其通过json.parse对数据进行解析。本工具对这些代码进行了封装，之后使用webstorage可以直接使用本工具，不必再写很多重复代码。

##npm
  * npm install hzz_storage
