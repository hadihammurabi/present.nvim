# `present.nvim`

Hey, this is a plugin for presenting markdown files!!

# Features: Neovim Lua Execution

Can execute code in lua blocks, when you have them in a slide

```lua
print("Hello world", 37, true)
```

# Features: Other Langs

Can execute code in Language blocks, when you have them in a slide.

You may need to configure this with `opts.executors`, only have Python and Javascript by default.

```python
print("yaayayayaya python")
```

# Installation

### [vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'tjdevries/present.nvim'
```

### [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use {
  'tjdevries/present.nvim'
}
```

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
    'tjdevries/present.nvim'
}
```

# Usage

```lua
require("present").start_presentation {}
```

Use `n`, and `p` to navigate markdow slides.

Or use `:PresentStart` Command

# Credits

teej_dv
