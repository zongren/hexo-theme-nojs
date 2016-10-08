## nojs
Hexo theme without any javascript codes or files.

## Add tag page
Excute `hexo new page tags`,and set layout to tags,and uncomment `tags` in `theme config`.

## Add category page
Excute `hexo new page categories`,and set layout to categories,and uncomment `categories` in `theme config`.

## Add archive page
Archive page shows all dates monthly.Excute `hexo new page archive`,and set layout to archives,and uncomment `archive` in `theme config`.

## Add archives page
Archives page show all posts.Uncomment `archives` in `theme config`.

## Add search page 
Search page requires [`Algolia`](https://www.algolia.com) or [`Tapir`](https://www.tapirgo.com)
### Use `algolia`
Uncomment following code to `theme.config` file
```
# algolia:
#   appId: "{replace with your Application ID}"
#   apiKey: "{replace with your Search-Only API Key}"
#   indexName: "{replace with your index name}"
```
### Use `tapir`
Uncomment following code to `theme.config` file
```
# tapir_token: "{replace with your token}"
```

## Enable duoshuo
Uncomment following code in 'theme.config' file
```
# duoshuo: 
```

## Enable disqus
Uncomment following code in 'theme.config' file
```
# disqus: 
```

## Change highlight theme
Edit `nojs/_config.yml`
```
highlight_theme: theme_name
```
theme_name can be found at `nojs/source/css/_highlight/`.