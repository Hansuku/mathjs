---
layout: default
---

<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

<h1 id="function-column">Function column <a href="#function-column" title="Permalink">#</a></h1>

Return column in Matrix.


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
math.column(value, index)    // retrieve a column
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`value` | Array &#124; Matrix | An array or matrix
`column` | number | The index of the column

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
Array &#124; Matrix | The retrieved column


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
// get a column
const d = [[1, 2], [3, 4]]
math.column(d, 1))        // returns [2, 4]
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[row](row.html)