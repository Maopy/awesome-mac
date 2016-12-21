# awesome-mac

> 得到了新的 Mac 之后，借着重新搭建开发环境，把用到的好用的东西做个记录。

## 基本环境

1. [Homebrew](http://brew.sh/index_zh-cn.html)

  更新 Homebrew 源
  
  ```bash
  
  # 替换 homebrew-core源
  cd "$(brew --repo)/Library/Taps/homebrew/homebrew-core"
  git remote set-url origin git://mirrors.ustc.edu.cn/homebrew-core.git
    
  # 替换 Homebrew Bottles源
  echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.ustc.edu.cn/homebrew-bottles' >> ~/.bash_profile
  source ~/.bash_profile

  brew update
    
  ```
  
2. [iterm2](https://www.iterm2.com/) + [zsh](https://www.zsh.org/) + [Oh my zsh](http://ohmyz.sh/)
  
  ```bash
  
  # 切换到zsh
  chsh -s /bin/zsh
  
  ```

## 触控板设置

1. 系统设置 -> 触控板 -> 光标与点按

  不选 `查询与数据检测器`
  
  选 `轻点来点按`
  
2. 辅助功能 -> 鼠标与触控板 -> 触控板选项

  启用拖移 `三指拖移`
