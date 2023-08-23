First thing to know : markdown ignores line endings.

In normal text, a line break needs two trailing spaces.

So :
```markdown 
This will show up as
a single line.
```

This will show up as
a single line.

```markdown
This is *italic* text.
This is also _italic_ text.
```

This is *italic* text.
This is also _italic_ text.


```markdown
This is **bold** text.
This is also __bold__ text.
```

This is **bold** text.
This is also __bold__ text.

```markdown
_This is **italic and bold** text_ using a single underscore for italic and double asterisks for bold.
__This is bold and *italic* text__ using double underscores for bold and single asterisks for italic. 
```

_This is **italic and bold** text_ using a single underscore for italic and double asterisks for bold.
__This is bold and *italic* text__ using double underscores for bold and single asterisks for italic. 

```markdown
_This is __italic and bold__ text_ using a single underscore for italic and double underscores for bold.
__This is bold and _italic_ text__ using double underscores for bold and single underscores for italic. 
```

_This is __italic and bold__ text_ using a single underscore for italic and double underscores for bold.
__This is bold and _italic_ text__ using double underscores for bold and single underscores for italic. 

The quick fox jumed over the lazy dog.

```markdown
\_This is all \*\*plain\*\* text\_.
```

\_This is all \*\*plain\*\* text\_.

```markdown
###### This is H6 text
```

###### This is H6 text

```markdown
![Link an image.](https://learn.microsoft.com/learn/azure-devops/shared/media/mara.png)
```

![Link an image.](https://learn.microsoft.com/learn/azure-devops/shared/media/mara.png)

```markdown
![Link an image.](file:///mara.png)
```

![Link an image.](file:///mara.png)

```markdown
![Link an image.](file:///plant.png)
```

```markdown
![Link an image.](file:///plant.svg)
```

A ordered list
```markdown
1. First
1. Second
1. Third
```

Will show up as
1. First
1. Second
1. Third

An onordered list allows nesting
```markdown
- First
  - Nested
- Second
- Third
```

Aan will display as
- First
  - Nested
- Second
- Third

Comments will not be shown at all :  
``` markdown
[//]: # (This is a comment.)  
[//]: # (This is a comment on a new line.)  
```

There is nothing to see below this line  

[//]: # (This is a comment.)  
[//]: # (This is a comment on a new line.)  

Make sure add a double space after each comment line and an empty line after the "normal" text.
