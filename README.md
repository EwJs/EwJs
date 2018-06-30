# EwJs
Tiny JavaScript framework for building UI on the web. (Being coding,Soon)

#### Get a element
```
$("h1");
$.query("h1");
```

#### Get all elements as array
```
$.querys("li");
```

#### Get HTML-Content HTML Value
```
$("h1").html();
-------------------
var h=$("h1");
alert ( h.html() );
```


#### Change HTML-Content
```
var h=$("h1");
h.html("New Value");
--------------------
h.html( h.html() + " ==> New Value");//like append
```


#### Append to HTML-Content
```
var h=$("h1");
h.append("!!!!");
```

#### Append Child to a element
```
```

#### Get all childrens 
```
var ul=$("ul");
var items=ul.childrens();
```
#### Get Length of childrens/array
```
var ul=$("ul");
var items=ul.childrens();
var count=items.length()
```

