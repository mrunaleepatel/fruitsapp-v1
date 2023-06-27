## Static File Serving

```
app.use(express.static("folderName"))
```
url is xyz.com

|file|url|
|----|---|
|public/index.html|xyz.com/|
|public/cheese.html|xyz.com/cheese.html|
|public/style.css|xyz.com/style.css|
|public/css/style.css|xyz.com/css/style.css|

### Urlcoded

```
?name=dragonfruit&color=pink&readyToEat=on
```

### JSON

```
{"name": "dragonfruit",
"color": "pink",
"readyToEat": "on"}

```

### XML

```


```