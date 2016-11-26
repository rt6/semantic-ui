# SEMANTIC-UI
tip and tricks

### Setup using CDN
```html
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/semantic-ui/2.2.6/semantic.min.css">
    <script
              src="https://code.jquery.com/jquery-3.1.1.slim.min.js"
              integrity="sha256-/SIrNqv8h6QGKDuNoLGA4iret+kyesCkHGzVUUV0shc="
              crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/semantic-ui/2.2.6/semantic.min.js"></script>
</head>
```

### Center on page using grids (responsive)
note each row has max 16 columns

```html
<div class="ui stackable page grid">
    <div class="left aligned column four wide">
        <div class="ui card">hello 1</div>
    </div>
    <div class="center aligned column four wide">
        <div class="ui card">hello 2</div>
    </div>
    <div class="right aligned column four wide">
        <div class="ui card">hello 3</div>
    </div>
    <div class="right aligned column four wide">
        <div class="ui card">hello 4</div>
    </div>
</div>
```
