# README语法
**语法参考 [github help](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)**  
**快捷键参考 [github keyboard](https://help.github.com/en/articles/using-keyboard-shortcuts)**
***
编写README.md 目录 :
- [标题](#标题)
- [文本样式](#文本样式)
- [文本引用](#文本引用)
- [代码引用](#代码引用)
- [链接](#链接)
- [Section links](#部分链接)
- [Relative links](#相对链接)
- [列表](#列表)
- [Task lists](#任务列表)
- [Mentioning people and teams](#提及人和团队)
- [引用问题和提取请求](#引用问题和提取请求)
- [内容附件](#内容附件)
- [表情](#表情)
- [段落换行符](#段落换行符)
- [Ignoring Markdown formatting](#忽略Markdown格式)  
- [Further reading](#Further-reading)  

## 标题  
 标题的格式：需要1——6个“#”号声明这是个标题，“#”号的个数代表了标题的大小
 ```
 # 一级标题
 ## 二级标题
 ###### 最小一级标题
 ```
 ![image](https://help.github.com/assets/images/help/writing/headings-rendered.png)

## 文本样式
  可以使用粗体，斜体或删除线文本来指示强调。  
 
  | 格式 | 语法 | 快捷键 | 例子 | 输出 |
  | ----------- | ----------- | ----------- | ----------- | ----------- |
  | 粗体 | ** ** 或 __ __ | control/command + b | `**粗体**` | **粗体** |
  | 斜体 | * * 或 _ _ | control/command + i | `*斜体*` | *斜体* |
  | 删除线 | ~~ |  | `~~错误的文本~~` | ~~错误的文本~~ |
  | 加粗倾斜 | ** ** 和 _ _ |  | `**加粗_倾斜_的文本**` |  **加粗 _倾斜_ 的文本** |

## 文本引用
  可以使用“>”号表示引用文本
  ```
  用他的话来说
  > 原谅我的法语
  ```
  用他的话来说
  > 原谅我的法语
  
## 代码引用
  可以使用反引号修饰句子的中代码或命令，反引号中的文本不会被格式化  
  ```Use `git status` to list all new or modified files that haven't yet been committed.```  
  **Use `git status` to list all new or modified files that haven't yet been committed.** 
    
  三个反引号划分引用块  
  ```
  Some basic Git commands are:

  git status
  git add
  git commit
  ```
## 链接
  链接的格式：`[链接文本](链接URL)`  
  `This site was built using [GitHub Pages](https://pages.github.com/).`  
  ![image](https://help.github.com/assets/images/help/writing/link-rendered.png)  
  
## 部分链接  
  ``` [标题](#标题) ```

## 相对链接
 定义跳转到库中其他目录或文件的链接  
 ~~[Contribution guidelines for this project] (docs/CONTRIBUTING.md)~~  
 ``` [到test文件](./text.txt)```  
 [到test文件](./test.txt)
## 列表  
 可以通过 - 或* 添加一行或多行文本来创建无序列表。  
 ```
 - George Washington
 - John Adams
 - Thomas Jefferson
 ```  
 - George Washington
 - John Adams
 - Thomas Jefferson  
 
 可以使用编号：  
 ```
 1. James Madison
 2. James Monroe
 3. John Quincy Adams
 ```  
 1. James Madison
 2. James Monroe
 3. John Quincy Adams  
 
 列表层级：  
 ```
 1. First list item
    - First nested list item
      - Second nested list item（注意这里-的位置）
 ```  
 1. First list item
    - First nested list item
      - Second nested list item  

## 任务列表  
 任务列表，列表符号`-`后跟`[]`符号，完成的任务标记为x  
 ```
 - [x] 任务1
 - [ ] 任务2
 - [ ] 任务3
 ```  
 - [x] 任务1
 - [ ] 任务2
 - [ ] 任务3  


## 提及人和团队  
 可以在GitHub上提一个人或团队，输入@ plus他们的用户名或团队名。 这将触发通知并将他们的注意力引向对话。 如果您编辑评论以提及其用户名或团队名称，也会收到通知。  
 ` @baocaixue What do you think about these updates?`  
 @baocaixue What do you think about these updates?

## 引用问题和提取请求  
 [Autolinked references and URLs.](https://help.github.com/en/articles/autolinked-references-and-urls)

## 内容附件  
 [Using Content Attachments](https://developer.github.com/apps/using-content-attachments/)

## 表情  
 @octocat :+1: This PR looks great - it's ready to merge! :shipit: :smile:


## 段落换行符  
 可以通过在文本行之间留一个空行来创建新段落。

## 忽略Markdown格式  
 You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.  
 
## Further-reading
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- ["About writing and formatting on GitHub"](https://help.github.com/en/articles/about-writing-and-formatting-on-github)
- ["Working with advanced formatting"](https://help.github.com/en/articles/working-with-advanced-formatting)
- ["Mastering Markdown"](https://guides.github.com/features/mastering-markdown/)
