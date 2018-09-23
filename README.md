# Android开发的单机版天气预报

# secondapplication
# 开发工具（android studio）
## 天气预报界面效果图预览

![image.png](https://upload-images.jianshu.io/upload_images/14162866-8e55eea6efbcc179.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


1.1. 顶部工具栏

- 效果图
![image.png](https://upload-images.jianshu.io/upload_images/14162866-8f89400bc53decb3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



采用`<LinearLayout>`中嵌套`<LinearLayout>`布局实现

- 左 - 水平方向

`<LinearLayout>`放1个`<ImageView>`组件

![image.png](https://upload-images.jianshu.io/upload_images/14162866-a9a74958f2b9dcef.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


- 中 - 水平方向

`<LinearLayout>`放1个`<TextView>`组件

![image.png](https://upload-images.jianshu.io/upload_images/14162866-27eff5ba89f00aa8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


- 右 - 水平方向

`<LinearLayout>`放3个`<ImageView>`组件

![image.png](https://upload-images.jianshu.io/upload_images/14162866-7c5d5351533134d2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


1.2. 主界面上部
- 效果图
![image.png](https://upload-images.jianshu.io/upload_images/14162866-abab712986996854.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


采用`<LinearLayout>`中嵌套`<RelativeLayout>`布局实现

- 1.3. 主界面中部


`<LinearLayout>`中放`<TextView>`
![image.png](https://upload-images.jianshu.io/upload_images/14162866-c851f508936a264b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



- 1.4. 主界面底部

`<LinearLayout>`中放`<TextView>`，左中右等比布局

![image.png](https://upload-images.jianshu.io/upload_images/14162866-0b9cc32a60b8fe78.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
