# Themebox 适配指南+配置文件说明
本主题基于 `Themebox` 适配指南进行适配，该部分文档是你设计主题的第一份`参考文档`。大部分人除非工作涉及性能优化或底层开发，都不需要关注代码如何编译成机器码。因此，一份好的`API+开发者文档`将帮助你只专注于生产`产出的内容`上，而无需关注和研究头疼的`脚手架`问题。<br><br>
主题制作同理，`Themebox`作者提供了详细的`说明文档`。这些属性值被填写到`json` 文件中，你可以在制作时直接向 `json` 文件中添加期望的`默认属性值`，以使主题被 `Themebox`初次加载时能如你设计思路所愿，避免不同人`Themebox` 的插件设置不一致出现的主题显示效果`差异性`。
[参考Themebox官方原始适配文档](https://docs.qq.com/doc/DWUxVVkpMQnRjd1p6)

<br>

> 编写时请具有基本json数据交换格式的语法常识。如果在这方面你还是小白，无需担心，我说过，你只需要关注内容产出，脚手架的事儿我给你提供几点提醒<br>
- `Themebox`中`config`使用`对象结构`组织数据。数据以键值对存在。`键`和`值`之间用冒号 `:` 分隔，多个键值对用逗号 `,` 分隔。
如：
```json
{
  "name": "John",
  "age": 30,
  "isStudent": false
}
```
- 键必须是`字符串`，用`双引号`包裹。键和值的双引号必须完整，不能漏掉。
- 最后一个键值对或数组元素后面不能加逗号.

<br>

> 好了，我说过，你只需要关注内容产出，所以说人话前面的一大堆在你这进行主题适配时就是：
- 左边"`设置`":右边"`值`"。
- 每行`逗号`结尾，最后一行记得`不要有逗号`。

如：
```json
{
    "name": "AAAAA",
    "auth": "BBBB",
    "version": "xxxx"
}
```
<br>


















## 1.配置文件config

基础配置只需要`主题名称`和`作者`即可

|   |   |   |
|---|---|---|
|名称|作用|参数|
|themeId|主题ID|系统生成，请勿填写！|
|name|配置主题名称||
|auth|配置主题作者||
|version|主题版本号|系统自动生成，可以不写|

## 2.底栏配置

|   |   |   |
|---|---|---|
|名称|作用|参数|
|tabbar_nor_color|底栏标题颜色|HEX颜色值，不需要#号|
|tabbar_nor_color_dark|暗黑模式||
|tabbar_sel_color|底栏选中时标题颜色||
|tabbar_sel_color_dark|暗黑模式||
|badge_color|消息角标背景颜色||
|badge_color_dark|暗黑模式||
|badge_text_color|角标文字颜色||
|badge_text_color_dark|暗黑模式||
|tabbar_size|底栏图标大小|可选或者宽*高，例如30*30|
|tabbar_top_enabled|用于修改底栏图标偏移，用户开启悬浮底栏时无效|true/false|
|tabbar_top|偏移值，当上面一项为true时才会生效，用户开启悬浮底栏时无效|偏移位置数值，例如-10|
|tabbar_hide_title|隐藏底栏标题，用户开启悬浮底栏时无效|true/false|

## 3.其它配置

|   |   |   |
|---|---|---|
|名称|作用|参数|
|luckmoney_text_color|打开红包时封面上的颜色|HEX颜色值，不需要#号|
|luckmoney_text_color_dark|暗黑模式||
|hongbao_text_color|气泡上红包和转账的文字颜色||
|hongbao_text_color_dark|暗黑模式||
|menu_text_color|长按消息菜单时的文字颜色||
|menu_text_color_dark|暗黑模式||
|hide_source_title|隐藏红包/转账/小程序等气泡上的来源标题|true/false|

## 4.裁剪

|             |      |                                          |
| ----------- | ---- | ---------------------------------------- |
| 名称          | 作用   | 参数                                       |
| bubble_edge | 气泡裁剪 | 可不填或者上*左*下*右<br><br>例如20*30*8*30，相见下面的说明 |
