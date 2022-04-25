# lightbox2
灯箱预览图片元素,用于最流行的图片预览效果<br>
<img src="http://www.wware.org/img/dengxiang996.jpg?_8f72" width="400px"><br>
普通属性<br>
data-alwaysShowNavOnTouchDevices	如果为true，则在查看图像集时鼠标悬停时显示的左侧和右侧导航箭头将始终在支持触摸的设备上可见。	false/true<br>
data-albumLabel	查看图像集时，文字显示在标题下方。默认文本显示当前图像编号和集合中的图像总数,例如:(Image %1 of %2)	Image %1 of %2<br>
data-disableScrolling	如果为true，则在Lightbox打开时阻止页面滚动。这可以通过隐藏在主体上的设置来实现。	false/true<br>
data-fadeDuration	灯箱容器和叠加层以淡入淡出的时间（以毫秒为单位）,例如:600ms	600<br>
data-fitImagesInViewport	如果为true，则调整将扩展到视口之外的图像，以便它们整齐地放在视口内。这使用户不必滚动查看整个图像。	true/false<br>
data-imageFadeDuration	一次加载后图像淡入的时间，以毫秒为单位。例如:600ms	600<br>
data-maxWidth	如果设置，图像宽度将被限制为这个数字，以像素为单位。长宽比不会保持。	100<br>
data-maxHeight	如果设置，图像高度将被限制为这个数字，以像素为单位。长宽比不会保持	100<br>
data-positionFromTop	Lightbox容器出现的视口顶部的距离（以像素为单位）例如:50px	50<br>
data-resizeDuration	在不同尺寸的图片之间切换时，灯箱容器在宽度和高度上动画的时间（以毫秒为单位）例如:700ms	700<br>
data-showImageNumberLabel	如果设置为false，则表示当前图像编号和设置图像总数的文本（例如“4的图像2”）将被隐藏	true/false<br>
data-wrapAround	如果设置为true，则当用户到达集合中的最后一个图像时，右侧的导航箭头将出现，并且将继续向前移动，这将使其返回到集合中的第一个图像。	false/true<br>
data-lightbox	设置单独预览还是图像集预览（图像集预览是图像带导航箭头）	如果设置单独预览则属性绑定data-lightbox的值不同，图像集预览data-lightbox的值相同<br>
data-title	设置每个预览图片的标题。	设置标题用该属性绑定操作<br>
# 注意事项
1、元素每个a标签中必须要填写data-lightbox属性。<br>
2、灯箱预览图可以分两组：单独图像data-lightbox属性值不同，图像集data-lightbox属性值相同。<br>
