# huanghe
## 123
####  123



 https://github.com/redrumq/krowemoh/blob/8746e6868f5fc2aa0dc01d5bdb854f7418dd3366/test.md

---


网络图片：

![网络图片](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.ccutu.com%2Fupload%2Fimage%2F20180126%2F6365256871015825663924036.jpg&refer=http%3A%2F%2Fimg.ccutu.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1622291295&t=fbb7433a7e58c8f4b78e35e440e79814)



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
    
    
    



    







