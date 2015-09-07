## TangScan job interview

### Python 研发工程师

#### 简单介绍:
使用 python 编写一个网站爬虫项目, 至少支持以下配置:

```
url: 进行爬取的 url 
headers: 每次请求附带的 header
depth: 爬取的深度
delay: 每次请求间隔时间
priority: 深度优先还是广度优先
limit: 最多爬取多少个页面
keyword: 只存储带有 keyword 的页面
logfile: 日志存储路径
loglevel: 日志级别
```

#### 功能要求:
1. 指定某网站爬取指定深度的页面
2. 可以指定 headers 进行爬取
3. 可以指定每次请求间隔时间
4. 可以指定深度或者广度优先
5. 如果没有 keyword, 那就存储所有页面
6. 将结果存储至 mysql
7. 使用命令行或者配置文件进行配置

#### 项目要求:
0. 请遵守 pep8 规范
1. 请使用 gevent, tornado, asyncio, twisted 等任一网络框架
2. 请使用 git-flow 工作流
3. 请使用 sphinx , 并在 rtfd.org 上生成文档
4. 请使用 doctest, unittest 等任一单元测试框架
5. 建议使用 cookiecutter 生成项目(非强制要求)
