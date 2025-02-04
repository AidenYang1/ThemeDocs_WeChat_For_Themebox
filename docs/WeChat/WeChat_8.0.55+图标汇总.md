
# 最新：该文档已按照`55+`版本整理。
- 如果你需要快速知道每个版本新增内容，例如 `55` 版本的单独命名，在此页面使用浏览器页面查找搜索 `#55` 即可快速跳转查看所有55单独变化的命名。
- 没有标注 `#55` 标签的表示与 `WeChat` 前一版本相同，保持不变。
- `@@` 标签表示已适配，但未整理。
- `@@@` 标签表示未知，欢迎补充。（页面查找此定位符快速帮助完善文档）


# 说明
- 文档按照适配工作 `延后更新`，如有遗漏，请反馈说明。
- 如你在 `再次实践中` 发现有标注错误的地方，欢迎 `反馈修正`。你将成为本项目的贡献者。
- 如果你有 `先于本项目` 的统计，欢迎投稿。优秀贡献者将获得原 `iMessage` 主题项目 `兑换码`。



# 全局背景和部分头像修改
- 该部分为 `Themebox` 主题插件单独命名的内容，请查看本项目 `首页` 目录中 ` Themebox ` 适配指南中针对各界面 ` 顶栏 `、` 底栏 `、` 全局背景 `、`聊天页背景`、`输入框背景` 等设置的解释。
- 在 `Themebox` 中部分头像的命名也已做映射，如你在该文档中没有找到你所需要查找的图标命名方式，请优先查看位于本项目首页目录的 `Themebox` 适配指南。
<br><br>
---

# 统计表开始

# 首页

## 1. 消息列表页
### 1.1. 右上角加号
部分功能槽由第三方插件提供，如没有显示请自行开启功能。

|     | 解释   | 图标命名                       | 1 x 基本尺寸  | 说明       |
| :-- | :--- | :------------------------- | :-----: | :------- |
|     | 一键已读 | eyes_on_filled             | 24 x 24 |          |
|     | 发起群聊 | bubble_circle_filled       |         |          |
|     | 添加好友 | person_plus_filled         |         |          |
|     | 扫一扫  | scan_filled                |         |          |
|     | 收付款  | pay_filled                 |         |          |
|     | 勿扰模式 | mike_off_regular           |         |          |
|     | 清理会话 | icons_filled_circle_delete |         |          |
|     | 切换账号 | icons_filled_transfer      |         | 共用“转账”图标 |
|     | 查找用户 | icons_filled_search        |         |          |


## 2. 通讯录页
### 2.1. 好友相关操作
|     | 解释      | 图标命名                          | 1 x 基本尺寸                                | 说明  |
| :-- | :------ | :---------------------------- | :-------------------------------------- | :-- |
|     | 新的朋友    | plugins_FriendNotify          | 30 x 30 纯圆图标或使用 60 x 60 透明无填充圆形包括不规则图标。 |     |
|     | 仅聊天的朋友  | Contact_Chatonlyfriends       |                                         |     |
|     | 群聊      | add_friend_icon_addgroup      |                                         |     |
|     | 标签      | Contact_icon_ContactTag       |                                         |     |
|     | 公众号     | add_friend_icon_offical       |                                         |     |
|     | 服务号     | add_friend_icon_brand_service |                                         |     |
|     | 企业微信联系人 | openimbrand                   |                                         |     |
|     | 右上角添加朋友 | person_plus_regular           |                                         |     |

### 2.2. 右上角二级菜单
|     | 解释      | 图标命名                             | 1 x 基本尺寸                                | 说明                  |
| :-- | :------ | :------------------------------- | :-------------------------------------- | :------------------ |
|     | 雷达加朋友   | redar_regular                    | 30 x 30 纯圆图标或使用 60 x 60 透明无填充圆形包括不规则图标。 | #55 单独              |
|     | 面对面建群   | add_friend_icon_addgroup         |                                         | 与通讯录群聊共用            |
|     | 扫一扫     | ScanQRCodeAction                 |                                         |                     |
|     | 手机联系人   | phone_rectangle_regular          |                                         | #55 单独              |
|     | 公众号     | person_tie_regular               |                                         | 与通讯录页图标共用 ( #55 单独) |
|     | 企业微信联系人 | enterprisewechat_filled_colorful |                                         | #55 单独              |
|     | 我的二维码   | add_friend_myQR                  |                                         |                     |

### 2.3. 侧边字母检索
|     | 解释       | 图标命名              | 1 x 基本尺寸             | 说明  |
| :-- | :------- | :---------------- | :----------------- | :-- |
|     | 字母滑动检索背景 | ContactIndexShape | 66 x 55 (也可自行设计尺寸) |     |

## 3. 发现页
|     | 解释  | 图标命名                                                                  | 1 x 基本尺寸  | 说明                 |
| :-- | :-- | :-------------------------------------------------------------------- | :------ | :----------------- |
|     | 朋友圈 | icons_outlined_colorful_moment<br>icons_outlined_colorful_moment_dark | 30 x 30 | 深色模式可能需要 svg 格式才生效 |
|     | 视频号 | icons_outlined_finder                                                 |         |                    |
|     | 直播  | moment_filled<br>moment_filled_Dark                                   |         |                    |
|     | 扫一扫 | scan_regular                                                          |         | 深色模式可能需要 svg 格式才生效 |
|     | 听一听 | icons_filled_ting_finder_entry_music                                  |         |                    |
|     | 看一看 | news_regular                                                          |         |                    |
|     | 搜一搜 | search_filled（可能标错，项目文件丢失）                                            |         |                    |
|     | 附近  | icons_outlined_live_nearby                                            |         |                    |
|     | 游戏  | icons_outlined_colorful_game<br>icons_outlined_colorful_game_Dark     |         | 深色模式可能需要 svg 格式才生效 |
|     | 小程序 | icons_outlined_miniprogram                                            |         |                    |
|     | 购物  | shopping_bag_regular                                                  |         |                    |

## 4. 我的页面
|     | 解释  | 图标命名                                                      | 1 x 基本尺寸 | 说明              |
| :-- | :-- | :-------------------------------------------------------- | :------- | :-------------- |
|     | 服务  | icons_outlined_wechatpay<br>icons_outlined_wechatpay_Dark | 30 x 30  |                 |
|     | 收藏  | favorites_filled_coloful<br>favorites_filled_coloful_Dark |          | #55 单独          |
|     | 贴纸  | smile_regular                                             |          |                 |
|     | 卡包  | icons_filled_cards&offers                                 |          | 可能需要 svg 格式才能生效 |
|     | 视频号 | play_circle_regular                                       |          |                 |
|     | 朋友圈 | picture_regular                                           |          |                 |
|     | 插件  | WeChat_Lab_Logo_light_small                               |          |                 |
|     | 设置  | gear_regular                                              |          |                 |



# 聊天页
## 1. 昵称顶栏操作区
### 1.1. 顶栏操作提示
|     | 解释   | 图标命名          | 1 x 基本尺寸  | 说明  |
| :-- | :--- | :------------ | :------ | :-- |
|     | 听筒模式 | 等待整理补充        |         |     |
|     | 通知静音 | 等待整理补充        |         |     |
|     | 搜索   |               |         |     |
|     | 更多   | dot_3_regular | 24 x 24 |     |
### 1.2. 进入右上角菜单后聊天更多设置界面
|     | 解释  | 图标命名                    | 1 x 基本尺寸  | 说明  |
| :-- | :-- | :---------------------- | :------ | :-- |
|     | 减少人 | avatar_dotline_minus_bg | 90 x 90 |     |
|     | 增加人 | avatar_dotline_add_bg   |         |     |


## 2. 气泡长按功能区
### 2.1. 微信默认操作
|     | 解释    |              图标命名               | 1 x 基本尺寸 | 说明               |
| :-- | :---- | :-----------------------------: | :------- | :--------------- |
|     | 听筒    |           ear_filled            | 30 x 30  |                  |
|     | 收藏    |                -                |          | 跟随聊天页官方菜单操作区收藏图标 |
|     | 转文字   |     convert_to_text_filled      |          |                  |
|     | 删除    |         trash_on_filled         |          |                  |
|     | 多选    |  icons_filled_multiple_choice   |          |                  |
|     | 背景播放    |  icons_filled_miniwindow   |          |  #56 单独          |
|     | 引用    |       icons_filled_quote        |          |                  |
|     | 提醒    |         bell_on_filled          |          |                  |
|     | 转发    |          share_filled           |          |                  |
|     | 搜一搜   | icons_filled_WeChatSearchEmblem |          |                  |
|     | 复制    |           doc_filled            |          | #55 单独           |
|     | 隐藏转文字 |         eyes_off_filled         |          |                  |
|     | 反馈错误 |  icons_filled_feedback_error    |          |                  |
|     | 更换语言 |  icons_filled_transfer_language      |          |                  |
|     | 静音播放 |  icons_red_story_volume_off      |          |                  |

### 2.2. 第三方插件气泡长按动作
|     | 解释   |          图标命名           | 1 x 基本尺寸  | 说明  |
| :-- | :--- | :---------------------: | :------ | :-- |
|     | 小丑   |       expression        | 30 x 30 |     |
|     | 转语音  |      icons_filled_radar          |         |     |
|     | 语音复读 | icons_filled_nearby_hot |         |     |
|     | 添加字体 | icons_outlined_font |         |     |
|     | 导入字体 | icons_filled_text |         |     |


## 3. 输入栏区
|     | 解释         |                图标命名                 | 1 x 基本尺寸       | 说明                                 |
| :-- | :--------- | :---------------------------------: | :----------- | :--------------------------------- |
|     | 语音消息       |        voice_circle_regular         | 30 x 30      |                                    |
|     | 贴纸         |            smile_regular            |              |                                    |
|     | 更多操作       |      icons_outlined_addoutline      |              | 与首页消息列表右上角+号共用                     |
|     | 键盘输入       |       keyboard_circle_regular       |              |                                    |
|     | 输入框文字输入栏背景 | input_text_bg<br>input_text_bg_Dark | 只需要 1 x 尺寸即可 | 输入文字时上下拉伸，高度自动挤压。（参考安全值：880 x 115） |



## 4. 微信助手插件快捷工具栏区
|     | 解释     |                 图标命名                 | 1 x 基本尺寸       | 说明                                            |
| :-- | :----- | :----------------------------------: | :----------- | :-------------------------------------------- |
|     | 快捷回复   |          icons_filled_chats          | 30 x 30 圆形图标 | 如需要使用不规则图标，请用 30 x 30 无边框不填充的圆形进行包裹，避免图标显示不全。 |
|     | 照片     |            picture_filled            |              |                                               |
|     | 拍摄     |         icons_filled_camera          |              |                                               |
|     | 文件     |         icons_filled_folder          |              |                                               |
|     | 红包     |      icons_filled_red_envelope       |              | 命名引用共用-官方更多工具栏                                |
|     | 转账     |        icons_filled_transfer         |              |                                               |
|     | 位置     |        icons_filled_location         |              | 命名引用共用-官方更多工具栏共用                              |
|     | 通话     |        icons_filled_videocall        |              | 命名引用共用-官方更多工                                  |
|     | 收藏     |        icons_filled_favorites        |              |                                               |
|     | 翻译     |           translate_filled           |              |                                               |
|     | 名片     |           icons_filled_me            |              |                                               |
|     | 搜表情    |                等待排查整理                |              | 与其他搜索图标共用                                     |
|     | 语音输入   |    icons_filled_voiceinput_white     |              |                                               |
|     | 扫一扫    |          icons_filled_scan           |              |                                               |
|     | 搜一搜    |         icons_filled_search          |              | 与其他搜索图标共用                                     |
|     | 收付款    |         icons_filled_qr_code         |              |                                               |
|     | 微信助手   |         icons_filled_setting         |              |                                               |
|     | 添加贴纸   |      icons_filled_othersticker       |              |                                               |
|     | 换行     |        icons_multitalk_scroll        |              |                                               |
|     | 粘贴     |          icons_filled_note           |              |                                               |
|     | @      |           icons_filled_at            |              |                                               |
|     | 全屏输入   |        icons_filled_maxwindow        |              |                                               |
|     | 小霸王    |          icons_filled_game           |              |                                               |
|     | 浮窗     |       icons_outlined_multitask       |              |                                               |
|     | 语音包    |          icons_filled_song           |              |                                               |
|     | Misaka |         icons_filled_effects         |              |                                               |
|     | 黄白助手   | icons_outlined_colorful_menu_browser |              | 存在其他地方浏览器图标引用                                 |


## 5. 官方菜单工具栏


|     | 解释       |             图标命名              | 1 x 基本尺寸 | 说明           |
| :-- | :------- | :---------------------------: | :------- | :----------- |
|     | 照片       |        picture_filled         | 30 x 30  |              |
|     | 相机       |         camera_filled         |          |              |
|     | 视频通话     |    icons_filled_videocall     |          | 共用命名-微信助手工具栏 |
|     | 位置       |        location_filled        |          |              |
|     | 红包       |   icons_filled_red_envelope   |          | 共用命名-微信助手工   |
|     | 转账       |        transfer_filled        |          | 共用命名-微信助手工   |
|     | 语音输入     | icons_filled_voiceinput_white |          |              |
|     | 收藏       |       favorites_filled        |          |              |
|     | 个人名片     |         person_filled         |          |              |
|     | 文件       |         folder_filled         |          |              |
|     | 卡券       |       cardholder_filled       |          |              |
|     | 直播       |     icons_outlined_chats      |          |              |
|     | 群工具      |    icons_filled_grouptool     |          |              |
|     | 群接龙      |    icon_outlined_solitaire    |          |              |
|     | 第三方转语音插槽 |     voice_circle_regular      |          | 具体哪个插件的反馈    |
|     | 音乐       |       icon_music_filled       |          |              |
|     | 小信号      |     icons_filled_barrage      |          |              |
## 6. 消息气泡
### 6.1. 语音条（该部分缺矫正和补充）
|     | 解释        |         图标命名         | 1 x 基本尺寸 | 说明     |
| :-- | :-------- | :------------------: | :------- | :----- |
|     | 语音条播放状态 1 | icon_voice_playing 1 | 24*24    | #55 单独 |
|     | 语音条播放状态 2 | icon_voice_playing 2 |          | #55 单独 |
|     | 语音条播放状态 3 | icon_voice_playing 3 |          | #55 单独 |
|     | 暂停状态      |          @@          |          |        |



## 7. 聊天页长按图片操作
|     | 解释          |            图标命名            | 1 x 基本尺寸 | 说明        |
| :-- | :---------- | :------------------------: | :------- | :-------- |
|     | 保存图片        |      download_filled       | 30*30    |           |
|     | 查看聊天记录中更多图片 | icons_filled_img_photowall |          |           |
|     | 此聊天中的图片视频 | icon_outlined_picture |          | #56 单独 |
|     | 编辑图片        |  pencil_rectangle_regular  |          |           |
|     | 提取文字        |     icons_outlined_ocr     |          |           |
|     | 其他未标注的      |             -              |          | 与其他地方图标共用 |

# 好友资料页
## 1. 性别显示
|     | 解释  |             图标命名             | 1 x 基本尺寸  | 说明  |
| :-- | :-- | :--------------------------: | :------ | :-- |
|     | 男   |  icons_filled_colorful_man   | 18 x 18 |     |
|     | 女   | icons_filled_colorful_female |         |     |

## 2. 语音视频通话

|     | 解释   |     图标命名      | 1 x 基本尺寸 | 说明            |
| :-- | :--- | :-----------: | :------- | :------------ |
|     | 语音通话 |       -       |          | 跟随首页右上角+号发起群聊 |
|     | 视频通话 | video_regular | 30 x 30  |               |


# 朋友圈
|     | 解释      |      图标命名      | 1 x 基本尺寸 | 说明                         |
| :-- | :------ | :------------: | :------- | :------------------------- |
|     | 评论      | bubble_regular | 30*30    | 会偏大，但是因与其他页面评论图标共用，会影响其他页面 |
|     | 点赞      | heart_regular  |          |                            |
|     | 朋友圈置顶      | icons_filled_top  |          |                            |
|     | 部分人可见      | person_2_filled  |          |                            |
|     | 删除朋友圈      | trash_on_regular  |          |                            |
|     | 第三方插件转发 |  欢迎补充<br>@@@   |          |                            |


# 公众号文章阅读页
|     | 解释        |               图标命名                | 1 x 基本尺寸 | 说明                |     |
| :-- | :-------- | :-------------------------------: | :------- | :---------------- | --- |
|     | 收藏        |   icons_filled_color_favorites    | 30*30    |                   |     |
|     | 转发        |           share_filled            |          |                   |     |
|     | 分享到朋友圈    |          Action_Moments           |          |                   |     |
|     | 在看        |           news_regular            |          |                   |     |
|     | 在电脑上打开    | icons_filled_othersticker            |          |                   |     |
|     | 在浏览器打开    |                 -                 |          | 黄白助手引用该图标命名，两者共用  |     |
|     | 微信读书中打开   |            欢迎补充<br>@@@            |          |                   |     |
|     | 发送到我的企业   |            欢迎补充<br>@@@            |          |                   |     |
|     | 邮件        |             AS_Email              |          |                   |     |
|     | 分享到 QQ    |               AS_QQ               |          |                   |     |
|     | 分享到 QQ 空间 |           Action_qzone            |          |                   |     |
|     | 更多打开方式    |        weapp_more_darkmode        |          |                   |     |
|     | 在小程序工具中打开    |        weapp_corner_icon_light<br>weapp_corner_icon_dark        |          |    #56 单独               |     |
|     | 浮窗        |     icons_outlined_multitask      |          | 微信助手工具栏内“浮窗”共用此图标 |     |
|     | 听全文       |       icon_outlined_listen        |          |                   |     |
|     | 稍后听       |    icons_outlined_listen_later    |          |                   |     |
|     | 保存为图片     |         download_regular          |          | 与其他下载共用           |     |
|     | 投诉        | exclamation_mark_triangle_regular |          |                   |     |
|     | 复制链接      |           link_regular            |          | #55 （与其他链接共用）     |     |
|     | 刷新        |          refresh_regular          |          |                   |     |
|     | 全文翻译      |         translate_regular         |          |                   |     |
|     | 查找页面内容    |    icons_outlined_find_content    |          |                   |     |
|     | 调整字体      |        icons_outlined_font        |          |                   |     |
|     | 打开调试      |         weapp_icon_debug          |          |                   |     |
|     | 更多信息      |            tag_regular            |          |                   |     |
|     | 首页左侧收起浮窗  |     arrow_left_circle_filled      |          |                   |     |

# 红包转账气泡卡面

|     | 解释    |                                       图标命名                                        | 1 x 基本尺寸  | 说明       |
| :-- | :---- | :-------------------------------------------------------------------------------: | :-------- | :------- |
|     | 发送方发送 |            ChatRoom_Bubble_HB_Sender<br>ChatRoom_Bubble_HB_Sender_Dark            | 800 x 250 | 导出加@3x后缀 |
|     | 发送方接受 |    ChatRoom_Bubble_HB_Sender_Handled<br>ChatRoom_Bubble_HB_Sender_Handled_Dark    |           |          |
|     | 接收方正常 |          ChatRoom_Bubble_HB_Receiver<br>ChatRoom_Bubble_HB_Receiver_Dark          |           |          |
|     | 接收方接受 |  ChatRoom_Bubble_HB_Receiver_Handled<br>ChatRoom_Bubble_HB_Receiver_Handled_Dark  |           |          |
|     | 发送方过期 |   ChatRoom_Bubble_HB_Overtime_Sender<br>ChatRoom_Bubble_HB_Overtime_Sender_Dark   |           |          |
|     | 接收方过期 | ChatRoom_Bubble_HB_Overtime_Receiver<br>ChatRoom_Bubble_HB_Overtime_Receiver_Dark |           |          |


# 更多内容将不断完善更新，记得 Star⭐️
如果有发现问题或者补充条目。你可以：
- 直接 fork 此仓库，修改对应的 markdown 文件后发起 pr，审核通过将合并请求，你将成为该项目的参与者。（推荐）
- 电报私信我或者使用 issue 发起反馈议题。

你的补充和反馈，将帮助完善此文档。也许你也是突然捣鼓微信主题，期待你在捣鼓期间，能留下你宝贵的经验和捣鼓心得，即使过一阵子就回归自己的工作生活，你留下的足迹也将为后来者乘凉。也许他们之中就有非常优秀的设计师，能带来非常棒的主题作品。
