AutoScrollTextView
=====================

Sample Android application show how to set auto scroll in text view in android.

Usage
-----

To make a auto scroll in your text view, you must use the following properties in your XML.

Properties:
* `ellipsize`
* `focusable`
* `focusableInTouchMode`
* `marqueeRepeatLimit`
* `scrollHorizontally`
* `singleLine`


XML
-----

```xml
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:ellipsize="marquee"
    android:focusable="true"
    android:focusableInTouchMode="true"
    android:marqueeRepeatLimit="marquee_forever"
    android:scrollHorizontally="true"
    android:singleLine="true"
    android:text="@string/your_value"
    tools:ignore="HardcodedText" />
```


Image Result
-----

![Capture Project](http://i39.tinypic.com/2n0rdlg.png)

LICENCE
-----

AutoScrollTextView by [Lopez Mikhael](http://mikhaellopez.com/) is licensed under a [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).
