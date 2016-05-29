開発環境setup
===

Mac
---

### home brew

##### main

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

##### git

```
brew install git
```

##### openssl

```
brew install openssl
```

##### readline

```
brew install readline
```

##### wget

```
brew install wget
```

#### Middleware

##### mysql

```
brew install mysql
```

##### nginx

```
brew install nginx
```

#### ruby系

##### ansible

```
brew install ansible
```

##### ruby-build & rbenv

```
brew install ruby-build rbenv
```

### rbenvで最新のruby install

インストール可能なバージョン一覧を取得

```
rbenv install -l
```

安定版の2.3.1をインストール

```
rbenv install 2.3.1
```

標準で利用するバージョンを設定

```
rbenv global 2.3.1
```

### gemで環境構築

##### rails

```
gem install rails
```

##### bundler

```
gem install bundler
```

##### unicorn

```
gem install unicorn
```

### PATH設定

##### rubyのバージョンをrbenvで管理した場合の設定

```
PATH_RUBY=$HOME/.rbenv/shims
PATH=$PATH_RUBY:$PATH
```

Server
---


