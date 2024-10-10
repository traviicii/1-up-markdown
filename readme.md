# 1-UP Markdown Workshop {#top}


## Basic Markdown Syntax

## 1. Headers

There are 6 different sizes of headers denoted by 1-6 conescutive `#` symbols

**Example**:

> # Header Size 1
> ## Header Size 2
> ### Header Size 3
> #### Header Size 4
> ##### Header Size 5
> ###### Header Size 6

**Syntax:**
```md
# Header Size 1
## Header Size 2
### Header Size 3
#### Header Size 4
##### Header Size 5
###### Header Size 6
```


## 2. Emphasis

We can make things **bold**
```md
**bold**
```

We can make things *italic*
```md
*italic*
```

We can also ~~strikethrough~~
```md
~~strikethrough~~
```


We can ~~***also do this***~~!
```md
~~***also do this***~~
```


## 3. Lists

### Ordered

1. first thing
    1. this is important
    1. another important thing
        1. important thing about this thing
            1. Another thing?!
1. second thing
1. third thing

### Unordered

- one thing
- another thing
    - this is important about this thing

## 4. Links and Images

### Inserting a Link
[Back to the top (using custom tag)](#top) 
[Back to the top](#1-up-markdown-workshop-top)

[Poke API](https://pokeapi.co/)

### Inserting Images

![An image of Ditto](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/132.svg)

![](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/132.svg)

---

## Advanced Features

### Tables

**Syntax**
```md
| Parameter | Type | Description |
|---|---|---|
| `first_name` | `string` | Required |
| `email` | `string` | Required |
```

**Result**
```http
POST /api/user
```

| Parameter | Type | Description |
|---|---|---|
| `first_name` | `string` | Required |
| `email` | `string` | Required |


### Code `blocks`!

```
simple code block
pip install this
```

```python
def solution():
    this = "that"
    for i in range(0, 20, 2):
        print(i)
    return this
```

```bash
pip install flask
```

### Block Quotes

> A block quote could be a side note, further info about a certain step, perhaps a definition for something.

### Definitions

What is an ORM?
: An ORM is an Object relational Mapper that helps us  relate a coding language like Python into SQL queries.

**What is an ORM?**
> An ORM is an Object relational Mapper that helps us  relate a coding language like Python into SQL queries.