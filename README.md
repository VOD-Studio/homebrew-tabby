# homebrew-tabby

[tabby](https://github.com/VOD-Studio/tabby) 的 Homebrew tap：mihomo（Clash.Meta）内核的终端界面。

```sh
brew install vod-studio/tabby/tabby-mihomo
```

从发布 tag 的源码构建，不带 quarantine 属性。包名是 `tabby-mihomo`，装好的命令是 `tabby`。不附带内核：tabby 首次启动时会自己下载，也可以用 `brew install mihomo` 装的那份。

公式由 tabby 仓库的 `make brew`（`scripts/brew.sh`）生成，源文件是 `packaging/homebrew/tabby-mihomo.rb`。发布新版本时，把它复制到这里的 `Formula/` 再推送。
