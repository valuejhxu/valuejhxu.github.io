# 照片存放约定

按年份分目录，每张照片两个文件：

```
static/photos/2024/chengdu-01.jpg        # 原图   长边 2000px, 质量 82, ≤500KB
static/photos/2024/chengdu-01-thumb.jpg  # 缩略图 长边 700px,  质量 80, ≤90KB
```

生成命令（ImageMagick）：

```sh
magick 原图.jpg -resize 2000x2000\> -quality 82 chengdu-01.jpg
magick chengdu-01.jpg -resize 700x700\> -quality 80 chengdu-01-thumb.jpg
```

然后在 `content/zh/gallery.md` 的 pin 区块里加一行：

```
{{< pin img="/photos/2024/chengdu-01-thumb.jpg" url="/photos/2024/chengdu-01.jpg" label="成都 · 玉林" >}}
```

主题不做图片处理，缩略图必须自己压好。
