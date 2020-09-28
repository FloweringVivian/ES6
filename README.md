# ES6方法总结

### 删除数组元素

```javascript
let arr = ['a', 'b', 'c']
// 删除'c'
arr = arr.filter(i => {
    return i != 'c'
})
```

### $set

有些情况下，仅仅通过“=”号来赋值，无法触发数据的实时更新，这个时候用$set就可以。

```javascript
this.$set(obj, 'name', value);  //三个参数分别为对象、参数名、参数值
```

### 对象赋值不改变原对象

```javascript
let newObj = Object.assign({}, oldObj);
```

### 数组去重
```javascript
let myArray = [1,1,2,2,3,3,4,4,5,5]
[...new Set(myArray )];  // [1, 2, 3, 4, 5]
```

### forEach

### filter

### every



