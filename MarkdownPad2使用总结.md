### MarkdownPad2使用总结 ###
2018/5/3 21:55:06 
1. 工具-在浏览器中预览，快捷键F6

1. 插入时间戳：Ctrl+T
2. 插入粗体：Ctrl+B
3. 插入斜体：Ctrl+I
4. 插入引用Quote：Ctrl+Q
5. 插入1-4级标题：Ctrl+（1-4）
6. 插入超链接：Ctrl+L
7. 插入图片：Ctrl+G
8. 插入无序列表：Ctrl+U
9. 插入有序列表：Ctrl+Shift+O
10. 插入水平分隔线Horizontal Rule：Ctrl+R，三个及以上的-也可。
11. 插入多级列表：需多级列表，请在二级列表前空两个空格，三级列表前空五个空格，四级列表前空九个空格
12. 插入代码：Ctrl+K；用一对'把代码包起来，单行代码块。
用一对'''把代码包起来，形成多行代码块。Tab缩进实现代码块。
13. 撤销：Ctrl+Z
14. 重做：Ctrl+Y
12. 表格语法

	|dog|cat|pig|
|:----:|:----:|:----:|
|1|2|3|
|4|5|6|
1. 跨表格编号连续：表格首行缩进即可。
2. 流程图与时序图：
> '''flow
> st=>start:Start
> e=>end
> op=>operation:My OP
> cond=>condition:Yes or No?
> st->op->cond
> cond(yes)->e
> cond(no)->op
> '''

'''flow
st=>start:Start
e=>end
op=>operation:My OP
cond=>condition:Yes or No?
st->op->cond
cond(yes)->e
cond(no)->op
'''