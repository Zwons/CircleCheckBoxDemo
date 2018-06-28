# CircleCheckBoxDemo
自定义圆形CheckBox控件，继承自CheckBox，选中与未选中样式继承自Drawable。
## 截图
![运行截图](https://github.com/ymht/CircleCheckBoxDemo/blob/master/art/screenshot.gif)
## Attrs
attr|format|描述
---|:--:|---:
radius_size|dimension|内圆半径
padding_size|dimension|圆形对外部的padding
tick_size|dimension|对勾大小
stroke_size|dimension|未选中时，边框大小
tickColor|color|对勾的颜色
checkedColor|color|选中时，圆的颜色
uncheckedColor|color|未选中时，圆的颜色
strokeColor|color|未选中时，圆的边框的颜色
## 使用
```
    <!--默认-->
    <com.ymht.circlecheckboxdemo.checkbox.CircleCheckBox
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
        
    <!--配置-->
    <com.ymht.circlecheckboxdemo.checkbox.CircleCheckBox
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:checkedColor="@android:color/holo_orange_light"
        app:padding_size="10dp"
        app:radius_size="20dp"
        app:strokeColor="@android:color/holo_red_light"
        app:stroke_size="5dp"
        app:tickColor="@android:color/holo_blue_bright"
        app:tick_size="2dp"
        app:uncheckedColor="@android:color/holo_green_light" />
```
## License

MIT License

Copyright (c) 2018 ymht

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

