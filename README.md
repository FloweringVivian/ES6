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

### 对象赋值不改变原对象

```javascript
Object.assign()
```
