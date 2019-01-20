# 我的 macOS 工作機軟體清單與環境設定分享

## 安裝軟體清單

### 整體環境

* Alfred
* Contexts

### 常用開發工具
### 生產力工具
### 寫作軟體



## 使用 Homebrew 管理軟體的安裝、升級


### mas-cli

### Homebrew-bundle & Brewfile


範例：
  * [我的 Brewfile](linyiru/dotfiles/blob/master/Brewfile)


## Shell 環境

## 開發環境


在 vscode 啟用 Vim 模式後利用 `hjkl` 移動游標時速度很慢，要用以下指令（To disable the press and hold for VSCode only）
或是全域關閉特殊字元的輸入（To disable the Character Accent Menu）

```shell
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```

```shell
defaults write -g ApplePressAndHoldEnabled -bool false
```
