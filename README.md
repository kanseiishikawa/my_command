# 自作のコマンド

## gp_check
git pushを間違った方向にしないように作った。  
.zshrcに以下を追加(正直他に方法がないかと思ってる)  
```
export PATH=$HOME/my_command:$PATH  
alias git='gp_check'  
compdef gp_check=git
```
