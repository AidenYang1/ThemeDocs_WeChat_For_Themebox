# 嘿👋🏻！我想你也遇到了一些DIY问题。（编写中）

![标题图](/images/标题图.png)

<br>

# 为好的内容买单
- 系统需要开放` API `才有开发者愿意开发适配，确保生态系统的可持续发展与功能扩展
- 设计需要一定`标准规范`才能统一体验，提高开发效率，同时降低沟通成本。
- 我想我们的工作重心`不应该花在如何用笔，而是如何用笔写出好的作品`。与其粗制滥造，不如大家都站在同一起跑线，拿着`同一份答题卡`，比`比谁的答卷更好`。
  
<br>

   因此，我将主题制作过程中的`相关制作内容`、`工程文件`、`图标命名`、`界面分类`、`主题盒子适配指南`、`其他规范`分享于此。即使有一天该主题因为各种原因工作、生活原因不再维护，后来者仍然会有另一个像当初怀有热情的我，突然闯进这个小圈子，攒着干劲。但后来的你，用创新、更加丰富的知识体系、审美水平、设计思路来制作、完善一份优秀的主题。

<br>
后来的你，这将是一份属于自己的付出的贡献，也是一份对主题插件作者们逆向努力的正向反馈。因为有好的作品，主题插件作者们的努力也才没有白费。
<br>
<br>
<br>

> **好的作品可以标上价格，但决不允许粗制滥造的玩意儿用信息差标上高的价格。**


<br><br><br>

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

  <br><br><br>
# WeChat自定义 `Assets` 图标命名汇总

## 1. 微信 `8.0.55` 版本图标命名（等待补充）

## [2. 微信 `8.0.54` 版本图标命名（更新中）](docs/WeChat/WeChat_8.0.54图标汇总.md)

## 3. 微信 `8.0.33` 版本图标命名

  <br><br><br>
# 现有的Sketch项目使用
我想，你也能站在我的肩膀上。使用我制作这份主题时的`完整Sketch`项目文件，用我设置好的`图标命名`、`规划整理`的好的答题卡，快速进行适配制作。你只管设计，所有`界面分区`我都已经设置好了。<br>我说过，你不用关注这些脚手架问题，你只需要盯着官方`WeChat`的界面，用发挥创意的大脑去想:这里的`图标`和`颜色`怎么设计，`风格`和`思路`即可。

<br>

> 所有调料、食谱你都不要操心，你只需要好好的烹饪这份美食就行。扼杀你做出黑暗料理却怪食谱的想法。

<br><br><br>
# 图标设计尺寸解释

## PNG素材
在 iOS 开发中，**2x 和 3x 图像资源是需要分别设置的**，因为不同设备使用不同的屏幕分辨率倍数。只设置 `3x` 是不够的，因为运行在 `2x` 屏幕分辨率的设备上会导致图像模糊或缺失。
<br>
  

### 1.为什么需要分别设置 `2x` 和 `3x`？

1. 屏幕分辨率差异

• iOS 设备有不同的屏幕分辨率倍数：

• **2x**：常见于 iPhone SE (2nd generation)、iPhone 8等非 Retina HD 设备。

• **3x**：常见于 Retina HD 设备，如 iPhone 13 Pro、iPhone 14 Pro。

• 如果只设置 `3x`，运行在 `2x` 设备上的图像可能会被强制缩小，导致模糊。


<br><br>

2. 兼容性和用户体验

- 提供设备分辨率匹配的图像，系统`无需缩放`，显示效果最清晰。
- 使用适配的图像可以`减少图像解码和缩放的额外计算`，提升应用性能。
- 直接提供输出的 `2x` 和 `3x` 图像，确保每种分辨率下的视觉效果一致。



<br><br>
---
### 2.如何正确配置 2x 和 3x 图像？

iOS 使用`后缀`来区分分辨率倍数的图像资源：

• **2x**：image@2x.png

• **3x**：image@3x.png



<br><br>
---
### 3.如何快速设置2x、3x尺寸图像？
你可能头疼还要单独设计两个尺寸，这么多素材不得熬夜赶工。实际上，使用现代原型设计工具`Sketch`、`Axure`、`Figma`等只需要知道图标的`基本尺寸`即可。在ios开发中标准化设计流程都是通过设计基本尺寸`1x`的`矢量素材`，设计`基本尺寸`下的图标和素材，导出时配置统一添加`后缀`、`多比例缩放设置`，打包自动生成`@2x`、`@3x`尺寸的两份图像。（正如我所说，你只需要关注设计本身）




<br><br>
---
### 4.我可以只设置3x尺寸让其等比例缩放吗?

在 iOS 中，缩放通常是等比例的，但即便是等比例缩放，仍然可能导致以下问题：

- 即使是等比例缩放，从更高分辨率（如 3x）缩小到 2x 时，细节可能会丢失，图像会显得模糊，尤其是小图标或文字较多的图片。
- 锯齿现象：如果图像边缘的像素不够平滑，从 3x 缩放到 2x 时可能会出现锯齿。
- 文件大小不优化：3x 图像的文件大小通常比 2x 图像大得多，而在 2x 设备上使用 3x 图像会增加内存占用和加载时间，浪费资源。
- 小型图标和 UI 元素在缩放后，细节（如线条、圆角）可能会失真。

<br>

> 这是偷懒的做法，你可能觉得设计2x浪费时间，但记住使用现代设计工具，不要傻傻的，也没人手动单独设计2x和3x尺寸的素材。所以，不要纠结这个问题。

<br><br>


---
### 5.只能提供 3x 图像怎么办？
在制作主题时，你可能无法准确的肯定某一素材的原始基本尺寸。例如红包转账气泡封面，这在设计时会出现困扰。此时你可以选择使用PS或Sketch直接测量截图情况下的尺寸。并清楚你的设备的缩放比例。如果是调用的3x尺寸的素材，但计算后2x尺寸图像不是整数。为了素材不被挤压变形，这时你可以只设计通过你测量后的3x比例的尺寸，无需设计2x尺寸。记得：

- 优化图像细节：确保 3x 图像在缩放到 2x 时不会模糊，比如使用更粗的线条、减少复杂细节。
- 如果是大图（如背景图），等比例缩放通常问题不大，但小图标更容易受影响。




<br><br><br>
## SVG素材


<br><br><br>
# 主题的封包
这些辛苦制作的内容都是你的`知识产权`，无论你选择公开`无偿`分享还是封包`售卖`，都是你具有的权利。<br>
但如要售卖请：
- 确保你的`主题质量`。
- 不要`粗制滥造`。
- 事实很残忍，你可能花一个月做出来的主题，大家反馈就是一般。（请认真听反馈意见，考虑提高自己的设计、制作、审美水平，而不是一味地沉溺在自己做出来的成就）

<br><br><br>
# 一切就绪，整理项目文件结构
不要将所有文件堆叠到顶层文件夹，后期维护比较费劲。推荐的目录结构：
