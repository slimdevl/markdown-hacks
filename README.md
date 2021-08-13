
<p><img src="https://api.timeforkids.com/wp-content/uploads/2020/02/feature-cover_-train-k1.jpg" alt="foo bar" title="train &amp; tracks" /></p>


## Links Fun
<p><a href="/url" title="title">foo</a></p>

[foo][bar]

[bar]: /url "title"


[link [foo [bar]]][ref]

[ref]: /uri


<p><a href="/uri">link [foo [bar]]</a></p>


[Толпой][Толпой] is a Russian word.

[ТОЛПОЙ]: /url




# markdown-hacks



<ol>
<li>
<p>A paragraph
with two lines.</p>
<pre><code>indented code
</code></pre>
<blockquote>
<p>A block quote.</p>
</blockquote>
</li>
</ol>

### Dividers
***
---
___

## Cool way to make attention 

<del>
  *foo*
</del>


<blockquote>
<h1>Foo</h1>
<p>bar
baz</p>
</blockquote>

## Pointless Code Block section
<del>
*Markdown*
</del>

<pre language="haskell"><code>
import Text.HTML.TagSoup

main :: IO ()
main = print $ parseTags tags
</code></pre>
<p>okay</p>

## Table Of Contents
<div class="toc">
  <ul>
    <li><a href="#a-collapsible-section-containing-code">A collapsible section containing code</a></li>
      <ul>
        <li><a href="#header-2">Header 2</a></li>
      </ul>
  </ul>
</div>
<h1 id="header-1">Header 1</h1>
<h2 id="header-2">Header 2</h2>



# Another Table of Contents
1. [A collapsible section containing code](#a-collapsible-section-containing-code)
2. [Introduction](#introduction)
3. [Some paragraph](#paragraph1)
    1. [Sub paragraph](#subparagraph1)
4. [Another paragraph](#paragraph2)

## Content

**[1. Markdown](#heading--1)**

  * [1.1. Markdown formatting cheatsheet](#heading--1-1)
  * [1.2. Markdown formatting details](#heading--1-2)

**[2. BBCode formatting](#heading--2)**

  * [2.1. Basic text formatting](#heading--2-1)

      * [2.1.1. Not so basic text formatting](#heading--2-1-1)

  * [2.2. Lists, Images, Code](#heading--2-2)
  * [2.3. Special features](#heading--2-3)

----


Block Quote:
> I’ve always been more interested
> in the future than in the past.


First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

```javascript
function test() {
 console.log("look ma’, no spaces");
}
```

## Funky Tables
<table><tr><td>
<pre>
**Hello**,

_world_.
</pre>
</td></tr></table>

@@ ANother
<table><tr><td>
<pre>
**Hello**,
<p><em>world</em>.
</pre></p>
</td></tr></table>



# Check lists
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)


GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: 

#1
github-flavored-markdown#1
defunkt/github-flavored-markdown#1

# A collapsible section containing code

<details>
<summary>I could use some help...</summary>
<p>

```c#
public class Order
{
    public int OrderId { get; set; }
    public int CustomerId { get; set; }

    public List<int> Products { get; set; }
}
```

</p>
</details>  


## This is the introduction <a name="introduction"></a>
Some introduction text, formatted in heading 2 style

## Some paragraph <a name="paragraph1"></a>
The first paragraph text

### Sub paragraph <a name="subparagraph1"></a>
This is a sub paragraph, formatted in heading 3 style

## Another paragraph <a name="paragraph2"></a>
The second paragraph text
