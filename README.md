check [this post](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) about Flexbox layout

```
body {
  background-color: #1F1E34;
  color: #FFF;
  font-family: "Avenir Next",
      "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica,
      Arial, "Lucida Grande", sans-serif;
  font-weight: 100;
}

h1 {
  font-size: 64px;
  font-weight: 100;
}

h2 {
  font-size: 48px;
  font-weight: 100;
}

p {
  font-size: 24px;
}

a {
  font-weight: 400;
  color: #FFF;
}

a:hover {
  font-weight: 400;
  color: #DADADA;
  text-decoration: none;
}
```
especially the font, it is so beautiful!

These units are vh (viewport height), vw (viewport width), vmin (viewport minimum length) and vmax (viewport maximum length).

## flex

在使用 ReactNative 时你会经常看到一个神秘的设定 flex: 1，用了来扩大一个 flexbox。flex 是一个简写，同时设置 flex-grow，flex-shrink 和 flex-basis 三个属性。它们的默认值为：

 ```
flex: 0 1 auto;
/*
flex-grow: 0;
flex-shrink: 1;
flex-basis: auto;
*/
```

flex: 1 意为 flex: 1 1 auto






















