<!-- Headings -->
## Headings
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

<br/>
<br/>

---
## Emphasis
<!-- Italics -->
```md
*Italicized text*
_Also italicized text_
```
*Italicized text*

_Also italicized text_

<br/>

<!-- Bold -->
```md
**Bold**
```
**Bold** 

<br/>

<!-- Strikethrough -->
```md
~~Strikethrough~~
```
~~Strikethrough~~

<br/>
<br/>

<!-- Horizontal Line -->
---
## Horizontal Rule
```md
---
___

***
```
--- 
___
***

<br/>
<br/>

---
## Blockquote and Nested Blockquote
<!-- Blockquote -->
```md
> This is a blockquote.
```
> This is a blockquote.

<br/>

<!-- Nested blockquote -->
```md
> First line of text in a blockquote.
>> Nested line of text in a blockquote.
```
> First line of text in a blockquote.
>> Nested line of text in a blockquote.

<br/>
<br/>

<!-- Links -->
---
## Links

<!-- Link  -->
```md
[This is a link](http://www.example.com)
```
[This is a link](http://www.example.com)

<br/>

<!-- Link with a tooltip -->
```md
[Link with a tooltip, hover over me](http://www.example.com "tooltip")
```
[Link with a tooltip, hover over me](http://www.example.com "tooltip")

<br/>

<!-- Reference links -->
```md
This is a [reference style link][1]. Which is a reference to a link defined elsewhere in the document, usually at the bottom. This is another for the [second link][2]. Any link can be reused and the [link text][1] can be changed. Also a reference link doesn't need an explicit name, [like this] example.

[1]: http://www.example1.com
[2]: http://www.example2.com
[like this]: http://www.example3.com
```

This is a [reference style link][1]. Which is a reference to a link  defined elsewhere in the document, usually at the bottom. This is another for the [second link][2]. Any link can be reused and the [link text][1] can be changed. Also a reference link doesn't need an explicit name,  [like this] example.

[1]: http://www.example1.com
[2]: http://www.example2.com
[like this]: http://www.example3.com


<br/>
<br/>

---
## Lists
<!-- Ordered List -->
```md
1. First item
2. Second item
```
1. First item
2. Second item

<br/>

<!-- Unordered List -->
```md
* Item one
    * Item two
```
* Item one
    * Item two

<br/>

<!-- Task list -->
```md
* [x] Do
* [ ] Do not
* [ ] ~~Try~~
```
* [x] Do
* [ ] Do not
* [ ] ~~Try~~

<br/>
<br/>

<!-- inline code block -->
---
## Inline Code
```md
`<p></p>`
```
`<p></p>`

<br/>
<br/>

---
## Code blocks
<!-- Zsh block -->
````md
```zsh
npm install
```
````
```zsh
npm install
```

<br/>

<!-- JS Block -->
````md
```javascript
function add(num1, num2){
  return num1 + num2
}
```
````
```javascript
function add(num1, num2){
  return num1 + num2
}
```

<br/>

<!-- Python block -->
````md
```python
print("Hello world")
```
````
```python
print("Hello world")
```

<br/>
<br/>

<!-- Images -->
---
## Images
```md
![Halloween Sun](halloween_sun_2014.jpeg)
```
![Halloween Sun](halloween_sun_2014.jpeg)