## 移动端解决方案

**边框`1px`**

* 缩放
* `viewport`

**点击穿透**

* 请勿混用`touch`和`click`事件

**`click`延迟**

* `fastClick`库

**部分机型输入法遮挡元素问题**

* `scrollIntoViewNeeded`
* 通过`JavaScript`控制

**关闭`ios`手机自动识别**

```html
<meta name="format-detection" content="telephone=no" />
```

**关闭`ios`表单获得焦点时自动放大**

```html
<meta name="apple-mobile-web-app-capable" content="yes"> 
```

**设置理想视口**

```html
<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no"> 
```

**清除`ios`表单元素内阴影**

```css
input {
    -webkit-appearance: none;
}
```

**禁止安卓识别`email`**

```html
<meta content="email=no" name="format-detection" />
```

**禁止`ios`弹出操作窗口**

```css
a {
	-webkit-touch-callout: none
}
```

**禁止选中文字**

```css
html {
    -webkit-user-select: none
}
```

**开启硬件加速**

```css
.cube {
	transform: translate3d(0, 0, 0)
}
```

**清除点击高亮效果**

```css
button {
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
```

**解决`ios`无法滑动**

```css
.scroll {
    -webkit-overflow-scrolling: touch;
}
```

**布局解决方案**

* 百分比
* `flex`
* `rem`
* `vw`/`vh`