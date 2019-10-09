## 1、画三角：
```bush
-margin-left: -9px;
-border-width: 10px;
-border-style: solid;
-border-color: #00CAEF transparent transparent transparent;
```
## 2、空心圆
```bush
.base span::before {
    content: '';
    border-radius: 50%;
    position: absolute;
    height: 12px;
    width: 12px;
    border-color: red;
    border: 2px solid #3EC68B;
    outline-color: red;
}
<div class="base">
    <span></span>
</div>
```
## 按钮默认值文字居中
```.base .btn {
    height: 22px;
    width: 50px;
    border: 1px solid #FF8100;
    line-height: 20px;
    /*padding: 10px;*/
    color: #FF8100;
    font-size: 12px;
    border-radius: 2px;
    text-align: center;
    outline:0.5px;
}
<div class="base">
    <div class="btn">进行中</div>
</div>```
