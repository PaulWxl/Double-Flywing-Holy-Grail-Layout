# 测试 双飞翼布局

总结： 1、 先给三个加一个容器，然后容器设置左右的padding， **然后left 和 right 设置 width 的 值 正好 为 容器 的 padding 的 左右的值**

2、 绝对定位(子绝父相) left right 各自定位到对应的位置上去。

```
.left {
        top: 0;
        left: 0;
    }
    .right {
        top: 0;
        right: 0
    }
```


3、 中间 center 高度自适应 可以用

```
height: 100%
```
