# 中国邮政编码 Postcodes of China

本数据库包含 37,257 个邮政编码，共计 1,844,219 条地址数据。(2016/10/11)

本数据库原始数据来源于互联网，不保证其准确性，可能含有并不仅限于以下错误：

* 邮编错误
* 地址错误
* 邮编遗漏
* 城市行政区划关系更新不及时
* 地址包含过多冗余及垃圾数据

希望大家共同维护。

----
本数据库使用5层Yaml作为原始数据格式，以方便数据文件的版本控制、比对，并减少文件大小。

```
省级行政区1:
    市级行政区1:
        区级行政区1:
            邮编1:
                - 地址1
                - 地址2
                - 地址3
                ...
            邮编2:
            ...
```

----

从原始数据生成数据库文件：

@TODO

## Todo List
- [ ] 香港特别行政区邮编
- [ ] 澳门特别行政区邮编
- [ ] 台湾省邮编
- [ ] 导出SQL脚本 (export script)
- [ ] 自动发布SQL (auto release)
- [ ] Contribute Guide
- [ ] 增量更新包

## 参考
- [中国邮政集团邮编查询地址]( http://www.cpdc.com.cn/web/index.php?m=postsearch&c=index&a=init&t=postcode)
- [国家统计局最新县及县以上行政区划代码(2015/9/30)](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/201608/t20160809_1386477.html)
