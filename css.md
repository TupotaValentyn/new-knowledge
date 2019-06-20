## CSS

### [css counter]

``` css 
ol {
  counter-reset: section;           /* create new counter for each <ol> tag 
                                      тега <ol>*/
  list-style-type: none;
}

li::before {
  counter-increment: section;      
  content: counters(section,".") " ";
}
```
