+++
title = "Markdown Test"
date = "2022-01-01"
updated = "2022-05-01"

[taxonomies]
tags=["example"]
+++

# H1

## H2

### H3

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Aliquet sagittis id consectetur purus ut. In pellentesque massa placerat duis ultricies. Neque laoreet suspendisse interdum consectetur libero id. Justo nec ultrices dui sapien eget mi proin. Nunc consequat interdum varius sit amet mattis vulputate. 

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Aliquet sagittis id consectetur purus ut. In pellentesque massa placerat duis ultricies. Neque laoreet suspendisse interdum consectetur libero id. Justo nec ultrices dui sapien eget mi proin. Nunc consequat interdum varius sit amet mattis vulputate. Sollicitudin tempor id eu nisl nunc mi ipsum. Non odio euismod lacinia at quis. Sit amet nisl suscipit adipiscing. Amet mattis vulputate enim nulla aliquet porttitor lacus luctus accumsan. Sit amet consectetur adipiscing elit pellentesque habitant. Ac placerat vestibulum lectus mauris. Molestie ac feugiat sed lectus vestibulum mattis ullamcorper velit sed. [Google](https://www.google.com)

![Markdown Logo](https://markdown-here.com/img/icon256.png)

## Code Block

```rust
fn main() {
    println!("Hello World");
}
```

```rust,hl_lines=2,linenos
fn main() {
    println!("Hello World");
}
```

## Ordered List

1. First item
2. Second item
3. Third item

## Unordered List

- List item
- Another item
- And another item

## Nested list

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Quote

> Two things are infinite: the universe and human stupidity; and I'm not sure about the
> universe.<br>
> — <cite>Albert Einstein</cite>

## Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |


## Table Inline Markdown


| Italics   | Bold     | Code   | StrikeThrough     |
| --------- | -------- | ------ | ----------------- |
| _italics_ | **bold** | `code` | ~~strikethrough~~ |


## Complex tables

<table>
  <thead>
    <tr>
      <th></th>
      <th colspan="3">Singular</th>
      <th colspan="3">Plural</th>
    </tr>
    <tr>
      <th>Case</th>
      <th>Masculine</th>
      <th>Feminine</th>
      <th>Neuter</th>
      <th>Masculine</th>
      <th>Feminine</th>
      <th>Neuter</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Nom.</th>
      <td>lang<b>ur</b></td>
      <td>löng</td>
      <td rowspan="2" style="vertical-align: middle">lang<b>t</b></td>
      <td>lang<b>ir</b></td>
      <td rowspan="2" style="vertical-align: middle">lang<b>ar</b></td>
      <td rowspan="2" style="vertical-align: middle">löng</td>
    </tr>
    <tr>
      <th>Acc.</th>
      <td>lang<b>an</b></td>
      <td>lang<b>a</b></td>
      <td>lang<b>a</b></td>
    </tr>
    <tr>
      <th>Dat.</th>
      <td>löng<b>um</b></td>
      <td>lang<b>ri</b></td>
      <td>löng<b>u</b></td>
      <td colspan="3" style="text-align: center">löng<b>um</b></td>
    </tr>
    <tr>
      <th>Gen.</th>
      <td>lang<b>s</b></td>
      <td>lang<b>rar</b></td>
      <td>lang<b>s</b></td>
      <td colspan="3" style="text-align: center">lang<b>ra</b></td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th></th>
      <th colspan="3">Singular</th>
      <th colspan="3">Plural</th>
    </tr>
    <tr>
      <th>Case</th>
      <th>Masculine</th>
      <th>Feminine</th>
      <th>Neuter</th>
      <th>Masculine</th>
      <th>Feminine</th>
      <th>Neuter</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Nom.</th>
      <td>lang<b>i</b></td>
      <td>lang<b>a</b></td>
      <td
        rowspan="4"
        style="text-align: start; vertical-align: middle"
      >lang<b>a</b></td>
      <td
        rowspan="4" colspan="3"
        style="text-align: center; vertical-align: middle"
      >löng<b>u</b></td>
    </tr>
    <tr>
      <th>Acc.</th>
      <td rowspan="3" style="vertical-align: middle">lang<b>a</b></td>
      <td rowspan="3" style="vertical-align: middle">löng<b>u</b></td>
    </tr>
    <tr>
      <th>Dat.</th>
    </tr>
    <tr>
      <th>Gen.</th>
    </tr>
  </tbody>
</table>

## Foldable Text

<details>
    <summary>Title 1</summary>
    <p>IT'S A SECRET TO EVERYBODY.</p>
</details>

<details>
    <summary>Title 2</summary>
    <p>Stay awhile, and listen!</p>
</details>

## Code tags

Lorem ipsum `dolor` sit amet, `consectetur adipiscing` elit.
`Lorem ipsum dolor sit amet, consectetur adipiscing elit.`

## Footnotes

Footnote 1 link[^first].

Footnote 2 link[^second].

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.

## Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

## Horizontal rules


Three or more...

---

Hyphens

***

Asterisks

___

Underscores

## Github Style Alerts

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
