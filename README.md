# A repo only contains a MarkDown files
> Yea, I know that maybe this is not a very useful repository.

# Markdown formating

# Heading 1
`# Heading 1`

## Heading 2
`## Heading 2`

### Heading 3
`### Heading 3`

#### Heading 4
`#### Heading 4`

##### Heading 5
`##### Heading 5`

###### Heading 6
`###### Heading 6`

---

# Paragraph

text `Inline Code` text		
~~Mistaken text.~~	
*Italics*	
**Bold**	

```markdown
text `Inline Code` text		
~~Mistaken text.~~	
*Italics*	
**Bold**	
```

---

# Tasks

- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**
- [ ] incomplete
- [x] completed

```markdown
- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**
- [ ] incomplete
- [x] completed
```

---

# Code Blocks

    4 space indention
    makes full-width
    standard code blocks

```js
document.innerHTML = "I'm js code";

/* I'm comment */
```

```css
.css {
font-size: 25px;
width: 100%;
padding: 5px;
height: 50%;
color: #333;

/* I'm comment */
```

```markdown
    4 space indention
    makes full-width
    standard code blocks

```js
document.innerHTML = "I'm js code";

/* I'm comment */
```

```css
.css {
font-size: 25px;
width: 100%;
padding: 5px;
height: 50%;
color: #333;

/* I'm comment */
```
```

---

# List

* List item one
* List item two
    * A nested item

```markdown
* List item one
* List item two
    * A nested item
```

---

# Numbered List

1. Number list item one		
	1.1. A nested item
2. Number list item two
3. Number list item three

```markdown
1. Number list item one		
	1.1. A nested item
2. Number list item two
3. Number list item three
```

---

# Quote

> Quote
> 
> Second line Quote

```markdown
> Quote
> 
> Second line Quote
```


---

Standard link =  https://igorkowalczyk.github.io <br>
[Custom Text Link](https://igorkowalczyk.github.io)

```markdown
Standard link =  https://igorkowalczyk.github.io
[Custom Text Link](https://igorkowalczyk.github.io)
```

---

# Image

![Image](https://igorkowalczyk.github.io/lib/favicon/favicon.jpg)

```markdown
![Image](https://igorkowalczyk.github.io/lib/favicon/favicon.jpg)
```

---

# Table

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

```markdown
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
```