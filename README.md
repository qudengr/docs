# Markdown 编写样例

## 一、标题与文字格式

格式:

1. `#` 符号表示标题等级
   * \# 一级标题
   * \## 二级标题
   * \### 三级标题
2. `Enter` 段落
   * 段落之间空一行
   * 段落之间空一行
3. 换行符
   * 一行结束时输入两个空格来换行
   * 一行结束时输入两个空格来换行
4. `** **` 符号表示文字粗体格式
   * **粗体文字**
5. `* *` 符号表示文字斜体格式
   * _斜体文字_
6. `~~ ~~` 符号表示文字带删除线格式
   * ~~文字带删除线~~
7. `== ==` 符号表示高亮
   * \==高亮显示==
8. `- [ ] -`符号表示方框
   *
     * [ ] \-

* \# 一级标题
* \## 二级标题
* \### 三级标题

## 二、引用

格式:`>` 符号表示引用

> 引用他人内容

## 三、列表

格式:

1.  无序列表

    `* 列表1`\
    `* 列表2`
2.  有序列表

    `1. 列表1`\
    `2. 列表2`\
    `3. 列表3`

效果：

* 无序列表1
* 无序列表2
* 无序列表3

1. 有序列表1
2. 有序列表2
3. 有序列表3

## 四、代码块

格式:

1. ` `` `单行代码
2. ` ``` ``` `多行代码

效果：

`<hello world>`

```
class HelloWorld {
    public static void main(String[] args) {
       System.out.println("Hellow World!");
    }
}
```

## 五、表格

格式:

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned |    $1 |
| col 2 is      | centered      |    $1 |
| zebra stripes | are neat      |    $1 |
```

效果：

| Tables   |      Are      | Cool |
| -------- | :-----------: | ---: |
| col 3 is | right-aligned |   $1 |
| col 2 is |    centered   |   $1 |
| col 1 is |  left-aligned |   $1 |

## 六、超链接

格式:

`[超链接说明](超链接)`

效果:

[点击访问郝晓龙主页](http://www.haoxiaolong.cn)

## 七、图片

格式:

`![图片说明](图片超链接)`

效果：

[![Nice Tool](https://vkceyugu.cdn.bspapp.com/VKCEYUGU-imgbed/8f959db3-8915-4a79-ac7c-079ab66edaf2.png)](https://imgbed.cn)

## 八、分割线

格式：

`***`

效果：

***

## 九、脚注

格式：

```
[^脚注]  
[^脚注]：https://www.haomuyang.com
```

效果：

欢迎访问我的主页[^1](https://www.haomuyang.com)
