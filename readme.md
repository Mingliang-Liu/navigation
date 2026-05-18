# 导航网站

## demo网站
https://navigation-liumingliang.readthedocs.io

https://raw.githack.com/Mingliang-Liu/navigation/refs/heads/main/navigation_html/index.html

## 📊 Star 趋势
[![Star History Chart](https://api.star-history.com/chart?repos=Mingliang-Liu/navigation&type=date&legend=bottom-right)](https://www.star-history.com/?repos=Mingliang-Liu%2Fnavigation&type=date&legend=bottom-right)

## 新建github仓库
新建navigation的公开仓库
.gitignore选Python
LICENSE选GPLv3
不初始化readme.md
```
git clone https://github.com/Mingliang-Liu/navigation.git
```

## 下载xg-nav模板
```
mkdir -p navigation_html

git clone https://github.com/verkyer/xg-nav.git navigation_html/

cd navigation_html

rm -rf demo.png docker-compose.yml Dockerfile .dockerignore entrypoint.sh .git .github/ .gitignore nginx.conf README.md

cd ..
```
## 接下来步骤
1. 新建.readthedocs.yaml
2. 注释.gitignore的lib/
3. 修改navigation_html/data/links.yaml 改为自定义的导航
4. 修改navigation_html/config.json navigation_html/assets/search 改为自定义的搜索


## 强制刷洗RTD CDN缓存

浏览器：

```text
Ctrl + Shift + R
```

macOS：

```text
Cmd + Shift + R
```

