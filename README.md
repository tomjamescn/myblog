#学习和测试markdown语法

本文用来学习和测试markdown语法

新的段落

>这个是引用

*这个是斜体*

_这个也是斜体_

**这个是粗体**

##无序列表
* item1
* item2
* item3

- item1
- item2
- item3

##有序列表
1. item1
2. item2
3. item3

[链接](http://test)



#GFM(GitHub Flavored Markdown)引入的一些特殊格式

##单词中的下划线（multiple underscores in words）
this_is_test

##中间的横线(strikethrough)
~~中间的横线~~

##代码块
```
function test() 
{

}
```

##语法高亮代码快
```php
function test()
{
    $t = 1;
    return $t;
}
```

##表格
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell


| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

并不需要对齐

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

多个语法使用

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

对齐

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |




