# DotCircleProgress
a circle constructed by dots. can be used as progress bar or percentage indicator.

![image](https://github.com/liuxu0703/DotCircleProgress/blob/master/DotCircleDemo.gif)

#Usage:

```xml
<lx.af.widget.DotCircleProgress
    android:id="@+id/dot_circle_tiny"
    android:layout_width="55dp"
    android:layout_height="55dp"
    android:layout_alignParentRight="true"
    android:layout_alignParentBottom="true"
    android:layout_margin="10dp"
    app:dotCount="12"
    app:dotProgress="210"
    app:dotColor="#d5dce4"
    app:dotSpinRadius="8dp"
    app:dotSpinColor="7b858e"
    app:dotSpinSpeed="180"
    app:dotSpinTailCount="3" />
```

 **dotCount**:
 dot count. default is 24.

 **dotRadius**:
 dot radius. default radius is determined by dot count.

 **dotColor**:
 dot color. default is white

 **dotProgress**:
 initial progress, range [0-360]. default is 0.

 **dotSpinRadius**:
 spinning dot radius. default is dotRadius * 2.

 **dotSpinColor**:
 spinning dot color. default is the same as dotColor.

 **dotSpinSpeed**:
 spinning speed, degree per second. default is 240. for example, if set to 360, it will spend 1 second to startSpin a whole circle.

 **dotSpinTailCount**:
 spinning tail count. default is dotCount / 6 .

#License:

 ```
 The MIT License (MIT)

 Copyright (c) 2016 Lyux

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
 ```