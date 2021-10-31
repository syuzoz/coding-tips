### 配列の重複要素を取り除く

```
const array = ["A", "B", "B", "B", "c", "c", "c"];
const uniques = [...new Set(array)];
=> ["A", "B", "C"]
```