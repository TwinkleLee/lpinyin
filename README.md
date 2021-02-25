# lpinyin
用于首字母/全拼音的模糊查询

# 使用说明
```
import lpinyin from "lpinyin";

var obj_arr = [
  { name: "张三", age: 18 },
  { name: "李四", age: 20 },
  { name: "家乐福", age: 100 },
];
var filterData = new lpinyin(obj_arr, "name").query("jiayuef",2);
// 0(默认) 首字母+全拼
// 1 首字母
// 2 全拼
//输出{ name: "家乐福", age: 100 }
```