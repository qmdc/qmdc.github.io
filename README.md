# qmdc.github.io

> 博客框架：[hugo](https://gohugo.io/)

> 博客主题：[Manis](https://github.com/yursan9/manis-hugo-theme) 

## hugo常用命令

```shell
1. `hugo new <post-name>`：创建新的文章或页面。例如：`hugo new blog/my-new-post.md`。

2. `hugo server`：启动本地服务器，用于预览网站。默认情况下，服务器将在`http://localhost:1313/`上运行。

3. `hugo server -D`：启动本地服务器，并包括未发布的草稿文章。

4. `hugo`：生成静态网站文件。默认情况下，生成的文件将存储在`public/`目录中。

5. `hugo version`：查看安装的Hugo版本。
```


## 自定义简码

> 替代 Mardown 默认的引用样式
```javascript
{{< quote >}}
十里青山远，潮平路带沙。数声啼鸟怨年华。
{{< /quote >}}
```
![](https://cdn.jsdelivr.net/gh/qmdc/oss@master/202308/8dDUbr.png)

> 设定文字的位置（居左、居中、居右、两端对齐等）
```javascript
{{< align right "疏影横斜" >}}
```
![](https://cdn.jsdelivr.net/gh/qmdc/oss@master/202308/dr2kH5.png)

> 设置文字各段落首行缩进
```javascript
{{<indent>}}
春江潮水连海平
海上明月共潮生
{{</indent>}}
```
![](https://cdn.jsdelivr.net/gh/qmdc/oss@master/202308/bWc0qi.png)

> 自定义html代码区域
```javascript
{{<html>}}
    <table class="custom-table">
        <tr>
            <th>
                <a href="https://github.com/qmdc/qmdc">
                    <img align="center" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=qmdc&show_icons=true&include_all_commits=true&theme=buefy&hide_border=true" alt="qmdc's github stats" />
                </a>
            </th>
            <th>
                <a href="https://github.com/qmdc/qmdc">
                    <img align="center" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=qmdc&layout=compact&theme=buefy&hide_border=true" />
                </a>
            </th>
        </tr>
    </table>
    <style>
        .custom-table {
        border-collapse: collapse;
    }
        .custom-table th, .custom-table td {
        border: 1px solid #ececec;
        padding: 8px;
    }
    </style>
{{</html>}}
```
![](https://cdn.jsdelivr.net/gh/qmdc/oss@master/202308/cyXSWA.png)



