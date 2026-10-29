# Pentax 67II 首卷批改

独立页面，不放进说明书网站。

- 线上：https://gengyueworks.github.io/pentax67ii-feedback/
- 说明书站：https://gengyueworks.github.io/pentax67ii-manual/

## 结构
- `index.html`：12 张照片页 + ISO 专页，纯静态
- `images/p01–p12.jpg`：按发送顺序裁切的照片（已去掉手机界面边框）
- 翻页：顶部序号、底部按钮、键盘左右键；锚点 `#p01` … `#p12`、`#iso`
- 每个控件的「手册 P.xx」可点击，直达说明书站对应页（`?page=xx`）
- 配色：克莱因蓝 #002fa7 / 纸色底 #f3f2ef，支持明暗切换

## 核对依据
控件名称、操作顺序、页码，全部对照原厂中文说明书（80 页扫描件）逐页 OCR 核对，
机型为 PENTAX 67II 中片幅单反（120 胶卷 10 张 / 220 胶卷 21 张）。
