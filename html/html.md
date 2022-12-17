#### 文本标签

##### div是块元素

##### span是行内元素

##### h1-h6

##### p pre br hr i b del ins

#### 图片

##### img 有src alt height等属性

#### 音频视频

```html
<audio
    controls
    src="/audios/bgm.mp3">
	<!--这里放如果不能播放后展示的内容-->
</audio>
```

```html
<audio controls>
    <source src="/audios/sound1" type="audio/mpeg"/>
    <source src="/audios/sound2" type="audio/mpeg"/>
</audio>
```

```html
<video controls width="800">

    <source src="/videos/video1.mp4"
            type="video/mp4">

    <source src="/videos/video2.mp4"
            type="video/mp4">

    Sorry, your browser doesn't support embedded videos.
</video>
```



#### 超链接

> <a></a>

target=""

- `_self`：当前窗口打开，这是默认值。
- `_blank`：新窗口打开。

#### 表单

由form包裹

```html
    <label for="age">年龄</label>
    <input type="number" name="age" id="age" required placeholder="年龄">
```

```html
<label for="pet-select">Choose a pet:</label>

<select name="pets" id="pet-select">
    <option value="">--Please choose an option--</option>
    <option value="dog">Dog</option>
    <option value="cat">Cat</option>
    <option value="hamster">Hamster</option>
    <option value="parrot">Parrot</option>
    <option value="spider">Spider</option>
    <option value="goldfish">Goldfish</option>
</select>
```

```html
    <label for="resume">个人简介</label>
    <textarea  name="resume" id="resume" placeholder="个人简介"></textarea>
```

#### 列表

```html
<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ul>
<ol>
  <li>Fee</li>
  <li>Fi</li>
  <li>Fo</li>
  <li>Fum</li>
</ol>
```



#### 表格

```html
<table>
    <caption>My Table</caption>
    <thead>
        <tr>
            <th colspan="2">The table header</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>The table body</td>
            <td>with two columns</td>
        </tr>
    </tbody>
</table>
```



#### 语义标签

```html
<header>
<nav>
<section>
<figure>
<figcaption>
<article>
<aside>
<footer>
```

#### 特殊符号

<hr>
<table>
<thead>
<tr>
<th>HTML源代码</th>
<th>显示结果</th>
<th>描述</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>&amp;lt;</code></td>
<td>&lt;</td>
<td>小于号或显示标记</td>
</tr>
<tr>
<td><code>&amp;gt;</code></td>
<td>&gt;</td>
<td>大于号或显示标记</td>
</tr>
<tr>
<td><code>&amp;amp;</code></td>
<td>&amp;</td>
<td>可用于显示其它特殊字符</td>
</tr>
<tr>
<td><code>&amp;quot;</code></td>
<td>“</td>
<td>引号</td>
</tr>
<tr>
<td><code>&amp;reg;</code></td>
<td>®</td>
<td>已注册</td>
</tr>
<tr>
<td><code>&amp;copy;</code></td>
<td>©</td>
<td>版权</td>
</tr>
<tr>
<td><code>&amp;trade;</code></td>
<td>™</td>
<td>商标</td>
</tr>
<tr>
<td><code>&amp;nbsp;</code></td>
<td></td>
<td>不断行的空白</td>
</tr>
</tbody>
</table>
        </div>