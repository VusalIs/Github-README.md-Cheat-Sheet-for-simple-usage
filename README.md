# Github-README.md-Cheat-Sheet-for-simple-usage

This cheat sheet will help you to create simple structured README.md files which is one of the main things to show your code more understandle for others.

#### List of topics

- [Introduction](#Introduction)
- [Headers](#Headers)
- [Lists](#Lists)
    - [Unordered Lists](#-unordered-lists)
    - [Ordered Lists](#-ordered-lists)
- [Add links to the text(Add README.md references)](#add-links-to-the-text)
- [Images](#images)
- [Table](#table)
- [Tips](#tips)

# Introduction

Writing code and push it to the GitHub is a great thing for either starting to programming or contribute to society. But if you wanna show what you have done during the process and explain to others how to use it, a great thing to express yourself. In this guide, I will show you Markdown which will help you write the README section in a sophisticated way. Firstly let's look at two examples. First one will be written without any Markdown, and  the second one uses styling and make life easier for readers(I have taken this section from https://github.com/expressjs/express):

##### First 

This is a Node.js module available through the
npm registry.

Before installing, download and install Node.js.
Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a `package.json` first with
the npm init.

Installation is done using the
npm install:

#### Second



This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a `package.json` first with
the [`npm init` command](https://docs.npmjs.com/creating-a-package-json-file).

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):


Which one is good? I thing, I is time to start ;)

# Headers

Headers are used for highlight main topics which you wanna talk about. There are 6 types of headers.

```html
# h1 
## h2 
### h3 
#### h4 
##### h5 
###### h6
```

# h1

## h2

### h3

#### h4

##### h5

###### h6

# Lists

There are 2 tpyes of lists - ordered and unordered.

### Unordered Lists

To create an unordered list you have to use '-' sign at the beginning of every line and add a space after the sign.

```html
- First item 
- Second item 
- Third item
```

-   First item
-   Second item
-   Third item

To add list inside of another list, you should do the same with longer space (<kbd> TAB </kbd>)

```html
- First item 
    - First item of First 
    - Second item of First 
- Second item 
    - First item of Second 
    - Third item
```

-   First item
    -   First item of First
    -   Second item of First
-   Second item
    -   First item of Second
-   Third item

### Ordered Lists

We do the same thing with numbers:

```html
1. First item 1. Second item 1. Third item
```

1. First item
1. Second item
1. Third item


# Add links to the text

Adding urls to the text, you should do following

> [text]\(https://yoururl.com)

If you want to add reference to your README.md file, you should add `#` sign in the url part and add your header with `-` sign instead of space with lowercase.

> [My Header]\(#my-header)


> \## My Header

```html

[Go to google.com](http://google.com)

[Your Reference Example](#reference-example)

#### Reference Example
```


[Go to google.com](http://google.com)

[Your Reference Example](#reference-example)

#### Reference Example
Example text should be located here

# Inline styling

Different styling techniques is below:

```html
Normal
**Bold**
*Italic*
~~Strikethrough~~
For keyboard buttons:
<kbd> TAB </kbd>
For 1 line higlight
> This is line higlight
```
Normal

**Bold**

*Italic*

~~Strikethrough~~

<kbd> TAB </kbd>

> This is line higlight

Additionally you can use code blocks and inline code to clearly indicate code parts. In the code block, you can indicate which programming language is used in the code block, and it will highlight some parts like in the IDE and will help people to understand the code easily. You can indicate name of the programming language after *```* sings(Example: html, javascript, java etc).

```html
For inline code:

Please change color with `Color.setColor(Colors.red);`

For code block:

```javascript

console.log("Hello");
```This part will look highlighted.



```

Please use to change color `Color.setColor(Colors.red);`

```javascript

console.log("Hello");
```

# Images

Adding photo is similar to adding urls to the file. Only difference is you should add `!` sign in front of everthing, add default text(which will be shown if the image will not be found), add image url, and title of image which will be shown if mouse hovers the image.

```html
![default text](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSBVRugawdgDKMHP2bZR-xEnAGMVX5G3BQg4Dz-LGONZ_Bhqkec&usqp=CAU 'That is a hover title')

![default text](http://wrongurl 'That is a hover title')
```

![default text](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSBVRugawdgDKMHP2bZR-xEnAGMVX5G3BQg4Dz-LGONZ_Bhqkec&usqp=CAU 'That is a hover title')



![default text](http://wrongurl 'That is a hover title')


# Table

Example table is the simplest one.

```html

| Header | Header | Header |
| :------ | :------: | ------: |
| Body   | Body   | Body   |
```

| Header | Header | Header |
| :------ | :------: | ------: |
| Body   | Body   | Body   |



# Tips

- When you wanna use any any of them please pay special attention to spacing.
- Techniques which are mentioned here is not only way and you can go deeper by yourself.
