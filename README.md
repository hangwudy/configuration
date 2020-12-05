# configuration

## anaconda不显示（base）

`conda config --set auto_activate_base false`

## anaconda修改默认源

恢复默认源：

`conda config --remove-key channels`

换源：

(清华源)

`conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/`

`conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge`

`conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/`


`conda config --set show_channel_urls yes`


## conda 查看环境信息：
`conda env list`

## conda 克隆环境
`conda create -n BBB(new env) --clone AAA(target)`

## pip修改默认源
`pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple`
