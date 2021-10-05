# ColorPic
🎨 简单轻量的色图网站

# From
[solstice23](https://github.com/solstice23)
初始代码的创作者，我又改了一下awa

# 部署
1. 导入 `palettes.sql` 文件 
2. 在 `config.php` 中修改数据库信息

## Nginx 伪静态
```
rewrite /p/(.*?)/?$ /index.php?subdir&id=$1;
`
