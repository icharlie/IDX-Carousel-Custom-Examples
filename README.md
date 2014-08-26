IDX-Carousel-Custom-Examples
============================

### Custom Arrow
> Please Replace the {{widgetID}} by your widget ID

#### Half-Circle

![](https://raw.githubusercontent.com/icharlie/IDX-Carousel-Custom-Examples/master/images/Half-Circle.jpg)


```css
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselPrevArrow {height:40px;line-height:40px; width: 20px; top:50%;border-radius:20px 0 0 20px;}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow span {top: 0; margin: 0}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselNextArrow {height:40px;line-height:40px; width: 20px; top:50%;border-radius:0 20px 20px 0 ;}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow { margin-top: -20px;}
```

#### Mini-Square
![](https://raw.githubusercontent.com/icharlie/IDX-Carousel-Custom-Examples/master/images/Mini-Square.jpg)


```css
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow {
top: 50%;
width: 25px;
margin-top: -20px;
height: 40px;
}
```