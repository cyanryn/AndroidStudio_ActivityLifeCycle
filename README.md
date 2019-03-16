### 实验内容：展示Activity生命周期

![Activity整个生命周期的过程](https://i.loli.net/2019/03/15/5c8b6fd629ab7.png)

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
![](https://i.loli.net/2019/03/16/5c8ce9845d972.png)
##### ②回到home界面：
![](https://i.loli.net/2019/03/16/5c8cbff7999d5.png)
##### ③回到程序界面：
![](https://i.loli.net/2019/03/16/5c8cc0f67107a.png)
##### ④退出程序：
![](https://i.loli.net/2019/03/16/5c8cc1d058610.png)
