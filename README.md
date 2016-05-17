![hexo-theme-kae](http://i12.tietuku.com/ad8d1df7702a0a53s.png)

## 安装

``` bash
hexo init Blog
cd Blog
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync
git clone https://github.com/simpkae/hexo-themes-kae.git themes/kae
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `kae`:

```yaml
theme: kae
```

## 更新

``` bash
cd themes/kae
git pull
```

## 自定义块

Markdown 生成的标签暂时比较简单，所以提供了一些 HTML 标签来标识特殊样式，详见 [custrom-blocks](https://github.com/SimpKae/hexo-themes-kae/blob/master/doc/custom-blocks.md)。

## License

MIT
