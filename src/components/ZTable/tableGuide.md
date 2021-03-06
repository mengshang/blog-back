###使用说明
1、参数

| 参数名 | 类型 | 说明 | 可选值| 默认值 |
| :------| :------ | :------ | :------ | :------ |
| tableHeader | Array | 表格头部数据 | — | — |
| tableData | Array | 表格显示的数据，见下表 | — | — |
| tableHeight | String | 表格高度 | — | auto |
| tableBorder | Boolean | 表格边框 | true/false | false |
| tableSelection | Boolean | 表格多选 | true/false | false |
| rowKey | String | 树结构的row-key | — | id |
| treeProps | Object | 树结构的子级信息 | — | — |
| tooltip | Boolean | 单元格内容过多是否超出隐藏 | true/false | true |
| colMinWidth | String | 单元格最小宽度 | — | auto |
| serial | Boolean | 是否显示序列号 | true/false | false |
| loading | Boolean | 是否显示loading | — | false |
| colAlign | String | 单元格对齐方式 | right/left/center | right |

2、tableData参数

| 参数名 | 类型 | 说明 | 可选值| 默认值 |
| :------| :------ | :------ | :------ | :------ |
| label | String | 表头标题 | — | — |
| prop | String | 单元格内容，需要和tableHeader的键保持一致| — | — |
| fixed | Boolean | 单元格是否固定定位,true为左定位 | right/left/false | false |
| width | Strng | 单元格宽度 | — | — |
| minWidth | Strng | 单元格最小宽度 | — | — |
| type | Strng | type为switch/btn是插槽 | text/switch/btn | 空 |
| align | String | 单元格对齐方式 | right/left/center | right |

3、事件

| 事件名 | 说明 | 参数 |
| :------| :------ | :------ |
| selectionChange | 表格多选时触发的事件 | selection |

4、table Slot

| name | 说明 | 参数 |
| :------| :------ | :------ |
| btnSlot | tableData参数type为btn是的slot name | row |
| switchSlot | tableData参数type为switch是的slot name | row |
