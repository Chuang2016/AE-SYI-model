R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:


<img src="pressure-1.png" style="display: block; margin: auto;" />

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
## 插入表格
| 记法 | 含义 |
| :-: |:-----:|
| %N | 作业号 |
| %S | 以字符串S开头的被(命令行)调用的作业 |
| %?S | 包含字符串S的被(命令行)调用的作业 |
| %% | "当前"作业(前台最后结束的作业, 或后台最后启动的作业) |
| %+ | "当前"作业(前台最后结束的作业, 或后台最后启动的作业)|
| %- | 最后的作业|
| $! | 最后的后台进程 |

## 插入html表格格式
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>row 1, cell 1</td>
        <td>row 1, cell 2</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td bgcolor=#C0FF3E> row 2, cell 2</td>
    </tr>
</table>

## links
<table border="1">
    <tr>
        <th>学术网址</th>
        <th>科学院</th>
		<th>影音搜索</th>
    </tr>
    <tr>
        <td><a href="https://scholar.google.ca">谷歌学术, </a></td>
        <td><a href="http://www.whiob.ac.cn">WBG-植物园, </a></td>
		<td><a href="https://www.google.ca">谷歌搜索, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
    </tr>
    <tr>
        <td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
 		<td><a href="http://onestop.ucas.ac.cn">CAS-登陆, </a></td>
		<td><a href="https://www.youtube.com">YouTube, </a></td>
		
		<td><a href="http://onestop.ucas.ac.cn">CAS-登陆, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
		<td><a href="http://xueshu.baidu.com/">百度学术, </a></td>
    </tr>
</table>
