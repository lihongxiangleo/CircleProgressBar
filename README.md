# CircleProgressBar
I's a custom CircleProgressBar
这是一个自定义的环形ProgressBar,并且带有动画增长效果,使用方便，拥有完整的属性设置。
##Effect chart(效果图)  
![circle](https://cloud.githubusercontent.com/assets/12996465/12743821/5c3008b2-c9cb-11e5-899b-738d6a5b8afb.gif)

## Include the CustomCircle widget in your layout(在布局中放入CustomCircle控件).
```
<com.byzk.customcircle.CustomCircle
        android:id="@+id/customCircle"
        android:layout_width="200dp"
        android:layout_height="200dp"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="100dp"
        app:circlePandding="20dp"
        app:circleTextColor="@color/colorAccent"
        app:circleTextSize="32sp"
        app:circleWidth="10dp"
        app:firstCircleColor="@color/colorAccent" />
```
##Attributes（xml中可设置的属性）
There are several attributes you can set:
*  __circlePandding__       
控件的padding值 内边距
*  __circleTextColor__      
文字颜色
*  __circleTextSize__       
文字大小
*  __circleWidth__          
圆弧的宽度
*  __firstCircleColor__     
进度条的颜色
*  __secondCircleColor__    
圆弧的颜色
*  __circleProgress__       
进度百分比（0~100）

##Method
1.__setTextSize(int textSize)__  
设置文字字体大小
  
2.__setTextColor(int color)__  
设置文字的颜色
  
3.__setStrockWidth(int width)__  
设置自定义CircleView的进度条宽度

4.__setDuration(long duration)__  
设置进度滚动的时间

5.__setProgress(int mProgress)__  
设置进度


