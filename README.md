# ncphi 

## Setup

```ssh
cd ~

git clone git@github.com:ncphillips/ncp-vim.git

echo "source ~/ncp-vim/vimrc" >> ~/.vimrc
echo "source ~/ncp-vim/zshrc" >> ~/.zshrc

sh ~/ncp-vim/install
```

## zsh commands

* `o`: Runs a function that opens a file picked from fzf in Vim.

## Vim Keybindings

**Legend**

* `C` : The `Ctrl` key
* `Leader` : The `,` key.

### Buffers

* **Reload:** `:e`
* **List Buffers:** `:ls`
* **Go To Buffer:** `:b <number>`
* **Delete Buffer:** `:bd`

### Files

* **Save:** `,w`
* **Quit:** `,q`
* **Save & Quit:** `,wq`
* **Rename File:** `,n`

### Navigating within Files

* **Page Forward:** `<C-f>`
* **Page Backward:** `<C-b>`
* **Half-Page Down:** `<C-d>`
* **Half-Page Up:** `<C-u>`

### File Browsing

* **Toggle NERDTree:** `<C-n>`
* **Help:** `?`
* **Open:** `<CR>`
* **Open in Tab:** `t`

### Search

Quick Options

* **Search File:** `,o`
* **Fulltext Search:** `,f`

Commands

* Search by Filename: `:Ag`
* Fulltext Search Files: `:Files`
* Search Commmits: `:Commits`

### Code

* **Autocomplete:** `<C-x C-o>`
* **Rename Symbol:** `,e`

#### Typescript

* **Go to def:** `<C-]>`
* **Go to use:** `<C-t>`
* **References:** `<C-^>`
* **Hint:** `,t`

### Ruby

* **Add Parameter:** `,rap`
* **Convert Post Conditional:** `,rcpc`
* **Extract Method:** `,rem`
* **Extract Local Variable:** `,relv`
* **Convert Conditional:** `,cc`

#### Rails

* **Go to Model:** `:Emodel site`
* **Go to Controller:** `:Econtroller sites`
* **Go to Code/Tests:** `:A`

### Vim Plugin System

* **Install Plugin:** `PlugInstall [name ...]`
* **Update Plugin:** `PlugUpdate [name ...]`
* **Upgrade vim-plug:** `PlugUpgrade`

## Plugins

* [vim-plug](https://github.com/junegunn/vim-plug): Plugin management
* [vim-sensible](https://github.com/tpope/vim-sensible): ???
* [seoul256.vim](https://github.com/junegunn/seoul256.vim): A color scheme.
* [vim-prettier](https://github.com/prettier/vim-prettier)
* [vim-surround](https://github.com/tpope/vim-surround)

### Typescript

* [tsuquyomi](https://github.com/Quramy/tsuquyomi): Typescript development
  support.
* [typescript-vim](https://github.com/leafgarland/typescript-vim):
  Typescript syntax highlighting
* [vim-jsx-typescript](https://github.com/peitalin/vim-jsx-typescript)
  : React JSX syntax highlighting Typescript.

### Ruby

* [vim-ruby](https://github.com/vim-ruby/vim-ruby): Ruby dev support.
  power tools
* [vim-rails](https://github.com/tpope/vim-rails): Ruby on Rails
* [vim-ruby-refactoring](https://github.com/ecomba/vim-ruby-refactoring): Ruby refactoring tools

### File Browsing

* [nerdtree](https://github.com/scrooloose/nerdtree)
* [nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin): Add git status to NERDTree browser.

### Git
* [airblade/vim-gitgutter](https://github.com/airblade/vim-gitgutter): Adds
  git diff (+/-) into the vim gutter.

### Search

* [fzf](https://github.com/junegunn/fzf)
* [fzf-vim](https://github.com/junegunn/fzf-vim)
* [ack.vim](https://github.com/mileszs/ack.vim')


## Potential Plugins 

I don't want to overload myself with too much information
so this is a list of plugins that I might add later.

* [fugitive-vim](https://vimawesome.com/plugin/fugitive-vim)
* [commentary.vim](https://vimawesome.com/plugin/commentary-vim)
* [vim-graphql](https://vimawesome.com/plugin/vim-graphql)
* [vim-styled-components](https://vimawesome.com/plugin/vim-styled-components-hard-things)
* [dispatch.vim](https://vimawesome.com/plugin/vim-dispatch)
