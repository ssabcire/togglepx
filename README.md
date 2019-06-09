# tpa

tpaは**"toggle_proxy_automatically"**という意味で、自動でプロキシを切り替えてくれるバイナリです。

---
* [Features](#features)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
    * [Quick Start](#quick-start)

---

# features
このtpaバイナリは、ターミナルを起動させたときに、あなたの環境下のネットワークアドレスを判断し、
.gitconfigや.curlrcに記述されているProxy設定の行を、自動でコメント/コメントアウトして、gitコマンドやcurlができるようにします。  

---

## Installation
* **Goの開発環境があなたのPCに存在する場合**
```
go get github.com/ssabcire/spc
```
<br>

* **Goの開発環境があなたのPCに存在しない場合**  
Download a binary from [release page](https://github.com/ssabcire/spc/releases)
```
vim ~/.bashrc
<バイナリのPATHを記載>
```


---

## Usage
1. 切り替えたいファイルなどを記述するための~/.sfp/config.jsonを作成します。そのために、〜します。  
2. 次に、~/.sfp/config.jsonに、設定したいファイルと、ネットワークアドレスを書き込みます。  
例
```json
{
  {},
  {},
}
```

---

##Example
