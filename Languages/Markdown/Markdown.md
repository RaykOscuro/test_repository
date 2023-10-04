_Markdown_ is a lightweight markup language for creating formatted text using a plain-text editor. ^816513

# Table of Contents
1. [[#Important Code To Know]]
	1. [[#Headings]]
	2. [[#Italic and Bold text]]
## Important Code To Know

### Headings
- You can create headings by using one or more \#-signs
### Italic and Bold text
- Add *single* or **double** \*-symbols around the text
### Lists
- Just start with 1. (ordered list) or - (non-ordered) and keep going)
### Links
- You can create external links by using these: \[*link text*\](*link*)
	- It's gonna look like this: [Google](https://google.com)

- You can create internal links by using these: \[\[*Node name*\]\]
	- It's gonna look like this: [[Basics of Web Development]]

- You can also link to a specific point in another node by using this: \[\[*Node name*#^*reference*\]\]
	- It's gonna look like this: [[Basics of Web Development#^796e47]]

- You can also show parts of other nodes with this \!\[\[*Node name*#^*reference*\]\]
	 ![[Basics of Web Development#^796e47]]
### Block Quotes
- You can create block quotes by using the \>-sign

>Wow, it's a block quote!
>Very impressive!

- You can also create info or warning blocks, just add \[!info] or \[!warning] after the \>-sign

>[!info] So much Information!
>Unbelievable!

>[!warning] This is a warning!
>Better take care...

### Code Segments in Markdown
- You can use the \`-symbol to mark single lines of code, like this:
	- `<iframe src=https://google.com></iframe>`

- Or you can triple it up to write code blocks:
```html
<html>
<iframe src=https://google.com></iframe>
</html>
```