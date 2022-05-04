# novels_grab

爬取笔趣阁小说，存为TXT文件
one.py为抓取单部小说
main.py为抓取小说总排行榜前两页所有小说
ex.py为测试程序
main.py存在响应超时问题，尚未解决

## 安装

1. 安装[chromedriver](https://chromedriver.chromium.org/downloads)，包管理器和手动下载皆可
1. 安装chrome

## 使用

1. 打开`https://www.bbiquge.net/`
1. 找到想要下载的书籍主页
1. 拷贝链接到`one.py`的28行，替换`get_toc("the url")`中的`the url`
1. 执行`python one.py`即可下载

## update

### 注释one.py

注释17~27行，在下载前找好链接，因为在搜索准确小说名称时会自动跳转到小说主页，不用搜索。

### 依赖项安装

add `requirements.txt`

```bash
pip install -r requirements.txt
```
