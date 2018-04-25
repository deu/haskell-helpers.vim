# haskell-helpers.vim

Helpers for writing Haskell in Vim.

### Insert mode mappings

* Hit `C-y` once to insert the function name according to the last type signature above the cursor, hit it more to insert `=` and `undefined`

### Motions

* `]]` go to next function type declaration

* `[[` previous function type declaration

### Installation

- vim-plug `Plug 'deu/haskell-helpers.vim', { 'for': 'haskell' }`
