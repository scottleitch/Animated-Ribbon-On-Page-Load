# Animating Ribbon On Page Load

Pretty self explanatory. Page loads, ribbon animates into view.

Modifying

```
$('.ribbon').on('load', function() {
```

to

```
$('.ribbon').on('click', function() {
```

will change the event from onLoad to onClick.
