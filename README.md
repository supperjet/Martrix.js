# Martrix.js
canvas黑客帝国特效插件
### 1、Feature
1. 使用原生canvas，不需依赖任何外部插件
1. 支持`AMD`&&`CMD`规范

### 2、Install&&Useage
下载文件引入`martrix.js`或`martrix.min.js`文件

```bash
 <canvas id="canvas" style="background:#000">
       your browser not support canavs
   </canvas>
   
   <script>
       martrix('canvas', {
           cW: 1390,
           cH: 700,
           wordColor: '#FFFC3A',
           fontSize: 13,
           speed: 0.13,
       });
```

###3、DEMO
[运行test.html](http://codepen.io/supperjet/pen/JbqZPK)

![](Imgs/demo.png)

###4、Configure
|   属性  |   类型  | 默认值 |   描述   |
|--------|-------- |-------|-------- |
|cW| Number| 1367  |canvas宽度|
|cH| Number| 700  |canvas高度|
|wordColor| String | '#33ff33' |文字颜色|
|fontSize| Number| 15|文字大小|
| speed| Number | 0.13  |下落速度|
|words| String | ”0123456...“ |文字|


###5、Supports browser
- IE 10+
- Chrome
- Firefox
- Opera
- Safari
