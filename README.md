# This is template files for vim
Please clone this project in `$HOME/.vim/`


.vimrc need like following settings:

```
augroup SkeletonAu
        autocmd!
        autocmd BufNewFile *.html 0r $HOME/.vim/template/tpl.html
        autocmd BufNewFile *.php 0r $HOME/.vim/template/tpl.php
        "autocmd BufNewFile *.pl 0r $HOME/.vim/skel.pl
        "autocmd BufNewFile *.pm 0r $HOME/.vim/skel.pm
augroup END
```

