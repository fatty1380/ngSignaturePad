ngSignaturePad
===

SignaturePad as an angularJS directive

Install
===

The install process is a little more manual right now...

```bash
bower install -S signature_pad
bower install https://raw.github.com/marcorinck/ngSignaturePad/master/ngSignaturePad.js

pushd app/bower_components/ngSignaturePad
wget https://raw.github.com/marcorinck/ngSignaturePad/master/ngSignaturePad.min.css
popd
```
    
Include the script tags

```html
<link rel="stylesheet" href="bower_components/ngSignaturePad/ngSignaturePad.min.css"></script>
<script src="bower_components/signature_pad/signature_pad.js"></script>
<script src="bower_components/ngSignaturePad/index.js"></script>
```

Use the directive somewhere in your html as an *attribute*

```html
<div signature-pad></div>
```

Then add the module to your list of angular dependencies as `ngSignaturePad`

```
angular.module('myDemoApp', [
    'ngCookies'
  , 'ngResource'
  , 'ngSanitize'
  , 'ui.bootstrap'
  , 'ui.router'
  , 'ngSignaturePad'
  ])
```
