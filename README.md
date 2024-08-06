# Browser Dark Mode Shortcut
Convert existing website to dark mode with quick css injection

## Just 2 lines of CSS

```css
html{filter: invert(100%) hue-rotate(180deg);}
img{filter: invert(100%) hue-rotate(180deg);}
```

## And you can inject it in many ways

### JavaScript Console
```js
var style = document.createElement('style');
style.innerHTML = 'html{filter: invert(100%) hue-rotate(180deg);} img{filter: invert(100%) hue-rotate(180deg);}';
document.head.appendChild(style);
```

### CSS Inspector
> Just open your browser, inspect the page, add above css rules

### Tool
> Find some CSS injection extension for your browser and use the css


_todo: add other examples_
