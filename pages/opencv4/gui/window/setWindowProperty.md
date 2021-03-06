---
title: 윈도우 속성 설정
sidebar: opencv4_sidebar
permalink: setWindowProperty
folder: opencv4
---

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">setWindowProperty</h2>
    </div>
    <div class="col-lg-12">

        <ul id="myTab" class="nav nav-tabs nav-justified">
            <li class="active"><a href="#service-one" data-toggle="tab"><i class="fa fa-support"></i> C++</a>
            </li>
            <li class=""><a href="#service-two" data-toggle="tab"><i class="fa fa-support"></i> C#</a>
            </li>
            <li class=""><a href="#service-three" data-toggle="tab"><i class="fa fa-support"></i> Python</a>
            </li>
        </ul>

        <div id="myTabContent" class="tab-content">
            <div class="tab-pane fade active in" id="service-one">
<pre class="prettyprint"><code class="language-cpp">void cv::setWindowProperty(
    const String& winname,
    int prop_id,
    double prop_value
)</code></pre>
            </div>
            <div class="tab-pane fade" id="service-two">
<pre class="prettyprint"><code class="language-cs">void Cv2.SetWindowProperty(
    string winName,
    WindowPropertyFlags propId,
    double propValue
)</code></pre>
            </div>
            <div class="tab-pane fade" id="service-three">
<pre class="prettyprint"><code class="language-py">None = cv2.setWindowProperty(
    winname,
    prop_id,
    prop_value
)</code></pre>
            </div>
        </div>
    </div>
</div>

<br>

### 요약(Summary)

> 윈도우의 속성을 설정합니다.

### 매개변수(Parameter)

> `윈도우 이름(winname)` 속성을 변경하려는 윈도우 이름

> [`속성 이름(prop_id)`](WindowPropertyFlags) 변경하려는 속성 이름

> [`속성값(prop_value)`](WindowPropertyFlags) 변경하려는 속성 값

### 반환값(Returns)

> `없음`