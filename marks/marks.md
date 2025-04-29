# 🔖 Marks in Vim?
> Marks allow us to save position in a file (or across files) so we can quickly jump back to them later.

- **Useful for:-**
    - Navigating large files
    - Working on multiple locations
    - Jumping between definitions and uses
    - Temporary bookmarks

- **Types of Marks** 
    1. User-defined Marks(**`a-z`**)
        - Set with:  **`m{a-z}`**
        - Use with:
            - **`'[a-z]`** or **``` `[a-z] ```** 
        - **Scope:** Current file only
        - **Reset when**: The file is closed
    
    2. User-defined Marks(**`A-Z`**)
        - Set with:  **`m{A-Z}`**
        - Use with:
            - **`'[a-z]`** or **``` `[A-Z] ```** 
        - **Scope:** **All files**
        - **Reset when**: Vim exits(unless using a plugin lke viminfo or shada)

    3. Automatic Marks
        - Set by: Vim automatically
        - Use with: Same as other marks
        - **Common automatic marks:**
            - `[` : Start of last changed/yanked text
            - `]` : End of last changed/yanked text
            - `<` : Start of last visual selection
            - `>` : End of last visual selection

## 🛠️ Helpful Commands forManaging Marks
| Command | Purpose |
|---------|---------|
| `:marks` | Show all current marks |
| `:delmarks a` | Delete marka |
| `:delmarks a-d` | Delete marks a through d |
| `:delmarks!` | Delete all marks |


## 🚀 Jumping to Marks
| Command | Description |
|---------|-------------|
| `'a` | Jump to the start of the line of mark a |
| `` `a `` | Jump to the exact position (line + column) of mark a |
| `'A` / `` `A `` | Jump to global mark A |
| `''` | Jump to the previous cursor line |
| ``` `` ``` | Jump to the previous cursor position |

