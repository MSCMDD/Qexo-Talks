# Qexo_Stellar_Talks
Qexo说说功能适配Stellar Theme
Qexo 静态文件

## 引入方法
在所需页面的markdown中或ejs模版中添加
```
<div id="qexot" class="tag-plugin timeline"></div>
<script src="https://gcore.jsdelivr.net/gh/MSCMDD/Qexo-Talks@main/Stellar/qexo_talk.js"></script>
<link rel="stylesheet" href="https://gcore.jsdelivr.net/gh/MSCMDD/Qexo-Talks@main/Stellar/qexo_talk.css">
<script>showQexoTalks("qexot", "${SITE}", 5)</script>
```
将其中的 ${SITE} 改为你的 Qexo 链接 例如 https://admin.mysite.com
>Tips: 第三个参数为每页的说说数量, 可结合实际进行修改

示例网站：[留言板 - M&A互助联盟](https://mscmdd.github.io/contact/)
