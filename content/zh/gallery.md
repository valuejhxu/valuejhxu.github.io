---
title: '影像'
date: 2024-03-27
description: '摄影作品'
type: 'gallery'
aliases: ['/zh/gallery/']
params:
    noIndent: true
---

随手拍的一些画面。点击图片看大图。

<!--
  如何添加照片
  ---------------
  1. 每张照片准备两个文件放进 static/photos/<年份>/：
       chengdu-01.jpg        原图   长边 2000px  质量 82  控制在 500KB 内
       chengdu-01-thumb.jpg  缩略图 长边 700px   质量 80  控制在 90KB 内

     用 ImageMagick 生成（在 static/photos/<年份>/ 目录下执行）：
       magick chengdu-01.jpg -resize 2000x2000\> -quality 82 chengdu-01.jpg
       magick chengdu-01.jpg -resize 700x700\>   -quality 80 chengdu-01-thumb.jpg

  2. 在下面的 pin 区块里加一行，img 用缩略图，url 指向原图：
       {{</* pin img="/photos/2024/chengdu-01-thumb.jpg" url="/photos/2024/chengdu-01.jpg" label="成都 · 玉林" */>}}

  说明：img/url 也接受外部图床的完整 URL，想用图床随时可以混着写。
  主题不做任何图片处理，所以缩略图必须自己压好，否则一页几十张原图会很慢。
-->

{{< pin "begin" >}}
{{< pin img="/images/camera_sensor.svg" url="/images/camera_sensor.svg" label="示例 · 把这里换成你的照片" >}}
{{< pin img="/images/sinusoidal_pe.svg" url="/images/sinusoidal_pe.svg" label="示例 · 删掉这两条即可" >}}
{{< pin "end" >}}
