title: about
date: 2016-07-13 22:28:32
subtitle: "simple responsive and beautiful"
---
Beautiful-hexo is a simple elegant hexo theme ported from [Beautiful-jekyll](http://deanattali.com/beautiful-jekyll) which written by [Dean Attali](http://deanattali.com/aboutme). Nice work!

![hexo-preview](/beautiful-hexo/assets/image/hexo-preview.png)

### Install

```
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-generator-archive hexo-renderer-jade hexo-generator-tag hexo-generator-feed hexo-generator-sitemap hexo-browsersync 
git clone --depth 1 git@github.com:twoyao/beautiful-hexo.git themes/beautiful-hexo
```


Modify `_config.yml` change `theme` to `beautiful-hexo` and configure hexo-generator-archive :

```
theme: beautiful-hexo

archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

Theme config file is brief and clear. 
If you have any question, check [hexo online document](https://hexo.io/).