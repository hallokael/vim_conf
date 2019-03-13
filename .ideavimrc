set guioptions-=T           " 隐藏工具栏
""map <F11> mpgg=G`p
""imap <F11> <esc>mpgg=G`pa
set guioptions-=m         " 隐藏菜单栏
source $VIMRUNTIME/vimrc_example.vim
source $VIMRUNTIME/mswin.vim
behave mswin
set t_Co=256
set history=400             " vim记住的历史操作的数量，默认的是20
syntax enable
syntax on
set go=
set autoread                " 当文件在外部被修改时，自动重新读取
set nu
set autoindent
"colorscheme murphy
set nocompatible
" 光标移动到buffer的顶部和底部时保持3行距离
set scrolloff=15
" 不要闪烁
set novisualbell


"字体
if (has("gui_running"))
    set guifont=Bitstream\ Vera\ Sans\ Mono\ 10
endif

set smartindent

set completeopt=longest,menu
set cmdheight=1
" history文件中需要记录的行数
set history=300
" 在处理未保存或只读文件的时候，弹出确认
set confirm
" 侦测文件类型
filetype on
" 载入文件类型插件
"
"
"
"
"o
filetype plugin on
" 为特定文件类型载入相关缩进文件
filetype indent on




" 保存全局变量
set viminfo+=!
" 语法高亮
syntax on

set backspace=2
"highlight StatusLine cterm=bold ctermfg=yellow ctermbg=blue
" 获取当前路径，将$HOME转化为~
function! CurDir()
    let curdir = substitute(getcwd(), $HOME, "~", "g")
    return curdir
endfunction
set numberwidth=3
:highlight LineNr guifg=#BBBBBB

filetype plugin indent on     " 开启插件
""autocmd GUIEnter * simalt ~x
""autocmd GUIEnter * call libcallnr("gvimfullscreen.dll", "ToggleFullScreen", 0)
map <c-u> <C-f>
map <c-i> <C-b>
" 自动设置目录为正在编辑的文件所在的目录
set ffs=unix,dos,mac " favor unix ff, which behaves good under bot Winz & Linux
set clipboard=unnamed,autoselect,exclude:cons\|linux "set clipboard
"使得注释换行时自动加上前导的空格和星号
noremap 0 ^
noremap - $
noremap <Enter> a<Enter><esc>
set timeout timeoutlen=50000 ttimeoutlen=50000
noremap <tab> a<esc>ddO
noremap <space> a<space><esc>
""map o $a<cr>
""map O k$a<cr>
noremap < <<
noremap > >>
set formatoptions=tcqro
" 禁止生成临时文件
set nobackup
set noswapfile
set ignorecase
"不要备份文件（根据自己需要取舍）
set nobackup
" 不要生成swap文件，当buffer被丢弃的时候隐藏它
setlocal noswapfile
set bufhidden=hide
" 启动的时候不显示那个援助索马里儿童的提示
set shortmess=atI
" 不让vim发出讨厌的滴滴声
set noerrorbells
""exec 'cd ' . fnameescape('C:\Users\hallokael\Desktop\')
highlight StatusLine guifg=Blue guibg=Gray
" "highlight StatusLineNC guifg=Yellow guibg=DarkBlue

set ts=4  "(注：ts是tabstop的缩写，设TAB宽4个空格)
set expandtab "把tab转换成空格
highlight search none
highlight incsearch none
set shiftwidth=4 "When auto-indenting, indent by this much.【1】

set softtabstop=4 "Make Vim treat <Tab> key as 4 spaces, but respect hard Tabs.

"call pathogen#infect()


set encoding=utf-8
set fileencodings=utf-8,chinese,latin-1
if has("win32")
    set fileencoding=chinese
else
    set fileencoding=utf-8
endif
language messages zh_CN.utf-8

"for ideaVim
noremap z :action AceAction<cr>
noremap J 5j
noremap K 5k
noremap H 5h
noremap L 5l
noremap U <C-r>
noremap mq mQ
noremap `q `Q
noremap mw mW
noremap `w `W
noremap me mE
noremap `e `E
noremap mr mR
noremap `r `R
noremap mt mT
noremap `t `T
noremap my mY
noremap `y `Y
noremap mu mU
noremap `u `U
noremap mi mI
noremap `i `I
noremap mo mO
noremap `o `O
noremap mp mP
noremap `p `P
noremap ma mA
noremap `a `A
noremap ms mS
noremap `s `S
noremap md mD
noremap `d `D
noremap mf mF
noremap `f `F
noremap mg mG
noremap `g `G
noremap mh mH
noremap `h `H
noremap mj mJ
noremap `j `J
noremap mk mK
noremap `k `K
noremap ml mL
noremap `l `L
noremap mz mZ
noremap `z `Z
noremap mx mX
noremap `x `X
noremap mc mC
noremap `c `C
noremap mv mV
noremap `v `V
noremap mb mB
noremap `b `B
noremap mn mN
noremap `n `N
noremap mm mM
noremap `m `M

