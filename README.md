# EasySetup

## 主要特点

- 一键安装常用软件
- 可自定义软件列表,添加需要的应用
- 支持oh-my-zsh等工具的安装和配置
- 提供iTerm2、VSCode等工具的配色方案
- 这个项目使用Shell脚本实现自动化流程,对新手用户很友好。它节省时间,提高生产力,是配置新Mac系统的好帮手
- 这是一个为你的Mac自动安装软件的Bash脚本，让你抽出时间喝咖啡而不是把时间花费在下载和安装你需要的软件
- 如果还有其他建议欢迎提出

## 开始

1. 克隆本仓库到您的电脑 `git clone https://github.com/Daker-china/Daker-script.git`
2. 进入仓库目录，要执行安装，只需要执行`./brew_install_app_for_mac.sh`即可。如果提示此脚本没有运行权限，请执行`chmod u+x brew_install_app_for_mac.sh`

软件清单分两个，`brew_cask_app_list`为GUI软件包，`brew_cli_app_list`为CLI软件包，这二者都是数组。

## 如何添加自定义的软件包 🔥

这很简单，只需要改写`brew_install_app_for_mac.sh`里面的`brew_cask_app_list`和`brew_cli_app_list`这两个数组即可，你可以删除里面你不想要的软件包，你也可以在对应的数组里面加入你想要的软件包，注意分清GUI和CLI即可。

## 使用

> `./brew_install_app_for_mac.sh`

### iTerm2 + oh-my-zsh 安装配置

安装软件及相关命令
> `./install_oh_my_zsh.sh`

oh-my-zsh 配置文件
`.zshrc`

iTerm2 Dracula+ 主题文件
`Dracula+.itermcolors`

Terminal Dracula+ 主题文件
`Dracula+.terminal`

Terminal 默认配置文件
`Default.json`

VS Code 字体配置
`"Monaco, Meslo, Consolas, 'Courier New', monospace, 'SauceCodePro Nerd Font Mono'"`

Terminal && iTerm2 字体配置
`'SauceCodePro Nerd Font Mono'`

Terminal 效果预览
![Terminal](./img/Terminal.png)

iTerm2 效果预览
![iTerm2](./img/iTerm2.png)

VS Code 效果预览
![VS Code](./img/VS%20Code.png)
