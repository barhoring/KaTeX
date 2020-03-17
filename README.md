grab an elemant in https://katex.org/#demo the demo site
by adding id to it and using document.getElementById... 

and from the dev console 

```
katex.render("c = \\pm\\sqrt{a^2 + b^2}", element, {
    throwOnError: false
});
```
