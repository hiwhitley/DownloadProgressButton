# DownLoadProgressButton

An awseome Download Button with Progress.

## ScreenShot

![demo](http://ww1.sinaimg.cn/large/8e985f95gy1fczixyzo6dg207i0dcgov)

## Usage

you can define the button in xml like this:

```xml
 <com.hiwhitley.downloadprogressbutton.DownloadProgressButton
        android:id="@+id/download_btn"
        android:layout_width="match_parent"
        android:layout_height="40dp"
        app:progress_btn_background_color="@color/colorAccent"
        app:progress_btn_radius="5dp"
        app:progress_btn_background_second_color="@color/colorPrimary"
        app:progress_btn_text_color="@android:color/black"
        app:progress_btn_text_cover_color="@android:color/white"
        app:progress_btn_ball_style="STYLE_BALL_PULSE"
        app:progress_btn_border_width="2dp" />
```

the Customized properties are in the follow table:

| Property                             |  Format   |             Default              |
| ------------------------------------ | :-------: | :------------------------------: |
| progress_btn_radius                  | dimension |               0dp                |
| progress_btn_background_color        |   color   |             #3385FF              |
| progress_btn_background_second_color |   color   |             #E8E8E8              |
| progress_btn_text_color              |   color   |  progress_btn_background_color   |
| progress_btn_text_cover_color        |   color   |           Color.WHITE            |
| progress_btn_border_width            | dimension |               2dp                |
| progress_btn_ball_style              |   enum    | STYLE_BALL_PULSE，STYLE_BALL_JUMP |

 The follow picture make a clear explanation:

 ![](http://ww1.sinaimg.cn/mw690/8e985f95gy1fczjrgbxndj20s90g7mzv)v)

## License

    Copyright 2017 hiwhitley.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.