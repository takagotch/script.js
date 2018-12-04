### script.js
---
https://github.com/ded/script.js

```
<script src="jquery.js"></script>
<script src="my-jquery-plugin.js"></script>
<script src="my-app-that-uses-plugin.js"></script>
```

```
$script('jquery.js', function(){
  $script('my-jquery-plugin.js', function(){
    $script('my-app-that-uses-plugin.js')
  })
})

$script(['jquery.js', 'my-jquery-plugin.js'], 'bundle')
$script('my-app-that-uses-plugin.js')'
$script.ready('bundle', function(){
})
$script.ready('bundle', function(){
})

$script('foo.js', function(){
})

$script(['foo.js', 'bar.js'], function(){
})
$script(['foo.js', 'bar.js'], 'bundle')
$script.ready('bundle', function(){
})

$script(['foo.js', 'bar.js'], 'bundle', function(){
})

$script('foo.js', 'foo')
$script('bar.js', 'bar')
$script
  .ready('foo', function(){
  })
  .ready('bar', function(){
  })
var dependencyList = {
  foo: 'foo.js'
, bar: 'bar.js'
, thunk: ['thunkor.js', 'thunky.js']
}

$script('foo.js', 'foo')
$script('bar.js', 'bar')

$script.ready(['foo', 'bar', 'thunk'], function(){
}, function(depsNotFound){
  depsNotFound.forEach(function(dep){
    $script(dependecyList[dep], dep)
  })
})
$script.ready('jquery', function(){
  $script.done('my-awesome-plugin')
})

$script('jquery.js', 'jquery')
$script('my-awesome-plugin.js')
$script.ready('my-awesome-plugin', function(){
})

$script.path('/js/modules/')
$script(['dom', 'event'], function(){
});

$script.path('/js/modules/')
$script(['dom', 'event'], function(){
})
$script.get('http://example.com/base.js', function(){
})

$script.urlArgs('key=value&foo=bar');

$.reuire(...)

var $$ = require('scriptjs')
$$('/foo.js', function(){
})
```

```
npm install -dev
make
ender add scriptjs
```


