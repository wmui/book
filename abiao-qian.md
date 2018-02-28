# &lt;a&gt;标签

### 属性

#### download:

```
<!-- 下载hello.txt -->
<a href="test.txt" download="hello">点击下载</a>
```

说明：hello为浏览器下载后文件的名字，浏览器会自动检测文件的扩展名

#### href

```
<a href="https://github.com/wmui">GitHub</a>
```

说明：url值可以是相对地址，绝对地址，锚点\(\#top\)

#### media

```
<a href="https://github.com/wmui" media="print and (resolution:300dpi)">GitHub</a>
```

##### 运算符

| 运算符 | 描述 |
| :--- | :--- |
| and | AND运算 |
| not | NOT运算 |
| , | OR运算 |

##### 设备

| 值 | 描述 |
| :--- | :--- |
| all | 默认。适合所有设备 |
| aural | 语音合成器 |
| braille | 盲文反馈装置 |
| handheld | 手持设备（小屏幕） |
| projection | 投影机 |
| print | 打印预览模式 / 打印页面 |
| screen |  |
| tty |  |
| tv | 电视类型设备 |

##### 值

| 值 | 描述 |
| :--- | :--- |
| width | 目标显示区域的宽度（可使用min-width, max-width），例如：media = "screen and  \(min-width: 300px\) |
|  |  |
|  |  |
|  |  |

































