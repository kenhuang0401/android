# TextView 文字
就單純是顯示文字，但很重要。

### layout
``` java=
android:text="個人資料"
android:textSize="42dp"     //文字大小
android:textColor="#000000" //文字顏色
android:text="weather"      //文字內容
android:textStyle="bold"    //文字樣式，目前是粗體
android:hint="提示文字"      //提示文字，打字後消失
android:gravity="center"    //文字在元件的位置
  ```

### Activity
``` java=
TextView text;
text = findViewById(R.id.textView);

text.setText("hello");   //設定元件text顯示的文字
  ```
