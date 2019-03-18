# ActivityApplication
test life cycle  
**代码功能**：测试activity的生命周期。  
**代码：**
```
public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.i("MainActivity","调用onCreate()");
    }
    @Override
    protected void onStart(){
        super.onStart();
        Log.i("MainActivity","调用onStart()");
    }
    @Override
    protected void onResume(){
        super.onResume();
        Log.i("MainActivity","调用onResume()");
    }
    @Override
    protected void onPause(){
        super.onPause();
        Log.i("MainActivity","调用onPause()");
    }
    @Override
    protected void onStop(){
        super.onStop();
        Log.i("MainActivity","调用onStop()");
    }
    protected void onDestroy(){
        super.onDestroy();
        Log.i("MainActivity","调用onDestroy()");
    }
}
```
**结果截图:**  
![image text](https://github.com/2017023633/hello-world/blob/master/image/%E5%AE%9E%E9%AA%8C1.1%E6%88%AA%E5%9B%BE.png)
![image text](https://github.com/2017023633/hello-world/blob/master/image/%E5%AE%9E%E9%AA%8C1.2%E6%88%AA%E5%9B%BE.png)
