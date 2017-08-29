相关资料查阅：
* [CMDB](http://www.linuxde.net/2015/09/15704.html)
* [JUMPSERVER](https://github.com/jumpserver/jumpserver/)
## 大纲

### 前台WEB端
> 用户管理
>> 用户（WEB登录用户）
>> 角色/用户组

> 资产管理
>> 资产（可实现信息收集）
>> 资产组
>> 机房
>> 管理用户（terminal登录用户）
>> 系统用户(ssh登录)

> 权限管理
>> 资产授权（terminal登录）

> 应用程序
>> 终端授权

> 任务中心
>> 发布（管理用户推送）

> 审计
>> 在线用户
>> 登录日志
>> 命令日志
>>

> 上传
>> 上传文件到指定目录

### 终端(WEB页面执行,jsshell)

> 跳板
>> 1) 输入 ID 直接登录 或 输入部分 IP,主机名,备注 进行搜索登录(如果唯一)

>> 2) 输入 / + IP, 主机名 or 备注 搜索. 如: /ip

>> 3) 输入 P/p 显示您有权限的主机.

>> 4) 输入 G/g 显示您有权限的主机组.

>> 5) 输入 G/g + 组ID 显示该组下主机. 如: g1

>> 6) 输入 E/e 批量执行命令.(未完成)

>> 7) 输入 U/u 批量上传文件.(未完成)

>> 8) 输入 D/d 批量下载文件.(未完成)

>> 9) 输入 H/h 帮助.
>> 0) 输入 Q/q 退出.

H1
========
H3
-------
# H1
### H3

> qqqq
> qqqqq

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.


> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");


*   Red
*   Green
*   Blue


1.  Bird
1.  McHale
1.  Parish


*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.
    

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
    
    
*   一列表项包含一个列表区块：

        <代码写在这>
        

1986\. What a great season.


这是一个普通段落：

    这是一个代码区块。
    
    
    
*****


This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

See my [About](/about/) page for details.

---------------------------------------


This is [an example][id] reference-style link.

[id]: http://example.com/  "Optional Title Here"

---------------------------------------


Visit [Daring Fireball][] for more information.
[Daring Fireball]: http://daringfireball.net/

![Alt text](http://img.eol.cn/images/ed/index/2013/logo.png "Optional title")

![Alt text][id]
[id]: http://img.eol.cn/images/ed/index/2013/logo.png  "Optional title attribute"

<http://example.com/>

<address@example.com>


*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

un*frigging*believable

\*this text is surrounded by literal asterisks\*

Use the `printf()` function.

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

``There is a literal backtick (`) here.``

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.
