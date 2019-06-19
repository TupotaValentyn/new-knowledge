# new-knowledge
I create this repo to summarize my new knowledge over the summer


## POST CSS

### @[custome selector]

```pcss
@custom-selector :--heading h1, h2, h3;

article :--heading + p {
  margin-top: 0;
}

/* becomes */

article h1 + p, article h2 + p, article h3 + p {}
```




[custome selector]: https://github.com/postcss/postcss-custom-selectors



### [color short]

```pcss
/* before */

.hello {
  border-bottom: 1px solid rgb(200);
  background: #20;
  color: #f;
  box-shadow: 0 1px 5px rgba(0, 0.5);
}

/* after */

.hello {
  border-bottom: 1px solid rgb(200, 200, 200);
  background: #202020;
  color: #fff;
  box-shadow: 0 1px 5px rgba(0, 0, 0, 0.5);
}
```

[color short]: https://github.com/andrepolischuk/postcss-color-short


### [focus]

```pcss
*:focus {
    outline: 0;
}
.button:hover {
    background: red;
}
```
```pcss
*:focus {
    outline: 0;
}
.button:hover, .button:focus {
    background: red;
}
```

