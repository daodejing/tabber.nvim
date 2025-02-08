# tabber
*tabber* is a neovim plugin for tabs
It takes you back to your last tab when you close the current tab.
The default neovim behavior is to take you to the most recently created tab, which confused me.
So I made tabber.

## Installation
### Lazy
```lua
{
    "daodejing/tabber",
    config = true,
}
```

## Usage
Just close a tab and you will be taken to the last tab you were on.

## Background
I first felt the need for this plugin when was using multiple tabs and opened and closed the neogit tab.
I was taken back to the most recently created tab, and experienced a moment of confusion.
