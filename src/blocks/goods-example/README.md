
# 介绍

> 商品展示组件，一行展示3个商品。

## 预览
![组件效果](image/snape1.png)
![在商品列表中的展示效果](image/snape2.png)
![参考网易严选中效果](image/snape3.png)

## 引用
```json
"usingComponents": {
  "em-goods": "path/to/blocks/goods-example/index"
}
```

## 案例

基本使用方法
```html
<em-goods value="{{goods}}" />
```

## 属性

| 属性 | 说明 | 类型 | 默认值 |
| --- | --- | --- | --- |
| value | 商品数据，数据结构参考说明文档。 | object | null |
| tag | 商品标签 | string, string[] | null |


## 事件

|事件名	| 说明 | 参数|
| --- | --- | --- |
|tap	| 点击商品 | goods:商品数据|
|taptag	| 点击商品标签 | tag:商品标签, index: 索引|