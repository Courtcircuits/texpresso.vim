# TeXpresso.vim
Neovim mode for TeXpresso

Installation:
1. Install [TeXpresso](https://github.com/let-def/texpresso).
   If installation is successful, you should have `texpresso` binary in your PATH.
2. Clone [TeXpresso.vim](https://github.com/let-def/texpresso.vim.git), and make sure it is in Neovim runtime path.
   For instance:
   ```shell
   $ cd ~/.config/nvim
   $ mkdir start
   $ cd start
   $ git clone https://github.com/let-def/texpresso.vim.git
   ```

Usage:
1. Open a `.tex` file. Launch the viewer:
   `:TeXpresso <path/to/main.tex>` (e.g. `:TeXpresso %` if the current file is the root)
2. The viewer should let you preview the `.tex` file.
   It should track your position in the buffer (when the cursor moves), and
   any change to the buffer should be reflected quickly in the preview window.

TODO:
- report errors/warnings in vim quickfix buffer
- allow customization: theme, cursor synchronizaiton, bindings, stay-on-top, ..
- simplify initialization, respect Neovim conventions, make code more robust

## Screenshots

Launching TeXpresso in vim:

https://github.com/let-def/texpresso.vim/assets/1048096/b6a1966a-52ca-4e2e-bf33-e83b6af851d8

Live update during edition:

https://github.com/let-def/texpresso.vim/assets/1048096/cfdff380-992f-4732-a1fa-f05584930610

Using Quickfix window to fix errors and warnings interactively:

https://github.com/let-def/texpresso.vim/assets/1048096/e07221a9-85b1-44f3-a904-b4f7d6bcdb9b

Synchronization from Document to Editor (SyncTeX backward):

https://github.com/let-def/texpresso.vim/assets/1048096/f69b1508-a069-4003-9578-662d9e790ff9

Synchronization from Editor to Document (SyncTeX forward):

https://github.com/let-def/texpresso.vim/assets/1048096/650ee9ea-39ad-451a-85d3-5474016e5a8f

Theming, Light/Dark modes: 😎


