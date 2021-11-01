### 配列の重複要素を取り除く

```
const arr = ["A", "B", "B", "B", "c", "c", "c"];
const removeDuplicates = (arr) => [...new Set(array)];

removeDuplicates(arr);

// ["A", "B", "C"]
```

### 平均を返す

```
const average = arr => arr.reduce((acc, current) => acc + current) / arr.length;

average([10, 15, 24, 32, 55]);

// 27.2
```