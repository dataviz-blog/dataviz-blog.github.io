---
published: true
title: 6 — Markdown Cheat Sheet
layout: post
---
TinyPress.co uses Markdown to format its blog posts.

Markdown is a simple way of adding a little 'punctuation' or syntax to your writing to add some font styling and some links and the like to your writing.

Below is a list of the main pieces of Markdown you'd want to use.

---

# Text things

<pre lang="no-highlight"><code>
# Giant heading
## Smaller heading
### And even smaler heading
</code></pre>
etc.


# Giant heading

## Smaller heading

### And even smaler heading


<pre lang="no-highlight"><code>
**bold** 
_italics_
</code></pre>

**bold** 

_italics_


<pre lang="no-highlight"><code>
1. ordered list
1. ordered list
  2. another item
</code></pre>

1. ordered list
1. ordered list
  2. another item

<pre lang="no-highlight"><code>
* unordered list
* unordered list
  * another item
</code></pre>

* unordered list
* unordered list
  * another item



# Code things

<pre lang="no-highlight"><code>
```
This is a block of code.
```
</code></pre>

```
This is a block of code
```


# Links things

## ..to a page

<pre lang="no-highlight"><code>
Click here for the more complete [cheet sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) we stole these points from.
</code></pre>

Click here for the more complete [cheet sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) we stole these points from.

## ..to an image

<pre lang="no-highlight"><code>
![clickable text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
</code></pre>

![clickable text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

# Tables

<pre lang="no-highlight"><code>
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
</code></pre>

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

# Pretty horizontal lines

<pre lang="no-highlight"><code>
---
</code></pre>
---