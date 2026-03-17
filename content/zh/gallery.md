---
type: 'slide'
title: '图库'
params:
    headless: true
    target: 'https://github.com/valuejhxu/blog'
---

这是一个使用 `{{</* pin */>}}` 短代码的幻灯片。

## 作品展示（示例）

使用 `Pin` 短代码的区块。
项目按列排序显示。
如果图片不是正方形，布局将以瀑布流方式显示。

{{< pin "begin" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/1.svg" label="项目 1">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/2.svg" label="项目 2">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/3.svg" label="项目 3">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/4.svg" label="项目 4">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/5.svg" label="项目 5">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/6.svg" label="项目 6">}}
{{< pin "end" >}}

## 产品目录（示例）

带有 `quote` 参数的 `{{</* pin */>}}` 短代码。

{{< pin "begin" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/7.svg" label="产品 1" url="#商城" quote="<s>￥299</s> ￥199" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/8.svg" label="产品 2" url="#商城" quote="<s>￥399</s> ￥299" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/9.svg" label="产品 3" url="#商城" quote="获取报价" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/10.svg" label="产品 4" url="#商城" quote="<s>￥299</s> ￥199" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/11.svg" label="产品 5" url="#商城" quote="<s>￥399</s> ￥299" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/12.svg" label="产品 6" url="#商城" quote="缺货" >}}
{{< pin "end" >}} 