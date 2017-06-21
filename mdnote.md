# ***<center>markdown 个人笔记</center>***
**<h6 style="text-align:right">by yiro</h6>**
----------------------------------------------

### **对齐**
```
<center> 这是要写的文字（居中对齐） </center>
<h6 style="text-align:right">这是要写的文字（右对齐）</h6>
<h6 style="text-align:left">这是要写的文字（左对齐）</h6>

note:
    h6为标题标签，也可以采用<p></p>段落标签，<article></article>文章标签,可能还有其他标签适用
```

### **<font face="STKaiti">字体</font>**
```
<font face="微软雅黑">我是这是要写的文字</font>
<font color=#00ffff>我是这是要写的文字</font>
<font color=#00ffff size = 2>我是这是要写的文字</font>

note:
    size:规定为文本大小，最大72，最小1
```
>[颜色对照表](./colortable.png)<br>
>[中文字体对照表](./charactertable.png)

### **图像**
行内式：<br>
    `！[图片名称](连接)`<br>
eg:
```
    ！[color](./colortable.png)
```
参考式:<br>
格式：
```
![name][link] 
ps：这里有空行不能省略      
[link]:url<br>
```

eg:
```
    ![color][num]
    ps：这里有空行不能省略
    [num]:./colortable.png
```
```
    note: 可以适用html的<img>标签优化效果
    <img src="url" alt="GitHub" title="GitHub,Social Coding" width="50" height="50" />
```

### **超链接**
格式：`[name][url]`
```
    行内式
    [Google](http://www.google.com/)
    参考式
    [Google][]
    ps：这里有空行不能省略
    [Google]: http://www.google.com/ "Google"
    使用 <> 包括的 URL 或邮箱地址会被自动转换为超链接：<http://www.google.com/>
```

### **代码块**
行间代码适用``

代码块：可以使用`tab键`开头

### **换行**
段落的前后必须是空行

如果需要在段落内加入换行<br>



