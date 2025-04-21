# 🗑️ Delete Commands
> It is used to delete characters, words, sentances from the editor. Vim provides several commands to do this.
## 📅 Table of Contents
- [Character-Based Deletion](#🔤-character-based-deletion)
- [Word-Based Deletion](#⭐-word-based-deletion)
- [Line and Paragraph Deletion](#⭐-line-and-paragraph-deletion)
- [Screen and Sentance Based](#⭐-screen-and-sentance-based)
- [Character and Line Range Deletion](#⭐-character-and-line-range-deletion)

## 🔤 Character-Based Deletion
| Command | Action |
|---------|--------|
| **`x`** | Delete character under cursor |
| **`X`** | Delete character before cursor |
| **`dl`** | Delete character under cursor (same as `x`) |
| **`dh`** | Delete character before cursor (same as `X`) |
| **`<n>x`** | Delete `n` characters forward |
| **`<n>X`** | Delete `n` characters backward |

## ⭐ Word-Based Deletion
| Command | Action |
|---------|--------|
| **`dw`** | Delete from cursor to **end of word** |
| **`dW`** | Delete to end of **WORD** |
 | `db` | Delete to **start** of word|
| **`dB`** or **`d$`** | Delete to **start** of WORD |
| **`de`** | Delete to **end** of word (includes word end) |
| **`dE`** | Delete to **end**


## ⭐ Line and Paragraph Deletion
| Command | Action |
|---------|--------|
| **`dj`** | Delete **current and next line** |
| **`dk`** | Delete **current and previous line** |
 | `d}` | Delete **end of paragraph** | 
| **`d{`** | Delete to **start of paragrpah** | 

## ⭐ Screen and Sentance Based
| Command | Action |
|---------|--------|
| **`d(`** | Delete to **start of sentance** |
| **`d)`** | Delete to **end of sentance** | 
 | `dL` | Delete to **buttom of screen** | 
| **`dM`** | Delete to **middle** of screen | 

## ⭐ Character and Line Range Deletion
| Command | Action |
|---------|--------|
| **`d0`** | Delete to **start of line** |
| **`d^`** | Delete to **first non-blank of line** | 
 | `d$` | Delete to **end of line** | 
| **`dG`** | Delete to **end of file** |
| **`dgg`** | Delete to **beginning of file** | 
| **`d<number>G`** | Delete from current line to line **`<number>`** | 