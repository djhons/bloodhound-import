# bloodhound-import
直接把bloodhound数据导入neo4j

## 代码来源

`https://github.com/fox-it/bloodhound-import`

## 支持的版本

`https://github.com/BloodHoundAD/SharpHound`这个是bloodhound5的数据采集器，不支持bloodhound4,采集数据请用`https://github.com/BloodHoundAD/BloodHound/tree/master/Collectors` 
这个导入脚本应该也不支持bloodhound5

## 用法

```
python main.py --database 192.168.66.190 -p 7687 -du neo4j -dp 123456 20230812170033_computers.json
```
