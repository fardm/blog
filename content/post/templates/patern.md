---
draft: true
---

## image

```
![](image)
```

تصویر هایپر لینک
```
[![name image](url image)](url link)
```


```
{{<figure src="/post/img/filename.jpg" width="80%" >}}
```



## link

```
[text]({{< ref "/folder" >}})
```


```
[text](/p/url localhost)
```


## Templater

```
<% tp.file.folder() %>
```

```
<% tp.file.title %>
```


## obsidian to hugo

```
python -m obsidian_to_hugo --obsidian-vault-dir=Publish --hugo-content-dir=C:\mysite\blog\content\post
```


```
python -m obsidian_to_hugo --obsidian-vault-dir=C:\Users\Arvin\OneDrive\Dokumenty\obsidian\Publish --hugo-content-dir=C:\mysite\blog\content\post
```
