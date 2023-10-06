---
layout: default
---

Welcome to the Princeton Alg-ML Seminar Page! Alg-ML is a weekly ML theory seminar primarily attended by the research groups of Prof. Sanjeev Arora, Prof. Elad Hazan, Prof. Jason Lee, and Prof. Chi Jin. 
We discuss exciting recent advancements in the areas of algorithm design and theoretical machine learning. 

Talks are held every Monday from 12:30 pm ET to 1:30 pm ET, with food usually served at 12:15 pm ET. It is open to all members of the Princeton community. 

For the 2023-2024 academic year, this seminar is organized by Simran Kaur, Eshaan Nichani, and Jennifer Sun.

<ul id="namesList">
    <li>Simran Kaur</li>
    <li>Eshaan Nichani</li>
    <li>Jennifer Sun</li>
</ul>

<script>
document.addEventListener("DOMContentLoaded", function() {
    var ul = document.getElementById("namesList");
    var liArray = Array.from(ul.children);

    var shuffledArray = liArray.sort(function() {
        return 0.5 - Math.random();
    });

    // Clear the list
    ul.innerHTML = "";

    // Append shuffled items back to the list
    shuffledArray.forEach(function(li) {
        ul.appendChild(li);
    });
});
</script>

If you would like to be notified about future Alg-ML talks, please subscribe to the alg-ml mailing list and google calendar.

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
