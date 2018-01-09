# Homebrew (un)installer
A Mainland China User-Friendly brew installer  
给brew加点油

[![Build Status](https://travis-ci.org/Homebrew/install.svg?branch=master)](https://travis-ci.org/Homebrew/install)

## 这是什么  
每次配置环境brew的都要下载半年，对新手太不友好了，来做一点微调
- 将默认repo来源设置为[TUNA清华大学的镜像源]（https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/)
- 反代一下github usercontent(不要滥用谢谢xD)

## Install Homebrew
```bash
/usr/bin/ruby -e "$(curl -fsSL https://githubusercontent.hfi.me/hfiprogramming/install/master/install)"
```

More installation information and options at http://docs.brew.sh/Installation.html.

## Uninstall Homebrew
```bash
/usr/bin/ruby -e "$(curl -fsSL https://githubusercontent.hfi.me/hfiprogramming/install/master/uninstall)"
```

Download the uninstall script and run `./uninstall --help` to view more uninstall options.
