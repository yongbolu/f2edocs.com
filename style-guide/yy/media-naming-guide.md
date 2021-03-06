# 多媒体命名规范指南

---

多媒体命名规范指南

---

## 文档目录

1. [图片](#1-图片)
2. [有声媒体](#2-有声媒体)
3. [字体](#3-字体)

### 1 图片

**【强制】** 由于图片通常会配合自动切图、gulp自动生成图片样式的工作流进行，所以图片的命名规则跟CSS中对图片的命名规则保持一致：

* **背景**：以`bg`作为命名空间，例如：`bg-body` 等；
* **图标**：以`ico`作为命名空间，例如：`ico-close` 等；
* **LOGO**：以`logo`作为命名空间，例如：`logo-duowan` 等；
* **内容图像**：以`img`作为命名空间，例如：`img-userGuide` 等；
* **雪碧图**：以`sprite`作为命名空间，例如：`sprite-form` 等；

### 2 有声媒体

**【强制】** 包括音频、视频、flash，根据具体情况命名。音视频文件一般别放在SVN中上传到CDN服务器；

### 3 字体

**【强制】** 为了尊重字体设计者的劳动以及版权，字体命名（包括CSS中的@font-face对font-family的命名）应当遵循字体本身的名称；