# 我的 macOS 工作機軟體清單與環境設定分享

## 安裝軟體清單

### 整體環境

* Raycast

### 生產力工具

* Visual Studio Code 搭配 vim 模式

### 筆記軟體

* LogSeq
* Obsidian
* Bear
* iA Writer
* Ulysses

偶爾也會直接在 vscode 裡面寫 Markdown。

### 通訊 & 協作

* Telegram
* Slack
* Asana
* Notion

### 其他常用軟體

* Fantastical 2
* 1Password

## 開發相關

### 開發用的軟體清單

* Visual Studio Code
* SnippetsLab
* Quiver
* Sourcetree
* iTerm 2


### Homebrew

使用 Homebrew 管理軟體的安裝、升級

#### mas-cli

#### Homebrew-bundle & Brewfile

#### Homebrew Cask & homebrew-cask-upgrade


範例：
  * [我的 Brewfile](https://github.com/linyiru/dotfiles/blob/master/Brewfile)


### Shell 環境

### 開發環境

在 vscode 啟用 Vim 模式後利用 `hjkl` 移動游標時速度很慢，要用以下指令（To disable the press and hold for VSCode only）
或是全域關閉特殊字元的輸入（To disable the Character Accent Menu）

```shell
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```

```shell
defaults write -g ApplePressAndHoldEnabled -bool false
```
