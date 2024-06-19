# My Lazy Vim Config 

My config for Lazy vim which is a config distribution for Neo vim.

# Installation Instructions
- Clone this repository in the `~/.config/` directory of your `linux` or `macOS` system.
- Rename the directory from `my-lazyvim-config` to `nvim` so that it can be identified by neovim as it's configuration

## Key findings since my switch to neovim from vscode : -

- To get the current info on LSP Servers, run the command `:LspInfo`

- To do search ( and replace too if you need it ), on a specific path, you can use the specter plugin which is part of Lazy Vim by default
    - You can trigger specter by this command : `<Leader>sr`.
    - Once triggered, it will open a new window where you can specify the search term and the path in which to search in.

- One very important change to make if you want to work with vim motions with maximum productivity is to remap `CAPSLOCK` key to the `Escape` key.
    - To do this on Mac OS you can do the following : -
        - Go to System Settings -> Keyboard -> Keyboard Shortcuts -> Modifier Keys
        - In the Modifier Keys popup remap `Capslock` to `Escape`

- To customize Lazy Vim / Neo Vim, you can add options in the `./lua/config/options.lua` file.
    - To view the default options that are already enable / setup by Lazy Vim you can go here : https://github.com/LazyVim/LazyVim/blob/main/lua/lazyvim/config/options.lua

- To enable vim motions in `zsh` shell, add the following line to your `.zshrc` file : `bindkey -v`
