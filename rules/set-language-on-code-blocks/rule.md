---
type: rule
archivedreason:
title: Markdown – Do you set the language on code blocks?
guid: 1f4e6b03-d6d3-45ca-9a8f-9595f3ff5fd5
uri: set-language-on-code-blocks
created: 2021-03-23T00:01:00.0000000Z
authors:
- title: Adam Cogan
  url: https://ssw.com.au/people/adam-cogan
related:

---

You should have a syntax highlighter to show pieces of code on your pages for a better readability.

Examples:
- [Prism](https://prismjs.com)
- [highlight.js](https://highlightjs.org)

<!--endintro-->

::: info
See this [json file](https://unpkg.com/gatsby-remark-vscode@1.0.3/lib/grammars/manifest.json) for all supported languages and their aliases we can use in SSW Rules.
:::


```
let iceCream = 'chocolate';
if(iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');    
} else {
  alert('Awwww, but chocolate is my favorite...');    
}
```
::: bad  
Figure: Bad example - No syntax highlighting
:::  

```javascript
let iceCream = 'chocolate';
if(iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');    
} else {
  alert('Awwww, but chocolate is my favorite...');    
}
```
::: good
Figure: Good example - This JavaScript code block shows its syntax highlighted
:::

::: codeauditor
[SSW CodeAuditor enforces this rule](https://codeauditor.com/rules).
:::
