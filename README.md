## vim-tips
Get nice Vim tips from the community :)

[![asciicast](https://asciinema.org/a/NOsf2l2Wis07Pot5OMy5If3El.png)](https://asciinema.org/a/NOsf2l2Wis07Pot5OMy5If3El)

## Usage
```
:Tip
```

**If you want a tip at one keystroke, add this to your `.vimrc`**
```
nnoremap <F5> :Tip<CR>
```

**If you want a tip everytime you open Vim, add this to your `.vimrc`**
```
autocmd VimEnter * call Tip()
```

## Can I add my tip to the list?
Yes! Just open a PR with your tip on `tips.md`, following this structure:

    ```author
    First, add your name after the first ``` block. Don't add special chars here, please.

    Then just type your tip here :)

    You may add new lines or anything really, just make sure the tip is cool!
    ```

## Installation
vim-tips needs `curl` and `td`. If you on an Unix system, you should be fine. You can install it with your favorite plugin manager.

Plugin Manager  | Add to your `/.vimrc`
--------------- | --------------------------------------------------
NeoBundle       | `NeoBundle 'jonatasbaldin/vim-tips'`
Plug            | `Plug 'jonatasbaldin/vim-tips'`
Vundle          | `Plugin 'jonatasbaldin/vim-tips'`

*If you want to add Windows support, please contribute!*
