## CSS

### [css counter]

``` css 
ol {
  counter-reset: section;           /* create new counter for each <ol> tag */
  list-style-type: none;
}

li::before {
  counter-increment: section;      
  content: counters(section,".") " ";
}
```

[css counter]: https://developer.mozilla.org/ru/docs/Web/CSS/CSS_Lists_and_Counters/Using_CSS_counters
