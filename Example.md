# Markdown examples

-----

# h1

## h2

### h3

-----

### Text Style

normal

*italics*
_italics_

**bold**
__bold__

~~Strikethrough.~~

-----

### table

|Col 1   |Col2   |Col3   |
|:---|:---:|---:|
|val leftalign|val center align|val right align|

### unordered list
* a 
* b
* c

- a
- b
- c

+ a
+ b
+ c

### ordered list
1. a
1. b
1. c


### nested list
1. a
   * nested item 1
     * nested item 2
1. b
1. c
-----

### code

```php

var php
echo $foo

```

### image

![alt text goes here](http://unsplash.it/250/250?random "A NON OBLIGATORY TOOLTIP!")

-----

### image with reference

![alt text goes here][imgRef]

[imgRef]: http://unsplash.it/250/250?random

-----

### image with link

[![alt text goes here](http://unsplash.it/250/250?random)](http://google.com)

### smaller image linking to bigger image

[![alt text goes here](http://unsplash.it/250/250?random)](http://unsplash.it/500/500?random)

#### with html

[<img src="http://unsplash.it/250/250?random">](http://unsplash.it/500/500?random)

#### with html + css

[<img src="http://unsplash.it/250/250?random" class="testMarkdownImg">](http://unsplash.it/500/500?random)

<style>
  .testMarkdownImg {
    width : 500px;
    height: 500px;
  }
</style>

### links

<http://www.google.com>

[Google dot com](http://www.google.com "A NON OBLIGATORY TOOLTIP!")

[Google dot com with reference 1][1]
[Google dot com with reference text][some_ref_text]


[1]: http://www.google.com
[some_ref_text]: http://google.com


### block quotes

> Some quote goes here - WhoeverSaidThis


> Some other quote goes here 
>   --- **AnotherPersonSaidThis**
>   

### checkboxes

* [ ] item 1
* [x] item 2
* [x] item 3
