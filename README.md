## NoJS
Hexo theme without any javascript codes or files.

## Add tag page
Execjte `hexo new page tags`,and set layout to `tags`,and uncomment the following code in `theme config`.
```
menu
#   - tag: 
#     url: 'tags'
#     title: 'tag'
#     icon: 'tag'
```

## Add category page
Execjte `hexo new page categories`,and set layout to `categories`,and uncomment the following code in `theme config`.
```
menu
#   - category: 
#     url: 'categories'
#     title: 'category'
#     icon: 'category'
```

## Add date page
Date page shows all dates monthly.Execjte `hexo new page date`,and set layout to `date`,and uncomment the following code in `theme config`.
```
menu
#   - date: 
#     url: 'date'
#     title: 'date'
#     icon: 'date'
```

## Add archives page
Archives page show all posts.Uncomment the following code in `theme config`.
```
menu
#   - archive: 
#     url: 'archives'
#     title: 'archive'
#     icon: 'archive'
```

## Add search page 
Search page requires [`Algolia`](https://www.algolia.com).Execute `hexo new page search` and set layout to `search`.Uncomment following code to `theme.config` file
```
# algolia:
#   appId: "{replace with your Application ID}"
#   apiKey: "{replace with your Search-Only API Key}"
#   indexName: "{replace with your index name}"
```

## Enable comment
NoJS supports staticman,first uncomment `# staticman:` in `theme config`.