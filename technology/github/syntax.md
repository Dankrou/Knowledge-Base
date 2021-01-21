# Syntax

# Headers
```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag"
```
## Result
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag"

# Emphasis
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

## Result
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

# Lists
## Unordered
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  ```
## Ordered
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

## Result
## Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
## Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

# Images
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

## Result
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

# Links
```
http://github.com - automatic!
[GitHub](http://github.com)
```

## Result
http://github.com - automatic!
[GitHub](http://github.com)

# Blockquotes
```
As Kanye West said:

> We're living the future so
> the present is our past.
```

## Result
As Kanye West said:

> We're living the future so
> the present is our past.

# Inline code
```
I think you should use an
`<addr>` element here instead.
```

## Result
I think you should use an
`<addr>` element here instead.

# GitHub Flavored Markdown

# Syntax highlighting
```
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
.``` 
```

## Result
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
``` 

# Task Lists
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

## Result
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

# Tables
### Table 1
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
### Table 2
~~~
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
~~~
### Table 3
~~~
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
~~~
### Table 4
~~~
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |
~~~

## Result
### Table 1
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
### Table 2
You can use formatting such as links, inline code blocks, and text styling within your table:
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
### Table 3
You can align text to the left, right, or center of a column by including colons : to the left, right, or on both sides of the hyphens within the header row.
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
### Table 4
To include a pipe | as content within your cell, use a \ before the pipe:
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |

# SHA references
```
Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.
```

## Result
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

# Issue references within a repository
```
Any number that refers to an Issue or Pull Request will be automatically converted into a link.
```

## Result
#1
mojombo#1
mojombo/github-flavored-markdown#1

# Username @mentions
```
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.
```

## Result
@Dankrou

# Automatic linking for URLs
~~~
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.
~~~

## Result
http://www.github.com

# Strikethrough
~~~
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.
~~~

## Result
~~this~~

# Emoji
```
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: 
```

## Result
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: 
