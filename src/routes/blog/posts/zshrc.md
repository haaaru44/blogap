---
title: zshrcにFlutterコマンドショートカットを追加😇
date: 2020-07-31T21:51:00.000Z
---

よく使いそうな Flutter コマンドのエイリアス(alias)を追加。#メモ

<!-- more -->

## <a name="top"></a> Table of Contents

- [FlutterAlias](#FlutterAlias)
- [GitHubAlias](#GitHubAlias)

---

# <a name="FlutterAlias"></a>Flutter

# FlutterAlias

git のエイリアスをコピペしてきたらかなり便利だったので
Flutter コマンドのショートカットを作りました

<h2>.zshrcに追加</h2>
<code>
#エイリアス：Flutter<br>alias f='flutter'
<br>alias fd='flutter doctor'
<br>alias fu='flutter upgrade'
<br>alias fr='flutter run'
<br>alias frd='flutter run --debug'
<br>alias frr='flutter run --release'
<br>alias fdv='flutter devices'
<br>alias fcr='flutter create'
<br>alias fcl='flutter clean'
<br>alias fpg='flutter pup get'
</code>

変更後は<br>
<code>source ~/.zshrc </code>

[[Top]](#top)

# <a name="GitHubAlias"></a>GitHub

参考にした git<br>
<code> #エイリアス: git 系
<br>alias g='git'
<br>alias gs='git status'
<br>alias gb='git branch'
<br>alias gc='git checkout'
<br>alias gct='git commit'
<br>alias gg='git grep'
<br>alias ga='git add'
<br>alias gd='git diff'
<br>alias gl='git log'
<br>alias gcma='git checkout master'
<br>alias gfu='git fetch upstream'
<br>alias gfo='git fetch origin'
<br>alias gmod='git merge origin/develop'
<br>alias gmud='git merge upstream/develop'
<br>alias gmom='git merge origin/master'
<br>alias gcm='git commit -m'
<br>alias gpo='git push origin'
<br>alias gpom='git push origin master'
<br>alias gst='git stash'
<br>alias gsl='git stash list'
<br>alias gsu='git stash -u'
<br>alias gsp='git stash pop'
</code>

[[Top]](#top)
