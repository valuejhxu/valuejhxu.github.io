---
type: 'slide'
title: 'Gallery'
params:
    headless: true
    target: 'https://github.com/foxihd/hugo-brewm'
---

This is a slide with `{{</* pin */>}}` shortcode.

## Pin it as Showcase (Example)

Section with `Pin` shortcode.
The item order is column-based.
If images are not square, the layout will displayed as masonry style.

{{< pin "begin" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/1.svg" label="Item 1">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/2.svg" label="Item 2">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/3.svg" label="Item 3">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/4.svg" label="Item 4">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/5.svg" label="Item 5">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/6.svg" label="Item 6">}}
{{< pin img="https://w.wallhaven.cc/full/01/wallhaven-01gwqw.jpg" label="Item 7">}}
{{< pin img="https://w.wallhaven.cc/full/ey/wallhaven-ey78gk.jpg" label="Item 8">}}
{{< pin img="https://w.wallhaven.cc/full/eo/wallhaven-eojxkk.jpg" label="Item 9">}}
{{< pin img="https://w.wallhaven.cc/full/l3/wallhaven-l3mw62.jpg" label="Item 10">}}
{{< pin img="https://w.wallhaven.cc/full/57/wallhaven-57z9g3.png" label="Item 11">}}
{{< pin img="https://w.wallhaven.cc/full/49/wallhaven-491wqw.jpg" label="Item 12">}}
{{< pin img="https://w.wallhaven.cc/full/qz/wallhaven-qzqv25.jpg" label="Item 13">}}
{{< pin img="https://w.wallhaven.cc/full/p2/wallhaven-p2mqw9.jpg" label="Item 14">}}
{{< pin img="https://w.wallhaven.cc/full/y8/wallhaven-y871gg.jpg" label="Item 15">}}
	

{{< pin "end" >}}

## Pin it as Catalogue (Example)

`{{</* pin */>}}` shortcode with `quote` parameter.

{{< pin "begin" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/7.svg" label="Item 1" url="#my-ecommerce" quote="<s>$299</s> $199" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/8.svg" label="Item 2" url="#my-ecommerce" quote="<s>$399</s> $299" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/9.svg" label="Item 3" url="#my-ecommerce" quote="Get Quote" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/10.svg" label="Item 4" url="#my-ecommerce" quote="<s>$299</s> $199" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/11.svg" label="Item 5" url="#my-ecommerce" quote="<s>$399</s> $299" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/12.svg" label="Item 6" url="#my-ecommerce" quote="Out of stock" >}}
{{< pin "end" >}}
