# new-knowledge
I create this repo to summarize my new knowledge over the summer


## CSS

### @custome selectors

```pcss
@custom-selector :--heading h1, h2, h3;

article :--heading + p {
  margin-top: 0;
}

/* becomes */

article h1 + p, article h2 + p, article h3 + p {}
```
