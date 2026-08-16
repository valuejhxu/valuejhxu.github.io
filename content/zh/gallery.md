---
title: '影像'
date: 2024-03-27
description: '摄影作品，按月份记录'
type: 'gallery'
aliases: ['/zh/gallery/']
params:
    noIndent: true
---

一些画面，按月份排。点击看大图。

<!--
  加照片
  ------
  1. 两个文件放进 static/photos/<年份>/：
       chengdu-01.jpg        原图   长边 2000px  质量 82  ≤500KB
       chengdu-01-thumb.jpg  缩略图 长边 700px   质量 80  ≤90KB
     生成命令见 .github/PHOTOS.md

  2. 按月份分区块，新的月份放最上面：
       {{</* photos month="2024 · 5月" */>}}
       {{</* photo src="缩略图" full="原图" label="说明" span="l" tilt="r" */>}}
       {{</* /photos */>}}

     span 控制宽度档位 s / m / l，tilt 控制轻微倾斜 l / r。
     交替使用不同的 span 和 tilt 就能形成错落效果，不必每张都写。
     src/full 也接受外部图床的完整 URL。
-->

{{< photos month="2024 · 3月" >}}
{{< photo src="/images/camera_sensor.svg" full="/images/camera_sensor.svg" label="示例 · 换成你的照片" span="l" tilt="l" >}}
{{< photo src="/images/sinusoidal_pe.svg" full="/images/sinusoidal_pe.svg" label="示例 · 删掉即可" span="s" >}}
{{< photo src="/images/camera_sensor.svg" full="/images/camera_sensor.svg" label="示例 · 错落排布" span="m" tilt="r" >}}
{{< /photos >}}
