# 🖥️ Mac Setup

This setup guide was created to streamline repetitive tasks when setting up a new Mac or switching to a new device. It is written based on Apple Silicon (M1/M2/M3, etc.), not Intel Macs.

> Adjust the configuration as needed.

<br/><br/>

# 🍺 Homebrew

Install Homebrew.

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

<br/>

Install the required packages.

```shell
brew install git
brew install wget
brew install curl
brew install tree
brew install htop
brew install --cask iterm2

brew install zsh
brew install fzf
brew install ripgrep
brew install bat
brew install exa
brew install jq
brew install fd
brew install tldr
brew install watch

brew install httpie
brew install telnet
brew install netcat
brew install mtr

brew install nvm
brew install pyenv
brew install rbenv
brew install openjdk

brew install docker
brew install docker-compose
brew install --cask docker
```

<br/><br/>

# 🖥️ Shell

Install oh-my-zsh. For other shells, install the corresponding framework or plugin manager.

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

<br/>

Add prompt and plugin settings.

```shell
PROMPT='$ '
unset RPROMPT

ZSH="$HOME/.oh-my-zsh"
plugins=(git)
source $ZSH/oh-my-zsh.sh
```

<br/>

Apply the updated configuration.

```shell
source ~/.zshrc
```

<br/><br/>

# 🚀 Tools

Download the required tools.

- [Adobe](https://www.adobe.com/home?acomLocale=kr)
- [Discord](https://discord.com/)
- [Docker](https://www.docker.com/)
- [draw.io](https://www.drawio.com/)
- [HHKB](https://happyhackingkb.com/download/)
- [IntelliJ](https://www.jetbrains.com/idea/)
- [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
- [Notion](https://www.notion.com/ko/desktop)
- [Postman](https://www.postman.com/)
- [PyCharm](https://www.jetbrains.com/ko-kr/pycharm/download/?section=mac)
- [Slack](https://slack.com/intl/ko-kr/)
- [Sublimetext](https://www.sublimetext.com/)
- [VSCode](https://code.visualstudio.com/download)
- [Zoom](https://support.zoom.com/hc/ko/article?id=zm_kb&sysparm_article=KB0060411)

<br/><br/>

# 📱 App

Download the required application.

- [Confluence](https://apps.apple.com/kr/app/confluence-cloud/id1006971684)
- [Flow](https://apps.apple.com/kr/app/flow-%EB%BD%80%EB%AA%A8%EB%8F%84%EB%A1%9C-%EC%A7%91%EC%A4%91-%EC%8B%9C%EA%B0%84%EA%B4%80%EB%A6%AC-%EA%B3%B5%EB%B6%80-%ED%83%80%EC%9D%B4%EB%A8%B8/id1423210932)
- [Magnet](https://apps.apple.com/kr/app/magnet/id441258766?mt=12)
- [Jira](https://apps.apple.com/kr/app/jira-cloud-by-atlassian/id1006972087)
- [RunCat](https://apps.apple.com/kr/app/runcat/id1429033973?mt=12)
- [XCode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

<br/><br/>

# ⚙️ IDE

JetBrains IDEs store their settings in version-specific directories. Check which IDE versions are installed with the following command.

```shell
ls ~/Library/Application\ Support/JetBrains/
```

<br/>

For example, if you are using IntelliJ IDEA 2025.1, you can check the keymap, codestyles, templates configuration files as follows.

```shell
# keymap
cat ~/Library/Application\ Support/JetBrains/IntelliJIdea2025.1/keymaps/macOS\ copy.xml
```

```shell
# codestyles
cat ~/Library/Application\ Support/JetBrains/IntelliJIdea2025.1/codestyles/Default.xml
```

```shell
# templates 
cat ~/Library/Application\ Support/JetBrains/IntelliJIdea2025.1/templates/Java.xml
```

