IDX-Carousel-Custom-Examples
============================

### Custom Arrow
> Please replace the {{widgetID}} by your widget ID

#### Half-Circle

![](https://raw.githubusercontent.com/icharlie/IDX-Carousel-Custom-Examples/master/images/Half-Circle.jpg)


```css
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselPrevArrow {height:40px;line-height:40px; width: 20px; top:50%;border-radius:20px 0 0 20px;}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow span {top: 0; margin: 0}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselNextArrow {height:40px;line-height:40px; width: 20px; top:50%;border-radius:0 20px 20px 0 ;}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow {margin-top: -20px;}
```

#### Mini-Square
![](https://raw.githubusercontent.com/icharlie/IDX-Carousel-Custom-Examples/master/images/Mini-Square.jpg)


```css
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow {top: 50%; width: 25px; margin-top: -20px; height: 40px;}
```



#### Medium-Square
![](https://raw.githubusercontent.com/icharlie/IDX-Carousel-Custom-Examples/master/images/Medium-Square.jpg)


```css
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow {height: 60px; margin-top: 30px; top: 60px; background-color: transparent;}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow span{height: 100%; top: 0; margin: 0;line-height: 60px; vertical-align: middle; background-color: #000;}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow.IDX-carouselPrevArrow span{ width: 50px; left: 5px}
#IDX-carouselGallery-{{widgetID}} a.IDX-carouselArrow.IDX-carouselNextArrow span {width: 50px; right: 5px;}
```