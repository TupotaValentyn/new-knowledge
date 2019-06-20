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


### [isolation]
#### [CodePen]

``` css 
  .module {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  isolation: isolate;
}
```

![text](https://css-tricks.com/wp-content/uploads/2015/07/isolate-1024x870.png)

[isolation]: https://css-tricks.com/almanac/properties/i/isolation/
[CodePen]: https://codepen.io/SitePoint/pen/GJjobw
