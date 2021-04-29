# huanghe
## 123
####  123



 https://github.com/redrumq/krowemoh/blob/8746e6868f5fc2aa0dc01d5bdb854f7418dd3366/test.md

---


网络图片：

![网络图片](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=3047467073,2356227797&fm=26&gp=0.jpg)



---



文件夹下的:

![avatar]()


---


an externalweb site:
<https://www.4399.com/>



---




a block quote:
> james
> > russell



---



 a bulleted list:
+ helen
+ rock
+ lebron



---



a numbered list:


1. 
    - banana
    - huanghe
    
2. 
    - jisuanji
    - yingyu
   
3. 
    - jilin
    - daxue

    
 ---
    
 


a table:

| 广东   | 东莞  |
|  ----  | ----  |
| 贵州  | 贵阳 |
|  湖南 | 长沙  |




---


**湖人总冠军**

*123*

~~abcd~~



---

```java
public class GeometryList extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_menulist);
        ListView demoList = (ListView) findViewById(R.id.mapList);
        // 添加ListItem，设置事件响应
        demoList.setAdapter(new DemoListAdapter(GeometryList.this, DEMOS));
        demoList.setOnItemClickListener(new AdapterView.OnItemClickListener() {
            public void onItemClick(AdapterView<?> arg0, View v, int index, long arg3) {
                onListItemClick(index);
            }
        });
    }

    void onListItemClick(int index) {
        Intent intent;
        intent = new Intent(GeometryList.this, DEMOS[index].demoClass);
        this.startActivity(intent);
    }
    
    ```
    
    
    



    







