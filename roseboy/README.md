# 蔷薇少年（酒馆美化）

宁宁 × Claude 自制的 SillyTavern 手机端美化：粉色蔷薇、天使羽翼和蝴蝶的少年主题。素材都是透明底 PNG，通过 jsDelivr 引用。

- 导入：酒馆 → 用户设置 → UI 主题 → 导入 `蔷薇少年.json`
- 调位置、颜色：改 `src/theme.css` 开头 `:root` 里的变量，然后运行 `python3 src/build.py` 重新生成 JSON
- 链接前缀：`https://cdn.jsdelivr.net/gh/Ttsningning/orange-shop-assets1@main/roseboy/`

| 文件 | 用在哪 |
|---|---|
| bubble_top / bubble_mid / bubble_bot | 消息气泡的头部、正文（九宫格拉伸）、尾部 |
| ring_overlay | 挖空的头像框，盖在头像上面 |
| bubble_top_angel | 备用头部 |
| topbar / input_bar | 顶栏、输入框 |
| btn_* / ico_* | 输入框按钮、编辑、更多、星标、箭头、勾叉、顶栏图标 |
| frame_circle / frame_heart / frame_moon | 备用头像框 |
| panel_bg.jpg | 所有设置面板的浅色背景插画 |
| deco_feather（滑块）、deco_butterfly（标题、分割线、输入框旁）、deco_box、deco_small | 装饰 |
| spinner / btn_loadmore / panel_scene / tile_a / tile_b | 加载图标、加载更多按钮、场景图、顶栏小图 |

![预览](preview.png)
