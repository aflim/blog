---
layout: page
title: Styleguide
---

## Paragraph
Vivamus sagittis lacus vel augue rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.

## Heading
Limit heading to three level
# Heading level 1
## Heading level 2
### Heading level 3

## Unordered list
- First list item
- Second list item
- Third list item

## Ordered list
1. First list item
2. Second list item
3. Third list item

## Definition list
<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>The language used to describe and define the content of a Web page</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Used to describe the appearance of Web content</dd>

  <dt>JavaScript (JS)</dt>
  <dd>The programming language used to build advanced Web sites and applications</dd>
</dl>

## Horizontal rule
<hr>

## Text formatting
- *Italic text* use `<em>`
- **Bold text** use `<strong>`
- ~~Deleted text~~ use `<del>`
- <mark>Highligh text</mark> use `<mark>`
- Inline code like `<!doctype html>` use `<code>`
- <cite>Citing</cite> use `<cite>`
- Abbreviation like <abbr>html</abbr> use `<abbr>`

## Blockquote
<figure>
  <blockquote cite="https://www.huxley.net/bnw/four.html">
    <p>Words can be like X-rays, if you use them properly—they’ll go through anything. You read and you’re pierced.</p>
  </blockquote>
  <figcaption>—Aldous Huxley, <cite>Brave New World</cite></figcaption>
</figure>

Someone said:
<figure>
  <blockquote cite="https://datatracker.ietf.org/doc/html/rfc1149">
    <p>
    Avian carriers can provide high delay, low throughput, and low altitude
    service. 
    </p>
    <p>
    The connection topology is limited to a single point-to-point path
    for each carrier, used with standard carriers, but many carriers can be used
    without significant interference with each other, outside early spring.
    This is because of the 3D ether space available to the carriers, in contrast
    to the 1D ether used by IEEE802.3.
    </p>
    <p>
    The carriers have an intrinsic collision
    avoidance system, which increases availability.
    </p>
  </blockquote>
</figure>

## Table
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

## Image
<figure>
  <img src="https://picsum.photos/500/500" width="500" height="500" alt="placeholder image 500×500">
</figure>

<figure>
  <img src="https://picsum.photos/400/300" width="400" height="300" alt="placeholder image 400×300">
  <figcaption>Placeholder image 400×300</figcaption>
</figure>

## Embedded video with iframe
<figure>
  <iframe src="https://www.youtube.com/embed/kdXfrMObAlA" width="720" height="480" frameborder="0" allowfullscreen style="aspect-ratio: 16/9;">
  </iframe>
</figure>

<figure>
  <iframe src="https://www.youtube.com/embed/kdXfrMObAlA" width="720" height="480" frameborder="0" allowfullscreen style="aspect-ratio: 16/9;">
  </iframe>
  <figcaption>With caption</figcaption>
</figure>

## Code snippets via rouge
{% highlight js %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

You may also optionally show code snippets with line numbers. Add `linenos` to the Rouge tags.

{% highlight js linenos %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

with <code>```</code>
```js
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
```

```js lineos
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
```


