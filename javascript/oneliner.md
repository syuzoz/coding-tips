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

### URLからパラメータークエリを取得

```
const getParameters = (URL) => {
  const query = JSON.parse('{"' + decodeURI(URL.split("?")[1]).replace(/"/g, '\\"').replace(/&/g, '","').replace(/=/g, '":"') +'"}');
  return JSON.stringify(query);
}

getParameters("https://www.google.com/search?q=hoge&hl=ja")

// {"q":"hoge","hl":"ja"}
```