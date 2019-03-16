### 实验内容：展示Activity生命周期

![Activity整个生命周期的过程](http://upload-images.jianshu.io/upload_images/16602345-336b8ecb343ca5cb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 代码：
```
 @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.d(TAG,"onCreate");
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.d(TAG,"onStart");
    }

    @Override
    protected void onResume() {
        super.onResume();
        Log.d(TAG,"onResume");
    }


    @Override
    protected void onPause() {
        super.onPause();
        Log.d(TAG,"onPause");
    }

    @Override
    protected void onStop() {
        super.onStop();
        Log.d(TAG,"onStop");
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d(TAG,"onDestroy");
    }
```
### 截图：

##### ①启动程序：
![image](https://t1.picb.cc/uploads/2019/03/16/VaNvVF.png)
##### ②回到home界面：
![image](http://upload-images.jianshu.io/upload_images/16602345-f5387adff05c32bc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##### ③回到程序界面：
![image](http://upload-images.jianshu.io/upload_images/16602345-1750fa8ab801bb8a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##### ④退出程序：
![image](http://upload-images.jianshu.io/upload_images/16602345-36b2226925658744.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
