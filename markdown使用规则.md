# Markdown使用规则
<!-- 这是一条注释，它不会在渲染后的文档中显示 -->

## 标题
用若干"#"表示标题的级别，最多六级。

## 段落和换行
直接编写文字来创建段落。要在段落之间添加空行来进行换行。

## 强调
- *斜体* 或 _斜体_：将文字两边各加上一个 * 或 _。
- **粗体** 或 __粗体__：将文字两边各加上两个 * 或 _。
- 粗斜体 或 ***粗斜体***：
  - 将文字两边各加上三个 * 或 _。

## 列表
  1. 无序列表：使用 - + * 符号作为列表标记，后面加上空格。
  2. 嵌套列表：在子列表的第一行加上 4 个空格。
  3. 有序列表：使用数字和点作为列表标记，后面加上空格。

## 链接
[我的B站主页](https://space.bilibili.com/3546380654086848/favlist?fid=3437317448&ftype=create)

## 图片
![这是一张图片哈哈哈](https://cn.bing.com/images/search?view=detailV2&ccid=5gnmANLH&id=BD66D41454D3FF11BCD4D977CB21291937EC09E8&thid=OIP.5gnmANLHi1QlkUSMF0FTZwAAAA&mediaurl=https%3A%2F%2Fwww.runoob.com%2Fwp-content%2Fuploads%2F2019%2F03%2Ficonfinder_markdown_298823.png&exph=128&expw=128&q=markdown%E5%9B%BE%E6%A0%87&simid=608043082350617455&FORM=IRPRST&ck=6F3FFBA733F23BD0E74D34BE51071BDC&selectedIndex=0&itb=1&cw=1145&ch=607&ajaxhist=0&ajaxserp=0 "markdown图标")

## 引用
在引用的文字前加上 >。
> 这是一个引用哈哈哈。

> 1234

## 代码
- 行内代码：用一对反引号包围代码 code。

`include <iostream>`
- 代码块：用三个反引号包围代码块或者用四个空格缩进。
```c
#include <iostream>
using namespace std;

int main() {
  cout << "Hello, World!" << endl;
  return 0;
}
```

## 表格
| 表头1 | 表头2 | 表头3 |
| ----- |----- | ----- |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

## 分割线
三个或三个以上的 - 、* 或 _ 符号。

## 公式
$$E=mc^2$$

## 任务列表
- [x] 已完成任务
- [ ] 未完成任务

## 脚注
这是一个脚注的例子。[^1]

[^1]: 这是一个实际的脚注内容。

## 目录

- [一级标题哈哈](#标题)
- [二级标题](#段落和换行)
  - [二级标题下的三级标题](#二级标题下的三级标题)
- [另一个一级标题](#公式)


## 标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题



