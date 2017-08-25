# css3-preload-img
CSS preload trick I learn from this [post](https://perishablepress.com/preload-images-css3/)

It looks like old trick, since you can prefetching image.

But you can still try it :p

# Usage
Just add a div(just one!) which class is "preload-img"

i.e.: `<div class="preload-img"></div>`

And it's done

Liquid will get all static asset which file name contain <b>thumbnail</b> and it's <b>image or gif</b> file, push them as preload-img's background, so browser will load them as soon as your site begin load, but it'll not show since their offset out of view.
