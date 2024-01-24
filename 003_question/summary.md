### 水平垂直居中方法

1. flex布局设置居中

父元素
```css
display:flex;
align-items: center; // 垂直居中
justify-content:center;// 水平居中 
height: 100%;
```

2. flex-margin

```css
.box {
  width: 200px;
  height: 200px;
  border: 1px solid;
  display: flex;
}
.child {
  margin: auto; // 水平垂直居中
}
```

3. 绝对定位

```css
.box {
  position: relative;
}
.child {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}  
```

4. grid设置居中

```css
.box {
  display: grid;
  align-items: center;
  justify-content: center;
}
```

5. grid-margin

```css
.box {
 display: grid;
}
.child {
 margin: auto;
}  
```

### [条纹背景](https://www.cnblogs.com/lpkshuai/p/17337854.html)