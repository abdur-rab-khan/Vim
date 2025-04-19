# ![Vim](https://img.icons8.com/?size=40&id=7XSgvKh878Kn&format=png&color=000000)  Vim Movements

- ### Table of Contents
- [Movements](#️-movement-commands)
    - [↗️ Movement Commands](#↗️-movement-commands)
    - [🖥️ Screen Movements](#️🖥️-screen-movements)
    - [🧭 Line Navigation](#🧭-line-navigation)
    - [🧾 Naviagate to Para & Sen](#🧾-paragraph--sentence)
    - [🔖 Marks & Jumps ](#🔖-mark--jump)


## ↗️ Movement Commands
> If you'r in insert mode you can use these commands. It is used to moving `cursor` around the text editor.

| Commands   | Description                                           |
|------------|-------------------------------------------------------|
| **`h`**        | **Move cursor left**                                      |
| **`j`**        | **Move cursor down**                                      |
| **`k`**        | **Move cursor up**                                        |
| **`0`** | **Move to the start of the line** |
| **`^`** | **Move to the first non-blank** |
| **`$`** | **Move to end of the line** |
| **`w`** | **Next word start** |
| **`W`** | **Next WORD start (WORD includes) puntuation** |
| **`b`** | **Begining of word** |
| **`B`** | **Begining of WORD (WORD includes puntuation)** |

## 🖥️ Screen Movements
| Commands | Actions |
|----------|---------|
| **`H`** | **Move to top of the screen** |
| **`M`** | **Move to middle of the screen** |
| **`L`** | **Move to buttom of the screen** |

## 🧭 Line Navigation
| Command | Actions |
|---------|---------|
| **`G`** | Go to **last** line |
| **`gg`**| Go to **first** line**|
| **`nG`**| Go to line number **`n`** |
| **`ngg`** | Same as above one |

## 🧾 Paragraph & Sentence
| Command | Action |
|---------|--------|
| **`{`** | Move to **previous paragraph** |
| **`}`** | Move to **next paragraph** |
| **`(`** | Move to **previous sentence** |
| **`)`** | Move to **next sentence** |

## 🔎 Search Based Movement
| Command | Action |
|---------|--------|
| **`/text`** | Search forward for `text` |
| **`?text`** | Search backword for `text` |
| **`n`** | Next match(in same direction)|
| **`N`** | Next match(opposite direction) |
| **`*`** | Search forward for word under cursor |
| **`#`** | Search backword for word under cusor |

## 🔖 Mark & Jump
| Command | Action |
|---------|--------|
| `'a` | Jump to the start of the line of mark a |
| `` `a `` | Jump to the exact position (line + column) of mark a |
| `'A` / `` `A `` | Jump to global mark A |
| `''` | Jump to the previous cursor line |
| **`'' or `` `** | Return to previous cursor location |
| **`ctrl + o`** | Go back (older cursor postion) |
| **`ctrl + i`** | Go forward(newer cursor position) |
