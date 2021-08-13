# markdown-hacks

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
