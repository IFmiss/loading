![](https://github.com/IFmiss/loading/blob/master/images/MA4poJbQzw1.gif)

![](https://img.shields.io/badge/IE-10%2B-orange.svg)

# loading
一个兼容移动端pc以及ie10以上的loading插件

演示地址: http://www.daiwei.org/components/loading/


### direction
方向，column纵向   row 横向
### animateIn
进入类型,这里不需要引用animatecss(因为个人觉得loading效果不需要太花哨,默认fadeInNoTransform,其他设置都不会有动画效果)
### title
loading的title名称  为'' 则不显示
### titleColor
title的文字颜色
### name
loading的name名称 这算是唯一标识,重复的name的loading不会再生成,因此每次需要给一个name属性
### type
loading显示的样式   是转动的小圆球 origin  还是图片 pic
### discription
loading的描述  为'' 则不显示
### discColor
loading的描述颜色
### loadingWidth
默认260    loading的宽度
### loadingBg
默认 'rgba(0, 0, 0, 0.6)'    loading的背景色
### borderRadius
默认12   loading的圆角
### loadingMaskBg
默认 transparent   loading的遮罩层背景色
### zIndex
默认 1000001   loading的层级

#### 圆形旋转的loading样式  （origin）
### originDivWidth
默认 60   loading内部圆球区域的宽度
### originDivHeight
默认 60   loading内部圆球区域的高度
### originWidth
默认 8   小圆球的宽度
### originHeight
默认 8   小圆球的高度
### originBg 
默认'#fefefe'  小圆球的背景色
### smallLoading
默认 false   是否显示更小一点的旋转小球效果

#### 这是图片的样式   （pic）
### imgSrc
默认的图片地址
### imgDivWidth
默认 80  图片的宽度
### imgDivHeight
默认 80  图片的高度

### flexCenter
默认false,  是否用flex布局让loading-div垂直水平居中
### flexDirection
默认'row'  row column  flex的方向   横向 和 纵向
### mustRelative
默认false  调用loading的元素是否规定relative


