# BarrierSearch

## 简介

    现在用单一搜索引擎，获得实用信息有限。定义专属搜索引擎组合，满足日常需求。

* 1.Chrome自带的搜索引擎只能在地址栏中调用；不支持多请求；添加过多，使用时容易忘记。

* 2.此脚本除了解决以上问题，还可以识别 `页面选择文本`。

* 3.浏览器可能会`拦截`部分窗口，手动允许。

## 快捷键

* 1.`Alt+x` ：脚本的开关。
  
* 2.`鼠标左键`：单个搜索引擎的开关。

* 3.`鼠标右键`：关闭其他搜索引擎。

## 搜索引擎

* **第一种：搜索字符在地址中**
  
    >将地址中的`搜索字符`替换为 `%s`  

    >名称：百度搜索  
    地址：`https://www.baidu.com/s?ie=UTF-8&wd=%s`

* **第二种：搜索字符在请求体中**
    >地址不用修改, 直接复制地址栏的地址。  
    控制台找到请求体，将其中的搜索字符替换为`%s`  

    >名称：subscene  
    地址：`https://subscene.com/subtitles/searchbytitle`  
    数据：`query=%s&l=`

* **中文乱码**
  
    >勾选 `复选框`

    >名称：美剧天堂  
    地址：`https://www.meijutt.tv/search/index.asp`  
    数据：`searchword=%s`  
    勾选 `复选框`

## 常用网站

>名称: **谷歌搜索**  
地址：`https://www.google.com/search?q=%s&ie=UTF-8`

>名称: **YOUTUBE**  
地址：`https://www.youtube.com/results?search_query=%s`

>名称: **B站**  
地址：`https://search.bilibili.com/all?keyword=%s`

>名称: **豆瓣**  
地址：`https://www.douban.com/search?q=%s`

>名称: **CSDN**  
地址：`https://so.csdn.net/so/search?q=%s`

>名称: **贴吧**  
地址：`https://tieba.baidu.com/f?ie=utf-8&kw=%s&fr=search`

>名称: **知乎**  
地址：`https://www.zhihu.com/search?type=content&q=%s`

>名称: **简书**  
地址：`https://www.jianshu.com/search?q=%s`

>名称: **IMDB**  
地址：`https://www.imdb.com/find?q=%s`
