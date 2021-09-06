##### 安装Scrapy
```
pip3 install Scrapy
```
##### Scrapy创建项目
```
scrapy startproject ArticleSpider
```
##### 初始化项目
```
cd ArticleSpider
scrapy genspider example example.com
# example 名称
# example.com 域名
# scrapy genspider jobbole news.cnblogs.com
```