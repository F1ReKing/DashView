# DashView
[![](https://jitpack.io/v/F1ReKing/DashView.svg)](https://jitpack.io/#F1ReKing/DashView)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/F1ReKing/StatusLayout/blob/master/LICENSE)   
<p>一个在Android上的虚线控件</p>

## 预览图

<a href="art/dashview.png"><img src="art/dashview.png" width="30%"/></a>

## 引入

#### Step 1. Add the JitPack repository to your build file
```
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

#### Step 2. Add the dependency
```
	dependencies {
	       compile 'com.github.F1ReKing:DashView:x.y.z'
	}
```
Current latest version: [![](https://jitpack.io/v/F1ReKing/DashView.svg)](https://jitpack.io/#F1ReKing/DashView)
## 使用
```java
<com.f1reking.library.dashview.DashView
  android:layout_width="300dp"
  android:layout_height="wrap_content"
  app:dashOrientation="0"
  app:dashWidth="2dp"
  app:lineColor="#FF4081"
  app:lineHeight="2dp"
  app:lineWidth="4dp"
  />
```
### 属性：

| 属性名             | 字段        | 描述              | 默认值       |
| --------------- | --------- | --------------- | --------- |
| dashOrientation | integer   | 虚线方向(0：水平；1：竖直) | 0         |
| dashWidth       | dimension | 虚线间距            | 4dp       |
| lineColor       | color     | 虚线颜色            | #ff888888 |
| lineHeight      | dimension | 虚线高度            | 2dp       |
| lineWidth       | dimension | 虚线宽度            | 4dp       |

## License

```
Copyright 2017 F1ReKing. 

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
