# git-status

## 目錄
- [回目錄](../SUMMARY.md)

***

## 0. 前置準備 - 安裝 git

### Windows
- git for windows：[https://git-for-windows.github.io/](https://git-for-windows.github.io/)

### Mac
- git osx installer：[http://sourceforge.net/projects/git-osx-installer/](http://sourceforge.net/projects/git-osx-installer/)

### Linux
- Fedora
// 於終端機貼上以下指令
```
yum install git-core
```

- Debian based(Ubuntu)
// 於終端機貼上以下指令
```
apt-get install git
```

## 1. git 設定初始化

以下指令會`全域地`設定你在 git 中顯示的使用者名稱以及 Email，同時也會讓 git 幫輸出的訊息上色。請依序複製並把以下三行指令貼到終端機中。

![](../img/git-init-1.png)

// 設定使用 git commit/git log 時顯示的使用者名稱
```
git config --global user.name "你的名字"
```

// 設定使用 git commit/git log 時顯示的信箱
```
git config --global user.email "你的信箱"
```

// 設定使用 git status 時把輸出結果彩色劃
```
git config --global color.ui auto
```

要開始使用 git 基本上只需要這些設定，[git config 技巧](../git-conifg/index.md) 章節中會在介紹其他常用的設定選項。

*** 

## 2. git init

首先，請先在你喜歡的地方（路徑中不能含有中文名稱）建立一個空的資料夾，命名為 `git-test`。

![](../img/git-init-2.png)

- Mac/Ubuntu 使用者打開終端機後輸入以下指令：
// 切換至家目錄
```
cd ~
```

// 建立 `git-test` 資料夾
```
mkdir git-test
```

// 切換至剛建立好的資料夾
```
cd git-test
```

// 建立 git repository
```
git init
```


- Windows 使用者打開終端機後輸入以下指令：
// 切換至根目錄
```
cd C:
```

// 建立 `git-test` 資料夾
```
mkdir git-test
```

// 切換至剛建立好的資料夾
```
cd git-test
```

// 建立 git repository
```
git init
```

完成之後會出現如下畫面，表示 git repository 已經在 `git-test` 資料夾初始化成功，我們可以開始新增檔案。

![](../img/git-init-2.png)


## 下一頁
- [回目錄](../SUMMARY.md)
- [git clone](../git-clone/index.md)