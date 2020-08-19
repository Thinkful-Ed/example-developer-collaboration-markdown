You may be used to writing text documents using a program like Microsoft Word, Pages, or Google Docs. Software developers don't use tools like this, but still need formatting for writing documentation and issues. The most common format you'll find is markdown.

Markdown is used in a variety of places frequented by developers and has become more popular on more mainstream applications and websites as of late, including Slack and Reddit. By learning markdown, you'll be able to write text documents in the same editor you use to write code.

By the end of this checkpoint, you will be able to:

- Write markdown and use a variety of formatting.

---

## What is markdown?

---

**Markdown** is a way of writing text that, when read by an interpreter, formats that text to include style like headings, bold, and italics.

---

Markdown is a popular and powerful syntax that is used across the web. Most commonly, you'll be writing markdown to write `readme.md` files as well as formatting your GitHub Issues.

Markdown isn't complicated to learn but may require a bit of practice at first. In this checkpoint, you'll briefly learn some of the most common syntax specifically for GitHub. While most markdown interpreters work the same, you may notice minor differences depending on the website.

## Markdown syntax

In general, the GitHub "Mastering Markdown" guide is useful to have bookmarked until you feel comfortable with the syntax. Some syntax is used more often than others. The most common syntax is detailed below.

- [GitHub Guides: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

### Preview markdown

You can write markdown in Visual Studio Code and preview it there as well. To do so, open up the _command palette_ while a `.md` file is open by pressing `⌘ + Shift + P` for a Mac or `Ctrl + Shift + P` for a Windows machine.

Then, type in "Markdown: Open Preview" and select the applicable option.

### Do this

#### Practice writing markdown

Create a `.md` file on your computer and open it with VSCode. Then, open the markdown preview by using the instructions above. When you type text into your `.md` file, it should automatically update in the newly open tab or pane!

When learning the syntax below, use this file to practice each new piece of syntax.

### Headings

Document headings can be written using `#` symbols. A single `#` symbol represents an `h1` element on the page, while two `##` symbols represents an `h2`, and so on up to an `h6` element.

```md
### Headings
```

For example, the heading above is an `h3`.

### Paragraphs

To write a paragraph, you simply need to write text! If you want your text to be on a separate line, you'll need to enter down two spaces.

No other formatting is needed to write simple paragraphs.

```md
To write a paragraph, you simply need to write text! If you want your text to be on a separate line, you'll need to enter down two spaces.

No other formatting is needed to write simple paragraphs.
```

### Emphasis and bold

You can add _emphasis_ to text by wrapping the text in underscores, and bold text by adding **two asterisks** on either side of the bolded text.

```md
You can add _emphasis_ to text by wrapping the text in underscores, and bold text by adding **two asterisks** on either side of the bolded text.
```

Depending on the interpreter, this syntax can sometimes be different. For example, with GitHub flavored markdown the distinction is between a single `_` or `*` compared to two.

```md
You can add _emphasis_ to text by wrapping the text in underscores, and bold text by adding **two asterisks** on either side of the bolded text.
```

### Inline code blocks

You can write code inline by wrapping text in a backtick. This helps distinguish the code, like `let x = 10;` from other text.

```md
You can write code inline by wrapping text in a backtick. This helps distinguish the code, like `let x = 10;` from other text.
```

### Larger code blocks

For longer blocks of code, it's better to use the large code block syntax that uses three backticks to start and end the code block. You can also include the language to provide appropriate syntax highlighting.

<pre>
```javascript
function hello(name) {
  console.log("Hello, " + name + "!");
}
```
</pre>

The syntax above will look like this:

```javascript
function hello(name) {
  console.log("Hello, " + name + "!");
}
```

### Lists

You can write ordered lists by writing your start number followed by a period. On many platforms, you can actually just repeat this number and the interpreter will appropriately order it for you.

```md
1. Markdown
1. Is
1. Amazing
```

This will result in a list like the one below:

1. Markdown
1. Is
1. Amazing

You can also write unordered lists by using `-` or `*` with a space in front of it.

```md
- Markdown
- Is
- Amazing
```

This will result in a list like the one below:

- Markdown
- Is
- Amazing

### Links

Links can be written inline with a mix of `[]` and `()` symbols, like so:

```md
This is a link to [GitHub](http://github.com).
```

### Images

Images are nearly the same as links except they include a `!` at the front. The text between the `[]` symbols is the alt text that can be viewed by hovering over the image.

```md
![This is an image of a bear.](https://placebear.com/202/203)
```

The syntax above will result in the following.

![This is an image of a bear.](https://placebear.com/202/203)

---

## Complete example

The full markdown of this checkpoint can be seen at the link below. This demonstrates a number of the contents above as well as a few more.

- [Developer Collaboration: Markdown]()
