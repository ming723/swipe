# swipe Activity左滑返回

#### 如何使用

###### 让Activity直接继承BaseSwipeBackActivity，如果要让多个Activity都能实现左滑返回，直接让BaseActivity继承

##### 记得初始化

```
public class App extends Application{
    @Override
    public void onCreate() {
        super.onCreate();
        SlideFinishManager.getInstance().init(this);
    }
}
```

