[Ted Yu](https://teddata.github.io/)
================================

---

Firstly, the title must be in the format yyyy-mm-dd-double-hyphen-title.md.

The 1st line is: --- # This format cannot be changed.

The 2nd line is: layout: post # This format cannot be changed.

The 3rd line is: title: "How to write a post" # Title

The 4th line is: subtitle: "Using markdown to make a post" # Subtitle (optional)

The 5th line is: date: yyyy-mm-dd # This format cannot be changed.

The 6th line is: author: "Ted" # This format cannot be changed.

The 7th line is: header-style: text # This format cannot be changed.

The 8th line is: tags:
  - key 1
  - key 2
  ... # Replace "key" with relevant keywords

The last line is: --- # This format cannot be changed.

Then, leave a blank line, and after that, you can start writing content in markdown format.

The title format, for example:
```
---
layout: post
title: "How to write a post"
subtitle: 'Using markdown to make a post'
date: 2023-09-10
author: "Ted"
header-style: text
tags:
  - markdown
---
```

> Followed by content, which can be formatted using markdown.

For example:
```
> The type is very important!!!
```

When adding image addresses, you must use URLs and not local addresses. For example:
```
![](https://raw.githubusercontent.com/TedData/TedData.github.io/master/img/post-bg-web.jpg)
```



```sh
$ bundle install 
```

3. Serve the website (`localhost:4000` by default):

```sh
$ bundle exec jekyll serve  # alternatively, npm start
```

