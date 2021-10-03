# 自作のコマンド

## gp_check
git pushを間違った方向にしないように作った。  
.zshrc  
```
alias git='gp_check'  
compdef gp_check=git
```
