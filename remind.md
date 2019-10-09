## 1、画三角：
```margin-left: -9px;
border-width: 10px;
border-style: solid;
border-color: #00CAEF transparent transparent transparent;```
## 2、空心圆
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
