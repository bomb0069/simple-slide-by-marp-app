---
marp: true
paginate: true
---

# H1 Simple Slide

a little content about this slide

---

## H2 Slide - without page no

a little content about this slide

<!-- paginate: false-->

---

## Slide in `invert` class

a little content about this slide

<!-- _class: invert-->

```markdown
<!-- _class: invert-->
```

---

## Text Style - Asterisk Emphasis with **Bold** and *Italic*

a little **bold** and *italic* style

```markdown
## Text Style - Asterisk Emphasis with **Bold** and *Italic*

a little **bold** and *italic* style
```

---

## Text Style - Underscore Emphasis with __Bold__ and _Italic_

a little __bold__ and _italic_ style

```markdown
## Text Style - Asterisk Emphasis with **Bold** and *Italic*

a little __bold__ and _italic_ style
```

---

## More Styles

```mardown
- ~~Strikethrough~~
- `Inline code`
```

- ~~Strikethrough~~
- `Inline code`

---

## Quotes

> The best way to predict the future is to invent it
-- Alan Kay

---

## Table

```markdown
| Header 1 | Header 2 | Header 3 |
| --- | --- | --- |
| Cell 1 | Cell 2 | Cell 3 |
| Cell 4 | Cell 5 | Cell 6 |
```

| Header 1 | Header 2 | Header 3 |
| --- | --- | --- |
| Cell 1 | Cell 2 | Cell 3 |
| Cell 4 | Cell 5 | Cell 6 |

---

## Table - Text Alignment

With :---: and ---: you can center or right align the cell content.

```markdown
|   Header 1  |    Header 2   |   Header 3   |
| ----------- | :-----------: | -----------: |
| Cell        |    _Cell_     |    *Cell*    |
| Cell        |   **Cell**    |   __Cell__   |
```

|   Header 1  |    Header 2   |   Header 3   |
| ----------- | :-----------: | -----------: |
| Cell        |    _Cell_     |    *Cell*    |
| Cell        |   **Cell**    |   __Cell__   |

---

## Emoji

Deckset supports emojis! :umbrella: :sunflower: :cat: :smile: :thumbsup:

---

## Directives

These are the setting value per slide pages.

- paginate: Show pagination by set true
- header: Specify the contents for header
- footer: Specify the contents for footer
- class: Set HTML class for current slide
- color: Set text color
- backgroundColor: Set background color

---

## Sample page with Text Content

`Test-driven development (TDD)` is a development technique where you must first write a test that fails before you write new functional code. TDD is being quickly adopted by agile software developers for development of application source code and is even being adopted by Agile DBAs for database development.

---

## Bullet List

```markdown
- What is TDD?
- TDD and traditional testing
- TDD and documentation
```

- What is TDD?
- TDD and traditional testing
- TDD and documentation

---

## Fragmented list

Marp will parse a list with asterisk marker as the fragmented list for appearing contents one by one. (Only for exported HTML by Marp CLI / Marp for VS Code)

```markdown
* One 
* Two
* Three

#MD004/ul-style in mardownlint
```

* One
* Two
* Three

---

## Ordered List

```mardown
1. Why TDD?
2. Myths and misconceptions
3. Who is actually doing this?
```

1. Why TDD?
2. Myths and misconceptions
3. Who is actually doing this?

---

## Fragmented Ordered List

```mardown
1) Why TDD?
2) Myths and misconceptions
3) Who is actually doing this?
```

1) Why TDD?
2) Myths and misconceptions
3) Who is actually doing this?

---

<!-- backgroundColor: aqua -->
<!-- backgroundImage: none -->

## After This page has aqua background

```sh
<!-- backgroundColor: aqua -->
<!-- backgroundImage: none -->
```

---

## This is Second Page of aqua background

---

<!--
backgroundImage: url('./images/car/car4.jpeg') 
color: white
-->

## After This Page is Background Image

```html
<!-- 
backgroundImage: url('./images/car/car1.jpeg') 
color: white
-->
```

---

<!-- _backgroundColor: aqua -->
<!-- _backgroundImage: none -->

## Only This page has aqua background

Local directives are the setting value per slide pages. These would apply to defined page and following pages.

If you want to apply local directives only to current page, you have to use prefix _ to the name of directives.

```html
<!-- _backgroundColor: aqua -->
<!-- _backgroundImage: none -->
```

---

## Change back to default BG Image

---

<!--
backgroundImage: none
backgroundColor: none
color: none
-->

## Disable Background Image

```html
<!-- 
backgroundImage: none
backgroundColor: none
color: none
-->
```

---

## Insert Image

- Default Image

![Logo](./images/logo.png)

```markdown
![Logo](./images/logo.png)
```

---

## Resize Image with 100 * 100 px

![width:100px height:100px](./images/logo.png)

```markdown
![width:100px height:100px](./images/logo.png)
```

---

## Blur Image

![blur](./images/logo.png)

```mardown
![blur](./images/logo.png)
```

---

## Sepia 50% Image

![sepia:50%](./images/logo.png)

```mardown
![sepia:50%](./images/logo.png)
```

---

## Blur and Sepia 50% Image

![blur sepia:50%](./images/logo.png)

```mardown
![blur sepia:50%](./images/logo.png)
```

---

## Background Image without Directive

![bg](./images/car/car2.jpeg)

[Deckset - Background Images](https://docs.deckset.com/English.lproj/Media/01-background-images.html)

```mardown
![bg](./images/car/car1.jpeg)
```

---

## Blur Background

![bg blur](./images/car/car2.jpeg)

```mardown
![bg blur](./images/car/car2.jpeg)
```

---

## Sepia Image Background

![bg sepia:50%](./images/car/car2.jpeg)

```mardown
![bg sepia:50%](./images/car/car2.jpeg)
```

---

## Blur Background with 50% with sepia

![bg blur sepia:50%](./images/car/car2.jpeg)

```mardown
![bg blur sepia:50%](./images/car/car2.jpeg)
```

---

## Multiple Background Image

<!-- _color: white -->

![bg](./images/car/car1.jpeg)

![bg](./images/car/car2.jpeg)

![bg](./images/car/car3.jpeg)

![bg](./images/car/car4.jpeg)

![bg](./images/car/car5.jpeg)

---

## Multiple Background Image [Markdown]

```markdown
<!-- color: white -->

![bg](./images/car/car1.jpeg)

![bg](./images/car/car2.jpeg)

![bg](./images/car/car3.jpeg)

![bg](./images/car/car4.jpeg)

![bg](./images/car/car5.jpeg)
```

---

## Multiple Vertical BG Image

<!-- _color: white -->

![bg vertical](./images/car/car1.jpeg)

![bg](./images/car/car2.jpeg)

![bg](./images/car/car3.jpeg)

![bg](./images/car/car4.jpeg)

![bg](./images/car/car5.jpeg)

---

## Multiple Vertical Background Image [Markdown]

```markdown
<!-- _color: white -->

![bg vertical](./images/car/car1.jpeg)

![bg](./images/car/car2.jpeg)

![bg](./images/car/car3.jpeg)

![bg](./images/car/car4.jpeg)

![bg](./images/car/car5.jpeg)
```

---

## Multiple BG Blur Image

<!-- _color: white-->

![bg blur](./images/car/car1.jpeg)

![bg blur](./images/car/car2.jpeg)

![bg blur](./images/car/car3.jpeg)

![bg blur](./images/car/car4.jpeg)

![bg blur](./images/car/car5.jpeg)

---

## Multiple BG Blur Image [Markdown]

```markdown

<!-- _color: white-->

![bg blur](./images/car/car1.jpeg)

![bg blur](./images/car/car2.jpeg)

![bg blur](./images/car/car3.jpeg)

![bg blur](./images/car/car4.jpeg)

![bg blur](./images/car/car5.jpeg)

```

---

## Background Fit Image

![bg fit](./images/car/car2.jpeg)

```markdown
![bg fit](./images/car/car2.jpeg)
```

---

## Split Slides

![bg left](./images/car/car2.jpeg)

Use the `left` or `right` modifiers to place the image in the left or right half of the slide, respectively.

```markdown
![bg left](./images/car/car2.jpeg)
```

---

## Background on Right

![bg right](./images/car/car2.jpeg)

- Topic 1
- Topic 2
- Topic 3
- Topic 4

---

## Background Fit on right

![bg right fit](./images/car/car2.jpeg)

Combine `left` or `right` with the `fit` keyword or a percentage to adjust the image scaling.

```markdown
![bg right fit](./images/car/car2.jpeg)
```

---

![bg right](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)

## Split + Multiple BGs

The space of a slide content will shrink to the left side.

---

![bg left:25%](https://picsum.photos/720?image=27)

## Split backgrounds with specified size

---

## Image filters

Image filters

![bg blur:10px](./images/car/car2.jpeg)
![bg brightness:1.5](./images/car/car2.jpeg)
![bg contrast:200%](./images/car/car2.jpeg)
![bg drop-shadow:0,5px,10px,rgba(0,0,0,.4)](./images/car/car2.jpeg)
![bg grayscale:1](./images/car/car2.jpeg)
![bg hue-rotate:180deg](./images/car/car2.jpeg)
![bg invert:100%](./images/car/car2.jpeg)
![bg opacity:.5](./images/car/car2.jpeg)
![bg saturate:2.0](./images/car/car2.jpeg)
![bg sepia:1.0](./images/car/car2.jpeg)

---

## Image filters (Markdown)

```markdown
![bg blur:10px](./images/car/car2.jpeg)
![bg brightness:1.5](./images/car/car2.jpeg)
![bg contrast:200%](./images/car/car2.jpeg)
![bg drop-shadow:0,5px,10px,rgba(0,0,0,.4)](./images/car/car2.jpeg)
![bg grayscale:1](./images/car/car2.jpeg)
![bg hue-rotate:180deg](./images/car/car2.jpeg)
![bg invert:100%](./images/car/car2.jpeg)
![bg opacity:.5](./images/car/car2.jpeg)
![bg saturate:2.0](./images/car/car2.jpeg)
![bg sepia:1.0](./images/car/car2.jpeg)
```

---

## Hex color (White BG + Black text)

![bg](#fff)
![](#000)

```markdown
![bg](#fff)
![](#000)

#MD045/no-alt-text in markdownlint
```

---

## Named color (rebeccapurple BG + White text)

![bg](rebeccapurple)
![](white)

```markdown
![bg](rebeccapurple)
![](white)

#MD045/no-alt-text in markdownlint
```

---

## RGB values (Orange BG + White text)

![bg](rgb(255,128,0))
![](rgb(255,255,255))

```markdown
![bg](rgb(255,128,0))
![](rgb(255,255,255))
```

---

## Math typesetting

$ax^2+bc+c$

```markdown
$ax^2+bc+c$
```

---

## Math typesetting (Center)

$$I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx$$

```markdown
$$I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx$$
```

---

## Auto-scaling for code blocks

```sh
Too long code block will be scaled-down automatically. ------------>
```

```sh
Too long code block will be scaled-down automatically. ------------------------>
```

```sh
Too long code block will be scaled-down automatically. ------------------------------------------------>
```

```sh
Too long code block will be scaled-down automatically. ---------------------------------------------------------------------------->
```

---

## Simple header

## <!--fit--> Auto-fitting header

Auto-fitting header (only for Marp Core)
is available by annotating <!--fit--> in headings.

```markdown
## Simple header

## <!--fit--> Auto-fitting header
```

---

<!-- Scoped style -->
<style scoped>
h2 {
  color: blue;
}
</style>

## Using Style CSS

```markdown

<!-- Scoped style -->
<style scoped>
h2 {
  color: blue;
}
</style>

## Using Theme CSS
```
