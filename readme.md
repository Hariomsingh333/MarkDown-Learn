# Date: 12 / 2 / 2022

# Lear how to write markdown doc

---

![markdown img](https://www.markdownguide.org/assets/images/markdown-guide-og.jpg)

## What is markdown?

It is a lightweight markup language. So markdown is a style of writing a document that makes it easy to define what the content should look like, it describes **headers text formatting links list** and so much more

Markdown is used all over the place it’s used in the documentation, articles, _notes_

## Headings

In markdown, we have 6 heading variations.

```md
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## Horizontal Rule ---

This is horizontal Rule

```md
---
```

---

It separates Content

## Text Formating

paragraph line spacing in important.

```md
<!-- put two space line for paragraph line spacing -->

this is

how we

space between

those line
```

this is

how we

space between

those line

### italic and bold text

<!-- italic: * | _ bold: ** -->

```md
_italic text_
**bold text**
**_bold and italic both at the same time_**
```

## list

ordered list

we can use the number for ordered list 1,2,

```md
1. first list
2. second list
3. third list
4. fourth list
   and so on so for
```

1. first list
2. second list

unordered list

for unordered list we use -

```md
- uno list
- uno list
```

- uno list
- uno list

## Code formating

### for inline code formating we use backtick``

```md
this is `console.log()` a js print statement
```

this is `console.log()` a js print statement

### code block

we use three backtick for code block ``` and the name of you programming language

````md
```js
console.log("hello world");
```

```py
print("hello world")
```

```java
system.out.println("hello world")

```
````

---

```js
console.log("hello world");
```

```py
print("hello world")
```

```java
system.out.println("hello world")

```

## Blockquote

for blockquote we use grater then symbol >

```md
> this is a blockquote
```

> this is a blockquote

## Links

links follow the convention you have square brackets [] and then parentheses () within the square brackets is going to be the text you'll see, then within the parentheses is the actual link

i can add a space and then within quotation marks "" i could add a alt tag or title

```md
[youtube.com](https://www.youtube.com "go to youtube")
```

[youtube.com](https://www.youtube.com "go to youtube")

### create reference link

```md
[youtube]: https://www.youtube.com "link for yt"
```

```md
[youtube][youtube]
```

## images

we use the same thing that we used for link but use the exclamation point ! mark in the first

```md
<!-- img -->

![img](https://www.img.com)
```

## Task list

[ ] it's mean not complete , [x] it's mean complete

```md
- [ ] not yet
- [x] yes
```

- [ ] not yet
- [x] yes
