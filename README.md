# &lt;instant-button&gt;

## Install
```
bower install instant-button [--save]
```

## Include
```html
<!-- Web Components polyfills -->
<script src="//cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.5.2/webcomponents-lite.min.js"></script>

<!-- fix-me and to-do elements -->
<link rel="import" href="bower_components/instant-button/instant-button.html" />
```

## Use
```html
<!-- random color -->
<instant-button></instant-button>
<instant-button color="random"></instant-button>

<!-- specified color -->
<instant-button color="#faf"></instant-button>
<instant-button color="gold"></instant-button>

<!-- sound file url -->
<instant-button src="sound.ogg"></instant-button>

<!-- multiple formats, pick the best one -->
<instant-button src="sound.{ogg,mp3}"></instant-button>
```


## Example
http://ondras.github.io/instant-button/


## Awesome!
Built with love (and caribbean rum) by [Ondřej Žára](http://ondras.zarovi.cz/)
