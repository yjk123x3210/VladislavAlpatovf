# 说明

此文件夹为表单组件配置文件

- url: 属性的说明地址
- common: 代表通用配置, 例如 `default`、`options`等, 具体参考: [formDesc 表单描述](https://www.yuque.com/chaojie-vjiel/vbwzgu/iw5dzf)
- attrs: 组件自身属性, 例如 `input` 组件有`maxlength`、`clearable`、`prefix-icon`等, 具体各个属性, 请参考[type 类型列表 第三列属性说明](https://www.yuque.com/chaojie-vjiel/vbwzgu/kz163g)
- attrsDefaultData: 组件自身属性的默认值
- commonDefaultData: 通用配置的默认值
- assistProperty: 辅助属性, 用于判断类型, 展示数据时, 当删除此属性

> tip: `attrs` 默认值, 有两个`attrsData`和`attrsDefaultData`, 原因是当默认值未发生变化时, 有的无需向用户展示, 需要删除, 有的必须有, 所有才区分两者, 同理 `common` 也是
